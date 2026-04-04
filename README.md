![IMG_1738](https://github.com/user-attachments/assets/79f96051-7d93-4449-8045-8ba856fa66a5)![IMG_1755](https://github.com/user-attachments/assets/afca106c-b708-44fb-8ec6-f53358ea4227)

![IMG_1743](https://github.com/user-attachments/assets/93e879ad-023c-4477-bb5c-54865a70bc2a)


"This is a voice assistant project that ports the ESP32-S3-BOX-3 ready-made project to the Elecrow CrowPaneL Advance 7.0-HMI ESP32 AI Display. It has full wake word and voice functionality. The long-term goal is complete feature parity with the ESP32-S3-BOX-3 project. It also sends a esphome.tts_uri event to Home Assistant with the URL for the audio response, thanks to the work done by [@formatBCE](https://github.com/formatBCE). This assistant is currently a work in progress, and has been [documented on XDA](https://www.xda-developers.com/built-google-home-hub-replacement-esp32-display/). It requires the S1 and S0 switches to be set to 0, so that both MIC and SPK are enabled. 

There are a number of improvements necessary to make this particular project more user-friendly, such as adding display brightness control."

I have modified the code for version v1.2.Fixed audio issues, no responses could be heard.Added backlight control.Increased memory speed to 120Mhz.It's not perfect but it works.
Still need to fine-tune a few things

I added a control panel for HA. 

All credits to the authors

voice assistant

https://github.com/Incipiens/Adam-Home-Assistant-Snippets


control panel

https://github.com/strange-v/RemoteWebViewServer

