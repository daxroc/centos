echo("hello from Pipeline");
node('linux') {
  dev packer = docker.image('test/jenkins/slave:latest')

  packer.pull  
  packer.inside {
	// some block
	sh 'env'
	sh 'which packero
	sh 'which virtualbox'
	sh 'which vagrant'
  }
}