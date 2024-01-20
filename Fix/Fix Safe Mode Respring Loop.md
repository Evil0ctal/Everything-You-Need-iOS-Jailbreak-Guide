# How to uninstall Bad/Incompatible tweak with Filza (Safe Mode Respring Respring Loop Fix)

> What's up guys and girls, today I'm going to be creating a quick yet detailed text tutorial that will also include a screen recorded video to walk you step by step on how to uninstall a bad tweak which is causing you to boot into safe mode every time and not allowing you to re-enter your jailbroken mode.

- Open Filza(If you're not already in the beginning of Filza, click the back button on the top left until you're at the beginning.)
- Scroll down until you see Library and open it.
- Now scroll down until you see MobileSubstrate and open it.
- Now open the DynamicLibraries folder.
- You will now see all of tweaks, go ahead and look for the name of the most recent tweak you installed and click Edit found at the top right, highlight both the .plist and .dylib files of that tweak, click trash at the bottom and confirm the deletion. For example, as shown in the video below, I deleted both LocalIAPStore.plist and LocalIAPStore.dylib
- Now back out of the DynamicLibaries folder and also back out of the MobileSubstrate folder, bringing you back to the Library folder.
- Scroll down until you see a folder named dpkg and go ahead and open it.
- Now open the info folder
- Here you're going to see a lot of files. You're going to need to find the name of the bad tweak and delete both files by clicking Edit in the top right, highlighting both files, clicking the trash button at the bottom and confirming the deletion (Watch what I did in the video below).

- Video link: https://youtu.be/pQQcyE1ZnCg
  
> Path of the deb install files:

- `/Library/dpkg/info`
- `/Library/MobileSubstrate/DynamicLibraries`

> I don't have Filza installed, what can I do ?

If you don't have Filza installed on your device don't worry, you can still fix the problem.

- Open Safari on your device
- Type http://tweakboxapp.com
- Click Download App
- Click Allow
- Click Install
- Open TweakBox
- Click the "Apps" section and then click "Tweakbox Apps"
- Click Search Tweakbox Apps and search for FilzaEscaped
- Click FilzaEscaped then click Install
- Click Install one last time and the app should be installed onto your device | Now proceed to follow the steps above
