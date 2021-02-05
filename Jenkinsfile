buildMvn {
  publishModDescriptor = 'yes'
  publishAPI = 'no'
  mvnDeploy = 'yes'
  runLintRamlCop = 'no'
  doKubeDeploy = true
  buildNode = 'jenkins-agent-java11'

  doDocker = {
    buildJavaDocker {
      publishMaster = 'yes'
      healthChk = 'no'
    }
  }
}
