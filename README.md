# SpeakBot by Sponkly — Google Tag Manager template

Adds [SpeakBot](https://sponkly.com/features/speakbot) to your website through Google Tag Manager:
live support in every language — visitors write, call or video call in their own language, your team
answers in yours, translated live by Sponkly. When nobody is available, an AI receptionist answers.

## Set up

1. In Sponkly (Business or Enterprise plan): **Dashboard → SpeakBot**, create a site, add your
   website's address and copy the site key (`sb_…`).
2. In Tag Manager: **Templates → Search Gallery → SpeakBot by Sponkly → Add to workspace**
   (or import `template.tpl`).
3. **Tags → New → SpeakBot by Sponkly**, paste the site key, trigger **All Pages**, then **Submit**.

Optional: *Widget language* (e.g. `de`) — by default each visitor's browser language.

The tag injects `https://sponkly.com/speakbot/widget.js` (the only permission it asks for). The
widget sets no cookies and does not track visitors; it runs in a frame from api.sponkly.com.

Privacy: https://sponkly.com/privacy · Help: help@sponkly.com
