pipeline {
    agent {
        node {
            label 'test-agent'
        }
    }
    stages {
        stage('build') {
            steps {
                bat 'echo Hello world, KB > test.txt'
            }
        }
        stage('Test') {
            steps {
                bat 'type test.txt'
            }
        }
    }
}
