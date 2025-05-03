pipeline {
    agent any
    stages {
        stage('Start') {
            steps {
                echo 'Début du Pipeline'
            }
        }
        stage('Run a Task') {
            steps {
                bat 'echo Ceci est une commande Windows' 
            }
        }
        stage('End') {
            steps {
                echo 'Fin du Pipeline'
            }
        }
    }
}
