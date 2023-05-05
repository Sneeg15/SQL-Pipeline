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
                sh 'mariadb -u root -proot test_db'
            }
        }
    }
}
