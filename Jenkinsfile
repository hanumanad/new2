pipeline {
    agent any

    stages {
        stage('Compile Stage') {
            steps {
           withAnt(ant : 'apache-ant-1.10.3')
            sh 'ant war'
                   }
           }
    }
}