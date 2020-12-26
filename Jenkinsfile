node {
stage('scm-checkout') {

git 'https://github.com/vijay2181/nexus.git'
}
stage('compile-package') {
  def mvnHome =  tool name: 'MAVEN', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}
}
