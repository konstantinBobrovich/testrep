pipeline {
    agent {
        node {
            label 'test-agent'
        }
    }
    stages {
        stage('Clone Test') {
            steps {
                echo "Hello world, KB" >> test.txt
                echo "fromfile:"
                cat test.txt
            }
        }
    }
}
