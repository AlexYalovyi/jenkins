//Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:lts' } }
    stages {
        stage('build') {
            steps {
                sh 'npm run start'
            }
        }
    }
}