node {
	stage('one') {
		echo 'one'
	}
	stage('two') {
		echo 'two'
	}
	stage('three') {
		echo 'three'
	}
	stage('script') {
		git 'https://github.com/jenkinsdemos/pipeone.git'
		sh 'chmod +x script.sh'
		sh './script.sh'
	}
}
