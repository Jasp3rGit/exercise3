pipeline {
    agent none
    stages {
        stage('Parallel Execution') {
            parallel {
                stage('Job 1') {
                    agent {
                        docker { image 'jenkins/inbound-agent' }
                    }
                    steps {
                        echo 'Running Job 1'
                        sh 'sleep 10'
                    }
                }
                stage('Job 2') {
                    agent {
                        docker { image 'jenkins/inbound-agent' }
                    }
                    steps {
                        echo 'Running Job 2'
                        sh 'sleep 10'
                    }
                }
                stage('Job 3') {
                    agent {
                        docker { image 'jenkins/inbound-agent' }
                    }
                    steps {
                        echo 'Running Job 3'
                        sh 'sleep 10'
                    }
                }
                stage('Job 4') {
                    agent {
                        docker { image 'jenkins/inbound-agent' }
                    }
                    steps {
                        echo 'Running Job 4'
                        sh 'sleep 10'
                    }
                }
            }
        }
    }
}
