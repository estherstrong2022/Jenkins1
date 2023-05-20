pipeline {
    agent any
    stages{
        stage('first') {
            steps {
                echo 'my first pipeline'
            }
        }
        stage('second'){
            steps {
                echo 'my second stage'
            }
        }
        stage('third'){
            steps {
                echo 'my third stage'
            }
        }
    }
}
