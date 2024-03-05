pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Executar o build do projeto C#
                    bat '"C:\\msbuild\\bin\\msbuild.exe" TestePublico.csproj /t:Rebuild'
                }
            }
        }
    }
}
