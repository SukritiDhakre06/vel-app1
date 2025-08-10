pipeline{
 	agent any
 	stages{
 		stage('parallel-stage')
 		  {
 		   parallel
 			{
 			stage('parallel-1')
 				{
 				steps{
 					echo "hey Dev branch"
 				     }
 				}
 			stage('parallel-2')
 				{
 				steps{
 					echo "hey2"
 				    }
 				}
 			stage('parallel-3')
 				{
 				steps{
 					echo "hey3"
 				    }
 				}


 			}
 		}
 
 
 	}

}
