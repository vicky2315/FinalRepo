node{
    stage('SCM checkout'){
    def mvnHome = tool name: 'maven-3', type: 'maven'
    git 'https://github.com/vicky2315/FinalRepo'
    }
    stage('Compile package'){
        sh "${mvnHome}/bin/mvn package"
    }
 }
    
