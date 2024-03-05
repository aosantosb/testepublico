pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Executar o build do projeto C#
                    bat 'msbuild TestePublico.csproj /t:Rebuild'
                }
            }
        }
    }
}
