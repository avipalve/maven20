node{
   stage('SCM Checkout'){
     git 'https://github.com/avipalve/maven20'
    }
    stage('Compile-Package'){
    def mvnhome = tool name: 'maven2', type: 'maven'
       sh "${mvnhome}/bin/mvn package"
    }  
    
}    
