pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'Development'
                bat 'git clone https://github.com/AnushkaD26/ToDoList_app.git'
            }
            
        }
        
        stage('QA') {
            steps {
                echo 'QA'
            }
            
        }
        stage('UAT') {
            steps {
                echo 'UAT'
            }
            
        }
        stage('Pre prod') {
            steps {
                echo 'Pre Prod'
            }
            
        }
        stage('Prod') {
            steps {
                echo 'Prod'
            }
            
        }
    }
}
