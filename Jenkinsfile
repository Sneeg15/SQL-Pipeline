pipeline {
    agent any 
        
    stages {
        stage('verification'){
            steps{
              echo "Hi"
                }  
            }
        stage('Connect MariaDB'){
            steps{
                sh 'mariadb -u jenkins -proot test_db'
            }
        }
    }
}
