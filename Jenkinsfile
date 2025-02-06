pipeline {
    agent any
    stages {
        stage("Compile") {
            steps {
                echo "Compiling code"
                bat "javac Sample.java"
            }
        }

        stage("Run") {
            steps {
                echo "Running code"
                bat "java Sample"
            }
        }
    }

    post {
        always {
            echo "always text ...."
        }

        success {
            echo "success text ...."
        }

        failure {
            echo "failure text ...."
        }
    }
}