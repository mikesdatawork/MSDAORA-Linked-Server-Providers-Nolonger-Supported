![MIKES DATA WORK GIT REPO](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_01.png "Mikes Data Work")        

# MSDAORA Linked Server Providers Nolonger Supported
**Post Date: October 7, 2007**        



## Contents    
- [About Process](##About-Process)  
- [SQL Logic](#SQL-Logic)  
- [Build Info](#Build-Info)  
- [Author](#Author)  
- [License](#License)       

## About-Process


If you are trying to setup a linked server between SQL and Oracle using
the familiar MSDAORA in a 64bit environment your out of luck.
microsoft has confirmed that they DO NOT support the MSDAORA provider
in in 64bit environments. you'll notice this straight-away when looking over
the providers list from management studio under Linked Servers. any Oracle
provider or variant is missing from the list. remember that this has nothing
to do with how you installed and configured your SQL Server. it simply is
no longer offered.
you have to use the Oracle driver ( ORAOLEDB.oracle ) which you get automatically
when you install the Oracle client. once installed you'll see the ORAOLEDB.oracle
provider listed in management studio.
suppose you have a 64bit SQL Server, and you are trying to connect to a 32bit
Oracle instance… that just makes things more difficult.
the conventional wisdom is that you need to have 64bit environments for both data
sources to get it to work.
i've read though; that the setup is possible if you have both the 64bit Oracle client
installed along side the 32bit Oracle Client.
this information may not be entirely new for some; but thought i would mention
it regardless. might save you call into ms over creating a linked server. 


[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

[![Gist](https://img.shields.io/badge/Gist-MikesDataWork-<COLOR>.svg)](https://gist.github.com/mikesdatawork)
[![Twitter](https://img.shields.io/badge/Twitter-MikesDataWork-<COLOR>.svg)](https://twitter.com/mikesdatawork)
[![Wordpress](https://img.shields.io/badge/Wordpress-MikesDataWork-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)





---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Mikes Data Work](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_02.png "Mikes Data Work")

