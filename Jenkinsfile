pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'echo Hello World'
                bat 'javac world.java'
                bat 'java solution'
            }
        }
    }
}
