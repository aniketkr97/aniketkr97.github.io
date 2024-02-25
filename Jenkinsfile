pipeline {
    agent any

    stages {
        stage('Hello Stage') {
            steps {
                sh 'echo $BUILD_NUMBER'
                sh 'echo $BRANCH_IS_PRIMARY'
                sh 'echo $CHANGE_URL'
                sh 'echo $CHANGE_BRANCH'
                sh 'echo $CHANGE_ID'
                sh 'echo $CHANGE_TARGET'
                sh 'echo $CHANGE_TITLE'
                sh 'echo $CHANGE_URL'
            }
        }
    }
}

