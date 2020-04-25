node{
	stage('SCM CHECK'){

		git 'https://github.com/abhineshkr/jenkins-pipeline-test1'
	}


	stage('COMPILE'){
		def mvnHome = tool name: 'maven3', type: 'maven'
		sh "${mvnHome}/bin/mvn package"
		
	}
}