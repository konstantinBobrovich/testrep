pipeline {
    agent {
        node {
            label 'test-agent'
        }
    }
    stages {
        stage('Test') {
            steps {
                echo "Hello world, KB" >> test.txt
            }
        }
    }
}
