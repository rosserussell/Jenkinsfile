pipeline 
{
    agent any
    stages 
    {
	stage ('build') 
	{
	    steps 
	    {
	        echo "build"
	    } // end of steps
	} // end of stage

	stage ('test: integration-&-quality') 
	{
	    steps 
	    {
		echo "test: integration-&-quality"
	    } // end of steps
	} // end of stage

	stage ('test: functional') 
	{
	    steps 
	    {
		echo 'test: functional'
	    } // end of steps   
	} // end of stage

	stage ('test: load-&-security') 
	{
	    steps 
	    {
		echo 'test: load-&-security'
	    } // end of steps
	} // end of stage

	stage ('approval') 
	{
	    steps 
	    {
		echo 'approval'
	    } // end of steps
	} // end of stage

	stage ('deploy:prod') 
	{
	    steps 
	    {
	        echo 'deploy:prod'
	    } // end of steps       
	} // end of stage

    } // end of stages
} // end of pipeline
