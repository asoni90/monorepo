node {
  //def ret = sh(script: '${env.BRANCH_NAME}', returnStdout: true)
  stage('Checkout') {
    checkout scm
  }
  
  stage('Print ENV') {
    sh "echo ${env.BRANCH_NAME}"
  }
}
