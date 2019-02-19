
node {


        stage('SCM Checkout') {
            git 'https://github.com/Mohammed-Ahmed2/maven'

        }
        stage('Compile-Package') {
            def mvnHome = tool name: 'Maven 3.6', type: 'maven'
            sh "${mvnHome}/bin/mvn package"
        }

}