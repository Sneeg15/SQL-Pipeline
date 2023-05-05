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
                sh 'mariadb -proot test_db'
            }
        }
    }
}
