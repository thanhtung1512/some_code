pipeline{
    agent {
        label "master"
    }
 
    stages {
        stage('echo') {
            steps {
                echo 'hello'
            }
        }
        stage ('after') {
            steps {
                echo 'after step'
            }
        }
    }
}
