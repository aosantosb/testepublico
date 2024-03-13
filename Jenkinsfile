pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Executar o build do projeto C#
                    bat '"C:\\Program Files\\Microsoft Visual Studio\\2022\\Community\\MSBuild\\Current\\Bin\\msbuild.exe" C:\\Bernhoeft\\projetosjenkins\\testepublico\\TestePublico\\TestePublico.csproj /t:Rebuild'
                }
            }
        }
    }
    stage('SonarQube analysis') {
            steps {
                withSonarQubeEnv('SonarQube Server') {
                    bat '"C:\\caminho\\para\\o\\sonar-scanner.bat"'
                }
            }
        }
}
