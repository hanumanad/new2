node{
	stage('SCM Checkout'){
		git 'https://github.com/hanumanad/new2'
	}
	stage('Compile-Package'){
	def antHome = tool name: 'apache-ant-1.10.3', type: 'ant'
        sh "${antHome}/bin/ant war"
        }
}
    
