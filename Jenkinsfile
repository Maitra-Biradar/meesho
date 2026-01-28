pipeline {
    agent any
    
    tools {
        maven 'maven'
    }
    
    stages {
        stage("Build the WAR file") {
            steps {
                sh "mvn clean package"
            }
        }
    }
}
