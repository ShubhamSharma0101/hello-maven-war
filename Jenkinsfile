pipeline {
    agent any

    stages {
        stage('Get Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/ShubhamSharma0101/hello-maven-war.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
