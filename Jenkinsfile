node {
  //def ret = sh(script: '${env.BRANCH_NAME}', returnStdout: true)
  stage('Checkout') {
    checkout scm
  }
  
  def ret = sh(script: "echo ${env.BRANCH_NAME} | cut -d '-' -f2", returnStdout: true)
  def br = sh(script: 'git rev-parse --abbrev-ref HEAD', returnStdout: true)
  stage('Print ENV') {
    sh "echo ${ret}"
    sh "echo ${br}"
  }
}
