pipeline {
    agent any

    stages {
       
        stage('Build') {
            steps {
                sh "${tool name: 'clean package', type: 'maven'}/bin/mvn package"
            }
        }
        stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
   
}
