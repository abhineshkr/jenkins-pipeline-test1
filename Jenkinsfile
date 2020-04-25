node{
	stage('SCM CHECK'){
		git 'https://github.com/abhineshkr/jenkins-pipeline-test1'
	}


	stage(COMPILE'){
		sh 'mvn package'
	}
}