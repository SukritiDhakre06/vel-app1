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
 					echo "Dev Branch"
 				     }
 				}
 			stage('parallel-2')
 				{
 				steps{
 					echo "Dev Branch"
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
