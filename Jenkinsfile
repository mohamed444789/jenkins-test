pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
		git branch: 'main', url: 'https://github.com/mohamed444789/jenkins-test'
            }
        }

        stage('Build') {
            steps {
                echo 'Running build step...'
                sh 'chmod +x hello.sh && ./hello.sh'
            }
        }
    }
}
