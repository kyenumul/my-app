node{
    stage ('SCM Checkout'){
    git 'https://github.com/kyenumul/my-app'
    }
    stage ('Compile-Package'){
    sh 'mvn package'
    }
}
