
  @Library('demo-SL@master')_
	//wrap([$class: 'AnsiColorBuildWrapper', 'colorMapName': 'xterm']) {
  //sh 'something that outputs ansi colored stuff'
ansiColor('xterm') {
pipeline {
	agent any 
     	stages {
		stage('build'){
			steps{
evenOrOdd(currentBuild.getNumber())
  }
 }
     }
}
}


