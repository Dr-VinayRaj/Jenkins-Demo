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
                bat '"C:\\Users\\admin\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe" app.py'
            }
        }
    }
}
