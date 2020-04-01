node{
    stage('SCM checkout'){
    def mvnHome = tool name: 'MAVEN_HOME', type: 'maven'
    git 'https://github.com/vicky2315/FinalRepo'
    }
    stage('Compile package'){
        sh "${mvnHome}/bin/mvn package"
    }
 }
    
