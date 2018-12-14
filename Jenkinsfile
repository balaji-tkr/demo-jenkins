
  @Library('demo-SL@master')_
//ansiColor('xterm') {
  //  echo 'something that outputs ansi colored stuff'
wrap([$class: 'AnsiColorBuildWrapper', 'colorMapName': 'xterm']) {
  sh 'something that outputs ansi colored stuff'
}
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


