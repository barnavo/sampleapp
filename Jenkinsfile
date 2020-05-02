// Powered by Infostretch 

timestamps {

node () {

	stage ('phptest - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'e72474e6-85d1-409a-bf9a-8f1a6bc0c5b5', url: 'https://github.com/barnavo/sampleapp.git']]]) 
	}
	stage ('phptest - Build') {
 	
withEnv(["JAVA_HOME=${ tool '"+JDK+"' }", "PATH=${env.JAVA_HOME}/bin"]) { 

// Unable to convert a build step referring to "hudson.plugins.sonar.SonarRunnerBuilder". Please verify and convert manually if required. 
	}
}
}
}