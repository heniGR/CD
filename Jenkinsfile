pipeline{
    agent any
   // tools {
     //   maven 'M2_HOME'
       //   }
    stages {
        stage('Pulling') {
        	steps{
        	
        	git branch: 'master',
        	url : 'https://github.com/heniGR/EmptyProject.git'
              script{
                    
                    sh "ansible-playbook etc/ansible/build.yml -i ansible/inventory/host.yml -e ansible_become_password=root "
                }
        	   
        	     }  
                         }
      
           }
         }