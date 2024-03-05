pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Executar o build do projeto C#
                    bat '"C:\\msbuild\\bin\\msbuild.exe" C:\\Bernhoeft\\projetosjenkins\\testepublico\\TestePublico\\TestePublico.csproj /t:Rebuild'
                }
            }
        }
    }
}
