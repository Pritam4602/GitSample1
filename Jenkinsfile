pipeline {
    agent any

    stages{
        stage('Development') {
            steps {
                echo 'Hello World - Development'
                bat 'git clone "https://github.com/Pritam4602/GitSample1.git"'
            }
        }
    
        stage('QA') {
            steps {
                echo 'Hello World-QA'
            }
        }
    
    
    
        stage('UAT') {
            steps {
                echo 'Hello World-UAT'
            }
        }
    
    
        stage('PrePod') {
            steps {
                echo 'Hello World - Prepod'
            }
        }
    
    
        stage('Prod') {
            steps {
                echo 'Hello World - Prod'
            }
        }
    }
}
