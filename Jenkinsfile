properties([pipelineTriggers([cron('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Stage_1') {
            steps {
                sh '''
                    ls -la
                    python3 hello.py
                    '''
            }
        }
    }
}
