pipeline {
    agent { 
    node {
    label 'java && dev'
    customWorkspace '/home/Family/javaproject' 
    }
    
    } 
    stages {
        stage('Build') {
            steps {
                //
                echo "Build-1"
            }
        }
        stage('Test') {
            steps {
                //
                echo "Test"
            }
        }
        stage('Deploy') {
            steps {
                //Deploy
                echo "Deploy"
            }
        }
    }
}
