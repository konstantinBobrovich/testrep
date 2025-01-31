pipeline {
    agent {
        node {
            label 'test-agent'
        }
    }
    stages {
        stage('Test') {
            steps {
                bat 'echo Hello world, KB > test.txt'
                bat 'type test.txt
            }
        }
    }
}
