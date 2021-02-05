pipeline {
    agent any
    trigger {
      cron("* 1 * * *")
    }
    stages{
      stage("Build") {
        steps {
            sh "dotnet build /src/Tryout/JenkinsTryout/JenkinsTryout.csproj"
              unstable	"Build phase not implemented"
        }
      }
      stage("Test") {
        steps {
              unstable	"Test phase not implemented"
        }
      }
      stage("Deliver") {
        steps {
              unstable	"Deliver phase not implemented"
      }
    }
  } 
}