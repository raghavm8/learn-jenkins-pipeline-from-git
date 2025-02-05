pipeline {
    agent any
    stages {
        stage("Compile") {
            steps {
                echo "Compiling code"
                sh "javac Sample.java"
            }
        }

        stage("Run") {
            steps {
                echo "Running code"
                sh "java Sample"
            }
        }
    }
}