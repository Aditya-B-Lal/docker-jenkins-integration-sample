pipeline {
    agent any
    environment {
        registry ='9526584898/helloworld'
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage ('Docker Build'){
            steps {
                dockerImage=docker.build registry
            }
        
            
    }
}
