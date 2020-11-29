node{
   stage('SCM CheckOut'){
        git 'https://github.com/vaishnaviamirtham/'
        }
        stage('Compile.Package'){
           sh '/usr/share/maven/bin/mvn package'
           }
           }
