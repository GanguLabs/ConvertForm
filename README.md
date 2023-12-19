[![Inactively Maintained](https://img.shields.io/badge/Maintenance%20Level-Inactively%20Maintained-yellowgreen.svg)](https://gist.github.com/cheerfulstoic/d107229326a01ff0f333a1d3476e068d)

Reference Videos:
- [Building a GUI based PowerShell script using FREE Tools – Method 1](https://www.youtube.com/watch?v=6HNbk9VylLc)
- [Building a GUI based PowerShell script using FREE Tools – Method 2](https://www.youtube.com/watch?v=Xkm4PCVAL7M)
- [Creating a GUI based PowerShell script using XAML and Visual Studio to unlock AD Users from scratch](https://www.youtube.com/watch?v=ZXxLk-b-TU4)
- [WPF & Powershell](https://www.youtube.com/watch?v=uJcvwgbTeks&list=PLsg-xXEEmCJozYQCiBxO5ydYI1KIV2pI4)
- [Powershell GUI Tutorial](https://www.youtube.com/watch?v=X6nU5QCF8XI&list=PLnK11SQMNnE5_cl8n54h6OXNMnGl5Odtq&index=1)
 
 # ConvertForm

![Logo](https://github.com/LaurentDardenne/ConvertForm/blob/master/Convert-Form-Icon.jpg)

Powershell module for converting a Winform file (xxx.Designer.cs) to a PowerShell script .ps1


To install this module :
```Powershell
$PSGalleryPublishUri = 'https://www.myget.org/F/ottomatt/api/v2/package'
$PSGallerySourceUri = 'https://www.myget.org/F/ottomatt/api/v2'

Register-PSRepository -Name OttoMatt -SourceLocation $PSGallerySourceUri -PublishLocation $PSGalleryPublishUri #-InstallationPolicy Trusted
Install-Module ConvertForm -Repository OttoMatt
```


