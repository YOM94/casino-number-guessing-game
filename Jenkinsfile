pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'if exist build rmdir /s /q build'
                bat 'cmake -B build -S .'
                bat 'cmake --build build'
            }
        }
    }
}
