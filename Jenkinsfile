node 
{
    stage('Preparation') 
    {
        git branch: 'main', url: 'https://github.com/bhaarn/DevOpsDemo.git'
    }
    stage('Build') 
    {
      git branch: 'main', url: 'https://github.com/bhaarn/DevOpsDemo.git'
      wait(5000)
      echo "success"
    }
    stage('Unit Test')
    {
      git branch: 'main', url: 'https://github.com/bhaarn/DevOpsDemo.git'    
      wait(6000) 
      echo "success"
    }
    stage('SonarQube Scan') 
    {
      git branch: 'main', url: 'https://github.com/bhaarn/DevOpsDemo.git'  
      wait(8000)
      echo "success"
    }
    stage('Lint Checks')
    {
      git branch: 'main', url: 'https://github.com/bhaarn/DevOpsDemo.git'  
      echo "success"
    }
    stage('Results') 
    {  
      git branch: 'main', url: 'https://github.com/bhaarn/DevOpsDemo.git'
      wait(15000)
      echo "success"
    }
}
