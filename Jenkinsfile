echo"This is a jenkins file "
pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                echo "Build Stage starts ...."
                sh 'pwd'
                sh 'ls'
                sh 'cd jenkinbasicdemo'
                sh 'sudo npm install' 
                sh 'sudo npm run build'
            }
        }
    }
}
