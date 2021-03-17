pipeline {

docker { image 'python' }
    stages {
        stage('Test') { 
            steps {
                 echo "*******testing************"
                sh 'python -m pytest'
            }
        }
}
}

