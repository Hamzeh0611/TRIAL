# TRIAL
- task: AzureRmWebAppDeployment@4
  inputs:https://HamzehMajali0567@dev.azure.com/HamzehMajali0567/mine/_git/mine
git push -u origin --all
    ConnectionType: 'AzureRM'
    appType: 'webAppLinux'
    WebAppName: mine
    packageForLinux: '$(System.DefaultWorkingDirectory)/**/*.zip'
