node {
	sage('SCM Checkout') {
            tool name: 'maven3', type: 'maven'
	git 'https://github.com/yemisie/myapp-2022'
	}
	stage('Compile-Package'){
	sh 'mvn package'
	}
}

