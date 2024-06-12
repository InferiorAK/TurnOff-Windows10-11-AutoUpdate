# Turn Off Windows 10/11 Auto Update Permanently


<p align="center">
  <img src="https://img.shields.io/github/stars/inferiorAK/TurnOff-Windows10-11-AutoUpdate?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/inferiorAK/TurnOff-Windows10-11-AutoUpdate?color=red&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/inferiorAK/TurnOff-Windows10-11-AutoUpdate?color=teal&style=for-the-badge">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Author-InferiorAK-blue?style=flat-square">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FInferiorAK%2FTurnOff-Windows10-11-AutoUpdate&title=Visitors&edge_flat=false"/>
</p>

## [+] My Links

<div align=center>
 
[![Github](https://img.shields.io/badge/Github-InferiorAK-orange?style=for-the-badge&logo=github)](https://github.com/InferiorAK)
[![Facebook](https://img.shields.io/badge/Facebook-InferiorAK-blue?style=for-the-badge&logo=facebook)](https://www.facebook.com/InferiorAK)
[![Messenger](https://img.shields.io/badge/Chat-Messenger-blue?style=for-the-badge&logo=messenger)](https://m.me/InferiorAK)
[![Twitter](https://img.shields.io/badge/Twitter-InferiorAK-skyblue?style=for-the-badge&logo=twitter)](https://www.twitter.com/InferiorAK)
[![YouTube](https://img.shields.io/badge/YouTube-InferiorAK-red?style=for-the-badge&logo=youtube)](https://youtube.com/@InferiorAK)
 
</div>

## $ Step - 01
- Press `Windows+R`
- Now Type `services.msc` and press OK

<img src="src/1.png"/>

<br>

- Now go to `Windows Update`
- Then Select *Startup type:* `Disabled` and press OK

<img src="src/2.png"/>

<br><br><br>

## $ Step - 02
- Press `Windows+R`
- Now Type `gpedit.msc` and press OK

<img src="src/3.png"/>

<br>

- Now go to <br>
`Computer Configuration > Administrative Templates > Windows Components > Windows Update >`*`Configure Automatic Updates`*
- Then Select `Disabled` and press OK

<img src="src/4.png"/>

<br><br><br>

## $ Step - 03
- Press `Windows+R`
- Now Type `regedit` and press OK

<img src="src/5.png"/>

<br>

- Now go to <br>
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
- Then Create Folder named `AU` if it doesn't exist

<img src="src/6.png"/>

- Then Create File `NoAutoUpdate` and set Hexadecimal Value `1` for it and press OK

<img src="src/7.png"/>

- Then also set `AlwaysAutoRebootAtScheduledTime` Hex Value `1`

<img src="src/8.png"/>

- Now you are all Done Turning off Windows Auto Update Permanently!
