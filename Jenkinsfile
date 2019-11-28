Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'Python:2.7.15' } }
    stages {
        stage('build') {
            steps {
                sh 'python -V'
            }
        }
    }
}