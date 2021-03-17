pipeline {

agent {
   docker { image 'pytest-docker' }
}
    stages {
        stage('Test') { 
            steps {
                 echo "*******testing************"
                sh 'python -m pytest'
            }
        }
}
}

