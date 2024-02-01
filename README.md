# Configuration Tracker
OpenVoice OS's raspbian image configuration on the system and user level.
https://github.com/OpenVoiceOS/raspOVOS
## Status of wake words
1. Nyumaya
    - incorrect plugin version to use nyumaya's trained model
      - https://github.com/OpenVoiceOS/ovos-ww-plugin-nyumaya
2. Open Wake Word
    - works, but is inconsistent
      - https://github.com/OpenVoiceOS/ovos-ww-plugin-openWakeWord?tab=readme-ov-file
    - Since the trained models are inconsistent and time constraints, I have decided to use a model that has been trained by someone in the OVOS community
      - https://github.com/OpenVoiceOS/precise-lite-models/tree/master 
3. Pocket Spinx
    - used a website to get the wording
      - http://www.speech.cs.cmu.edu/cgi-bin/cmudict?in=Hey+android
