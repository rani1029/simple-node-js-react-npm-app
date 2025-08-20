pipeline {
    agent any
    stages {
        stage('install dependencies') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Build') {
            steps {
                // If your app has a build script in package.json
                sh 'npm run build'
            }
        }
    }
}
