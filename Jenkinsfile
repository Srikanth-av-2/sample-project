pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Srikanth-av-2/sample-project.git'
            }
        }
        
        stage('testing feature') {
            steps {
                echo "testing"
            }
        }
        
        stage('build feature') {
            steps {
                echo "building"
            }
        }
        stage('deploy') {
            steps {
                echo "application deployed to feature server"
            }
        }
    }
}
