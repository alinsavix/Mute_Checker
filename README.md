# Mute_Checker
This script will notify the user if they're muted or not.

(User Options to Edit:)
  * audio_source - This variable will need an Audio source to monitor. The default value is "Mic/Aux" which is the first default microphone source. No need to change if it's called that!

  * x_position - This variable would be the x position of the mute notification
    ---- I have made a axis locator and it's on my GitHub. Link: [Not uploaded yet]
  * y_position - This variable would be the y position of the mute notification

  * mute_message - Message to display when muted. The default message is "YOU'RE MUTED IDIOT"

  * mute_time - Time AFTER muting when the notification will show. The default time is 30 seconds

  * recording_or_streaming - This variable will be used if the user wants to notify ONLY when recording or ONLY when streaming. There's an option if you want it as both - it will notify if you're recording OR streaming. values: ("recording", "streaming", "both").

    ![](https://github.com/Malik403/Mute_Checker/blob/main/Animation.gif)

(Installation:)
    Note: As of right now, you'll need Python 11.6 or below, Python 12 isn't supported. NO MODULES NEEDED. Also, the OBS module is ONLY for OBS, no need to pip install it!
 
 * Open OBS Studio
 * Tools
 * Scripts
 * Python Settings
 * Browse
 * Navigate to installation of Python (Probably in: C:\Users\[username]\AppData\Local\Programs\ and Select Folder
 * Add the script to the Scripts section
 * Reload OBS
 * Script automatically loads when starting OBS!


(Streamer info:)
I originally made this script for my streamer friend. If you want to see it in action, his Twitch is Kobe_Skrobe.
