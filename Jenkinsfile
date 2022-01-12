pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
              echo "${env.BRANCH_NAME}"
              echo "${env.CHANGE_BRANCH}" 
            }
        }
    }
}
