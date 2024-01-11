# RootlessJamesDSPTutorial
**NOTE:**

- INTERNET CONNECTION IS REQUIRED FOR PAIRING WITH SHIZUKU
- May not work in all system (due to System Limitation)
- This Tutorial is Underwork, additional testing is needed
- Minimum Android version is 12
- This is not for IOS users!
- Expect bugs, crashes
- You can see it works if you see "Audio Processing Idle" on your notification 

**Preparation**

- Download Rootless JamesDSP: [HERE](https://f-droid.org/en/packages/me.timschneeberger.rootlessjamesdsp/)
- Download Shizuku (if needed): [HERE](https://apt.izzysoft.de/fdroid/index/apk/moe.shizuku.privileged.api)

**Magic-Normal Method**
1. Download & Install Rootless JamesDSP
2. Grant all needed permissions
3. Done

**Shizuku Method**

*Please enable developer settings first*
How to enable developer settings?

1. Open settings and search for "About Devices"
2. Search for "Build Number"
3. Tap the build number for serveral times until it shows "You are in developer mode" (Some systems may require to authenticate via user password)


1. Open Shizuku app
2. Tap on pairing
3. Enable Notifications
4. Go to Developer Options
5. Search for Wireless Debugging and allow access to network
6. Tap on the Wireless Debugging and Pair Device with pairing code
7. Enter pairing code on Shizuku notification
8. Go back to Shizuku and press start
9. Authorize Rootless James DSP from Shizuku
10. Now go back to Rootless JamesDSP and set it up
11. Done

**Performance Tweaks**

*Benchmark method*

1. Go to Audio Processing
2. Enable "Use Benchmark to optimize performane"

*Allow Notification method*

1. Go to Troubleshooting
2. Enable "Allow notification access for better session detection"

*Import Convolver File*

1. Go to Convolver
2. Click on Impulse Respone
3. Click Import
4. Select the .irs file
5. Done

**In Case you wonder where you can get those .irs files, you can go to ConvolverExample folder**

Credit: 
- programminghoch10 (Convolver Files)
- ThePBone (Developer of Rootless JamesDSP)
