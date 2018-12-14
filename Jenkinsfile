
  @Library('demo-SL@master')_
	//wrap([$class: 'AnsiColorBuildWrapper', 'colorMapName': 'xterm']) {
  //sh 'something that outputs ansi colored stuff'
pipeline {
	agent any 
     	stages {
		ansiColor('xterm') {
		stage('build'){
			steps{
evenOrOdd(currentBuild.getNumber())
  }
 }
	}
}
}


