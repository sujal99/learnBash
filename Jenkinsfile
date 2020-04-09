pipeline {
    agent { label 'master' }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
		sh './test1.sh'
            }
        }
    }
}
