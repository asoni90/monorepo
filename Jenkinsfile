pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo "Hello $GIT_BRANCH"
                echo "This is ${env.CHANGE_ID}"
                echo "this is ${env.CHANGE_BRANCH}"
                echo "There is ${env.CHANGE_TARGET}" 
            }
        }
    }
}
