pipeline {
    agent any
    stages {
        stage('Clone sources') {
            steps {
                git branch: 'main', url: 'https://github.com/SphinxPL/CICD-jenkins.git'
            }
        }
    }
    
}