# Heating Oil Management Interface for Home Assistant
Since I was unable to find something else quite like this online, and I wanted a way to keep track of my heating oil usage within Home Assistant, I took it upon my self to come up with the following.

It's definitely not perfect, and likely has a few bugs still, but it seems to be working well enough for me right now so I figured I'd post it for others to use as well.

Keep in mind, this won't be as accurate as a physical tank level sensor, but it seems to be pretty close in my usage so far.

It should work with minimal changes, other than those noted within the configuration files (fuel pump rating, hvac state sensor name, etc)

Each time you add fuel to your oil tank you just input the amount of fuel added to the "Last Fill" input, and set the "Last Fill Price" to the cost per litre for your last fillup; the sensors and automations should take care of the rest.
<br/>
<br/>
**SCREENSHOTS:**
<br/>
Main Interface:
<img src="https://i.imgur.com/4rABENQ.jpg" width="800px">
<br/>
<br/>
Configuration Options Expanded:
<img src="https://i.imgur.com/iZ2vzBM.jpg" width="800px">
<br/>
