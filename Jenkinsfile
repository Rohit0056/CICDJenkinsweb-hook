pipeline {
  agent any
  stages{
   stage('1st STAGE'){
     steps {
         git branch: 'main', url: 'https://github.com/Rohit0056/CICDJenkinsweb-hook.git' 
   } 
  }
stage('2nd STAGE'){
     steps {
         sh 'sudo apt install apache2 -y' 
   } 
  }
stage('3rd STAGE'){
     steps {
         sh 'sudo cp -R index.html /var/www/html/' 
   } 
  }
 }
}
