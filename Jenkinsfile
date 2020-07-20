node{
    stage ('SCM Checkout'){
    git 'https://github.com/kyenumul/my-app'
    }
    stage ('Compile-Package'){
    def mvhome=tool name: 'maven', type: 'maven'
        sh ="${mvhome}/bin/mvn package"
    }
    stage ('Email notification'){
           mail bcc: '', body: 'my first jenkins', cc: '', from: '', replyTo: '', subject: 'jenkins job', to: 'kishorebabu.yenumula@gmail.com'
           }
}
