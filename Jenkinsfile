node {
stage('scm-checkout') {
git 'https://github.com/vijay2181/nexus.git'
}
stage('compile-package') {
sh 'mvn clean package'
}
}
