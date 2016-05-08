echo("hello from Pipeline");
node {

  withDockerContainer('test/jenkins/slave:latest') {
    // some block
    sh 'env'
    sh 'which packer'
    sh 'which virtualbox'
    sh 'which vagrant'
  }

}