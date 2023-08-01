Launch Terminal as admin and then:
notepad $PROFILE.AllUsersAllHosts

oh-my-posh init pwsh --config C:\src\FancyPompt\amit-velvet.omp.json | Invoke-Expression

oh-my-posh init pwsh --config ~\markbull.omp.json | Invoke-Expression

Debug:
oh-my-posh debug 

See all themes:
Get-PoshThemes

Themes location: C:\Users\bahre\AppData\Local\Programs\oh-my-posh\themes

To change your theme, adjust the init script in F:\SynologyDrive\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1.
Example:
  oh-my-posh init pwsh --config C:\Users\bahre\AppData\Local\Programs\oh-my-posh\themes/jandedobbeleer.omp.json | Invoke-Expression

  For conda shell to show up, in Anaconda powershell run this:
  conda init powershell

  See https://hackf5.medium.com/how-to-enable-anaconda-in-powershell-7-on-windows-394ba62c3f9c