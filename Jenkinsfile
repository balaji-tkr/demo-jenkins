
  @Library('demo-SL@master')_
	//wrap([$class: 'AnsiColorBuildWrapper', 'colorMapName': 'xterm']) {
  //sh 'something that outputs ansi colored stuff'
pipeline {
	buildEnvironment{
		ansiColor('xterm') {
    	echo 'something that outputs ansi colored stuff'
	}
	}
   agent any 
     stages {
	 stage('build'){
	     steps{
evenOrOdd(currentBuild.getNumber())
  }
 }
     }
}


