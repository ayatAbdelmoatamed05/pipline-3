pipeline {
    agent any

    stages {
        stage('Run Script 1') {
            steps {
                sh 'chmod +x hello1.sh'
                sh './hello1.sh'
            }
        }

        stage('Run Script 2') {
            steps {
                sh 'chmod +x hello2.sh'
                sh './hello2.sh'
            }
        }
    }
}

