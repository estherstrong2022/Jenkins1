pipeline {
    agent none
    stages{
        stage('first') {
            agent any
            steps {
                echo 'my first pipeline'
            }
        }
        stage('second'){
            agent any
            steps {
                echo 'my second stage'
            }
        }
        stage('third'){
            agent any
            steps {
                echo 'my third stage'
            }
        }
    }
}
