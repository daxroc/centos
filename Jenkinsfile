echo("hello from Pipeline");

withDockerContainer('test/jenkins/slave:latest') {
    // some block
    sh 'env'
    sh 'which packer'
    sh 'which virtualbox'
    sh 'which vagrant'
}