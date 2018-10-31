pipeline {
    agent {
        node {
            label 'master'
        }
    }
    stages {
        stage('Compile Stage') {
            steps {
           withAnt(installation: 'apache-ant-1.10.3') {
            sh 'ant war'
                   }
             }
  }
  stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
	}
	}
    
