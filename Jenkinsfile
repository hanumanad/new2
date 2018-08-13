pipeline {
    agent any

    stages {
        stage('Compile Stage') {
            steps {
           withAnt(installation: 'apache-ant-1.10.3', jdk: 'jdk1.8.0_172') {
            sh 'ant war'
                   }
             }
           }
    }
}