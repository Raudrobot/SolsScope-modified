# SolsRNGBot Server Edition
## This is a variant of the SolsRNGBot macro designed for people who have to Macro in a Glitch Hunt server.

# Features:
- Biome Detection
- Auto Craft Mode (for afking)
- Merchant Detection (if autocraft is off)
- Sending to a webhook
- Specific Role Pings for Mari/Jester or Glitched/Dreamspace
- Sending a screenshot of a Merchant's stock upon detection
- If the Glitched/Dreamspace IDs are 0, then by default it will ping everyone.

# Note that this version is very minimal compared to the full version of SolsRNGBot.
# Setup:
## Exe:
Just run the exe and it will start the macro, it will take some time to start because of all the Python packages that were bundled with it.
## Python:
In order to setup the Macro, you need to install the requirements (py -m pip install -r requirements.txt) or (py -m pip install discord==1.7.3 pyautogui pynput requests pillow screeninfo mousekey psutil).
## Do this for both:
Run the Macro and paste your webhook link into the Webhook URL field. You can also customise your settings, including the roles to be mentioned, the biomes to notify about etc here. Once you are done, press save and start macro to begin.

# Stopping the Macro:
## To stop the Macro, you need to press Ctrl and E, or whatever the value of your Failsafe Key is in settings.
