pipeline {

agent {
   docker { dockerfile true }
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

