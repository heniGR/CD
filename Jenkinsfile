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
                sh "ansible-playbook C:\Users\heni\Desktop\myApp\myApp\ansible\ansible\build.yml -i C:\Users\heni\Desktop\myApp\myApp\ansible\inventory\host.yml "
                      }
        	   
        	     }  
                         }
      
           }
         }