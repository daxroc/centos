echo("hello from Pipeline");
node('master') {
  def packer = docker.image('test/jenkins/slave:latest')

  packer.pull()
  packer.inside {
	// some block
	sh 'env'
	sh 'which packer'
	sh 'which virtualbox'
	sh 'which vagrant'
  }
}