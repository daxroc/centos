echo("hello from Pipeline");
docker.image('test/jenkins/slave:latest').inside {
	// some block
	sh 'env'
	sh 'which packer'
	sh 'which virtualbox'
	sh 'which vagrant'
}