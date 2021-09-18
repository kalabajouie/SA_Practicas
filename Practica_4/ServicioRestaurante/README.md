SonarScanner.MSBuild.exe begin /k:"ServicioRestaurante" /d:sonar.login="8ead54cad189d65e5c751167d129c11d78e10223"

MSBuild.exe D:\Documents\GitHub\LabSA2021_200714432\ServicioRestaurante /t:Rebuild

SonarScanner.MSBuild.exe end /d:sonar.login="8ead54cad189d65e5c751167d129c11d78e10223"
