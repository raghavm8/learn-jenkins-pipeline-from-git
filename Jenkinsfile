pipeline {
    agent any
    stages {
        stage("Compile") {
            echo "Compiling code"
            sh "javac Sample.java"
        }

        stage("Run") {
            echo "Running code"
            sh "java Sample"
        }
    }
}