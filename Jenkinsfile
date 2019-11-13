pipeline {
    agent { docker { image 'elunic/node-angular-chrome:node12-angular8' } }
    stages {
        stage('test') {
            steps {
                sh 'npm i'
                sh 'npm run test:ci'
            }
        }
    }
}
