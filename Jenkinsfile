pipeline {
    agent any        
    stages {
        
        stage("Check Node Version"){
            steps {
                sh "node --version"
            }
        }
        stage("install dependencies"){
            steps {
                sh "npm --version"
                sh "npm install"
            }
        }
        stage("Test"){
            steps {
                echo "node app.js"
            }
        }
        stage("Release the version"){
            steps {
                echo "Release the Version"
            }
        }

    }
}