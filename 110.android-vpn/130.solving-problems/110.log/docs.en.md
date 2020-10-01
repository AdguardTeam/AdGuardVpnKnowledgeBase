---
title: 'Collecting a log on AdGuard VPN for Android'
taxonomy:
    category:
        - docs
visible: true
---

* [How to collect a debug log?](#debug)


Sometimes in order to understand a problem and fix it we need to collect **log files**, or **logs**. Basically, these files contain information about the program and it's work. 

<a id="debug"></a>

#### Collecting a debug log

To collect a **debug** log and send it to us you need to perform following steps:

1. Open AdGuard VPN and go to "Settings".

<img src="https://cdn.adguard.com/public/Adguard/kb/VPN/android_debug_settings.png" width="350" />

2. Choose "Advanced settings" in the "Settings" menu.

<img src="https://cdn.adguard.com/public/Adguard/kb/VPN/android_debug_advanced.png" width="350" />

3. Go to "Logging level" and Choose "Trace" tab with "Record everything" below. It's desirable to close all background apps that don't concern the problem beforehand.

<img src="https://cdn.adguard.com/public/Adguard/kb/VPN/android_debug_trace.png" width="350" />


4. Reproduce the problem and set the logging level back to "Info" with "Default logging level". Note down the exact time when it happened.

<img src="https://cdn.adguard.com/public/Adguard/kb/VPN/android_debug_info.png" width="350" />

5. Send us a message from program by choosing "Report a bug" in the "Settings" menu. Don't forget to check the "Send detailed system info" checkbox under the text field and to include the timestamp from the step 4 into the message. 

<img src="https://cdn.adguard.com/public/Adguard/kb/VPN/android_debug_send_report.png" width="350" />

As an alternative, you can export the logs (along with the *state.txt* file that contains system information and information about AdGuard settings) directly into a local file. It can be convenient, for example, if you are having a conversation with a developer on [GitHub](https://github.com/Adguardteam/), [forum](https://forum.adguard.com/) or on another platform. Or you can send it to our [Support Team](mailto:support@adguard.com)

To export logs and system information into a file, go to "Settings — Advanced settings" and tap on "Export logs and system info". Select the destination folder and tap on "Save".

Another way of collecting logs is to do it with logcat. Read more about logcat [here](add link)

<br>
<br>
<br
<br>
<br>
