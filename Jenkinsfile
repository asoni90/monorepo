node {
  def ret = sh(script: '${env.BRANCH_NAME}', returnStdout: true)
  stage('Print ENV') {
      sh '${ret}'
  }
}
