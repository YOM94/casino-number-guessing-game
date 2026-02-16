pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'if exist build rmdir /s /q build'
                bat 'cmake -G "MinGW Makefiles" -B build -S .'
                bat 'cmake --build build'
            }
        }
    }
}
