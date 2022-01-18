pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
              echo "Hello $GIT_BRANCH"
              echo "This is $CHANGE_ID"
              echo "this is $CHANGE_BRANCH"
              echo "There is $CHANGE_TARGET" 
            }
        }
    }
}
