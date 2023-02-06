pipeline {

    agent any
  
    parameters {
        string defaultValue: 'Tran Anh', description: 'Choose your name', name: 'name'
    }

    
    stages {
    
      stage("build"){
          steps {
              echo "Welcome to my pipeline ${name}"
          }
      }    
    }
}
   
