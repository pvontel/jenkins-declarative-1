pipeline {
    agent any
    stages {
        stage ('SCM') {
            steps {
                git branch: 'main', url: 'https://github.com/rajulucky812/jenkins-Declarative.git'
            }
        }
        stage ('Build Artifact') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
