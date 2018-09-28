pipeline {
    
agent any

    stages {

	/*stage('SCM')
{

            steps {

                checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '9640e04d-e2ce-44e1-a3ec-dd0f93e8b77c', url: 'https://github.com/Shrihari4607/Java-HelloWorld.git']]])

            }

        }*/

        stage('build')
 {

            steps {

                //bat 'javac Hello.java'
		//bat 'java Hello'
		    echo 'build'

            }
        }
    }
}
