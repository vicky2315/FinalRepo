 packagenode{
    stage('SCM checkout'){
    mvnHome = tool name: 'M3', type: 'maven'
    git 'https://github.com/vicky2315/FinalRepo'
    }
    stage('Compile package'){
        bat "'${mvnHome}\bin\mvn package' -Dmaven.test.failure.ignore clean package"
    }
}
    
