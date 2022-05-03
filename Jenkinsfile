echo"This is a jenkins file "
pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                echo "Build Stage starts ...."
                cd /jenkinsbasicdemo
                sh 'npm install' 
            }
        }
    }
}
