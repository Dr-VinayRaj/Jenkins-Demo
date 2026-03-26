pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Run') {
            steps {
                echo 'Running application...'
                bat 'cd /d "G:\\1. NIT Trichy\\ByteXL\\PEP 9P 158 - 161\\Jenkins Demo" && python app.py'
            }
        }
    }
}
