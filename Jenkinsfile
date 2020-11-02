node{
	stage('SCM Checkout'){
        git 'https://github.com/kumarsql359/my-app/'
	}
	stage('Compile-Package'){
	def mvnHome = tool name: 'M2_HOME', type: 'maven'	
		sh "${mvnHome}/bin/mvn package"

	}
}
