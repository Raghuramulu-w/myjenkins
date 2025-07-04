pipeline {
    agent {
    node {
        label 'myagent-1'
        
    }
}
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }


post { 
        always { 
            echo 'Iam sying Hello again!'
        }
    }
}


