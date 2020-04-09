pipeline {
    agent { label 'master' }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
		sh 'bash ./test1.sh'
            }
        }
    }
}
