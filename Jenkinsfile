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
                    ls -ls
                    sed -e 's/devops/Hello World/g' example.txt
                    echo example1.txt
                '''
            }
        }
    }
}
