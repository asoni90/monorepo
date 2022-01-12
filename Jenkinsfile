node {
  //def ret = sh(script: '${env.BRANCH_NAME}', returnStdout: true)
  stage('Checkout') {
    checkout scm
  }
  
  def ret = sh(script: "echo ${env.BRANCH_NAME} | cut -d '-' -f2", returnStdout: true)
  stage('Print ENV') {
    sh "echo ${ret}"
    sh "echo ${env.BRANCH_NAME}"
  }
}
