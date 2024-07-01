pipeline {
agent none
    stages {
        stage('SCM') {
           steps {
                echo "pull the source code from git hub repo"
           }
        }
        stage('build') {
           steps {
                echo "code is build & deployed"
           }
        }
        stage('test') {
           steps {
                echo "application is working fine"
           }
        }
        stage('SCM') {
           steps {
                echo "pull the source code from git hub repo"
           }
        }
}
}