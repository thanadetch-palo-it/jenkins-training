pipeline {
    agent any
    stages {
        stage('exercise 1') {
            steps {
                sh '''
                    grep -o -i devops example.txt | wc -l
                '''
            }
        }
        stage('exercise 2') {
            steps {
                sh '''
                    sed -e 's/devops/Hello_World/g' example.txt
                    echo example1.txt
                '''
            }
        }
    }
}
