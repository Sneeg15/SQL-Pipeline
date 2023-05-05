pipeline {
    agent {label 'linux'}
        
    stages {
        stage('verification'){
            steps{
              echo "Hi"
                }  
            }
        stage('Connect MariaDB'){
            steps{
                sh 'sudo mariadb -u root -proot test_db'
            }
        }
    }
}
