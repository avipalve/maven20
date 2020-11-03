node{
   stage('SCM Checkout'){
     git 'https://github.com/avipalve/maven20'
    }
    stage('Compile-Package'){
     def myhome = tool name: 'maven2', type: 'maven'
       sh "${maven20}/bin/mvn package"
    }  
    
}    
