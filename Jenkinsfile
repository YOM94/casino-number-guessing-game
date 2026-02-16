pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                bat 'rm -rf build'
                bat 'cmake -B build -S .' 
                bat 'cmake --build build'
            }
        }
    }
}