
  @Library('demo-SL@master')_
pipeline {
   agent any 
     stages {
	stage('Demo'){
	  steps {
buildjob(currentBuild.getResult())
	  }
	}
	     stage('build'){
		     steps{
evenOrOdd(currentBuild.getNumber())
	  }
  }
     }
}


