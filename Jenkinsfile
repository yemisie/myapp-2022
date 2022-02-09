node {
	sage('SCM Checkout') {
            tool name:'maven-3', type: 'maven'
	git 'https://github.com/yemisie/myapp-2022'
	}
	stage('Compile-Package'){
	sh 'mvn package'
	}
}

