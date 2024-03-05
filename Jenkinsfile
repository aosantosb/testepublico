pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Executar o build do projeto C#
                    bat '"C:\\MSBuild\\Bin\\msbuild.exe" TestePublico.csproj /t:Rebuild'
                }
            }
        }
    }
}

