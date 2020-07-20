node{
    stage ('SCM Checkout'){
    git 'https://github.com/kyenumul/my-app'
    }
    stage ('Compile-Package'){
    def mvhome=tool name: 'maven', type: 'maven'
        sh ="${mvhome}/bin/mvn package"
    }
}
