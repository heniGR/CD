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
                sh "ansible-playbook myApp/ansible/ansible/build.yml -i myApp/ansible/inventory/host.yml "
                      }
        	   
        	     }  
                         }
      
           }
         }