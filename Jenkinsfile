pipeline {
    agent any
    stages {
        stage('exercise 1') {
            steps {
                sh '''
                   chmod +x ./scripts/exercise1.sh
                   ./script/exercise1.sh
                '''
            }
        }
        stage('exercise 2') {
            steps {
                sh '''
                    chmod +x ./scripts/exercise2.sh
                    ./script/exercise2.sh
                '''
            }
        }
    }
}
