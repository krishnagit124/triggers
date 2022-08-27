pipeline{
    agent any
        stages{
            stage("TEST"){
		steps{

                      tools{
                           maven 'MVN2'
                         
		      }
		}
                 steps{
                        sh 'mvn --version'
		 }
                   

	    }



	}


}
