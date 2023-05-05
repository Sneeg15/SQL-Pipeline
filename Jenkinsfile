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
                sh 'sudo mariadb -proot test_db'
            }
        }
    }
}
