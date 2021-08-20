pipeline 
{
	parameters
    {
        string(name: 'OPERATION', defaultValue: '', description: '<BR><font color=RED>*</font> 	Operation to Perform')
        string(name: 'Email', defaultValue: '', description: '<BR><font color=RED>*</font> Email for user')
        string(name: 'OU_Name', defaultValue: '', description: '<BR>Enter OU Name')
	}	
  agent any
  stages 
  {
	stage ("Input Values") 
	{
      steps {
				echo "Hello ${params.OPERATION}"

                echo "Biography: ${params.Email}"

                echo "Toggle: ${params.OU_Name}"
			}
	}
}
}	