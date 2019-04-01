pipeline {
    agent any

 stages 
 {
      stage("BASIC")
     {
      stages 
        {       
          stage('Build') 
        {
            steps 
            {
                echo 'Building..'
            }
        }
        stage('Test') 
        {
            steps 
            {
                echo 'Testing..'
            }
        }
        stage('Deploy')
        {
            steps 
            {
                echo 'Deploying....'
            }
        }
        }
     }
     
     stage("ALIAS")
     {
         stages{
          stage('Build') 
        {
            steps 
            {
                echo 'Building..'
            }
        }
        stage('Test') 
        {
            steps 
            {
                echo 'Testing..'
            }
        }
        stage('Deploy')
        {
            steps 
            {
                echo 'Deploying....'
            }
        }
         }
     }

 }
}
