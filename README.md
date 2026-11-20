## Summary

iOS engineer focused on native app and framework architecture. Passionate about crafting complex UX and seamless CI/CD. When I'm not in Xcode, dabble in Node.js and JavaScript.
##

## Portfolio

### Photo keyboard for iPhone and iPad

Photo Keyboard is a custom keyboard for iPhone and iPad that puts your photo library one tap away. Instead of leaving a conversation to find a picture and share it, you open the keyboard, tap the photo you want, and paste it into the message, email, or note you are already writing. There is no account and no server: photos are read from your library on the device, copied to the clipboard, and left there for you to paste. It is a simple utility for people who send photos often and want to stay in the flow of writing.

The keyboard reads photos from your library on your device. It does not upload your photos, and the app includes no analytics, advertising, or third-party SDKs. A copied photo is placed on the local clipboard and set to expire after two minutes. It is marked local-only, so it is not sent to your other devices through Universal Clipboard.

• Your photo library in a scrollable grid, newest photos first. • A preview confirmation after each copy, so you can see what is on the clipboard. • The original photo data in its original format, not a compressed screenshot. • A grid that adapts from iPhone to iPad. • No account, no sign-up, and no server. • An interface that follows your system appearance. Photo keyboard for iPhone and iPad.

• Requires iOS or iPadOS 16 or later. • The keyboard needs Full Access and photo library access to work. • Pasting depends on the app you are using; some apps accept images and others do not.

<img width="1512" height="949" alt="photo_keyboard_20261116_1" src="https://github.com/user-attachments/assets/1aba7626-ee0d-47b2-9572-f66b9de84b5d" />

##

### Social media-sharing apps

A set of iOS social apps for sharing photos and moments with friends, groups and followers. They share three core screens: a feed of posts with reactions and comments, a create flow for sharing media and one-to-one and group chat. One app keeps photo quality intact when sending, another places time-limited media.

<img width="2760" height="1880" alt="feed_create_chat_screens" src="https://github.com/user-attachments/assets/3789abda-5ed9-43e9-9698-990a20c73c56" />

##

### Street mapping app

Cities change every day and keeping street data fresh takes people on the road. This app is built for drivers and help keep it up to date.

Built core driver-facing screens for a crowdsourced street-mapping app: hourly coverage, driver hours and session details, and an in-app update alert. Developed a data-checking map mode on Apple Maps with custom overlays, showing street segments and how many stops are available, kept smooth for large city areas.

• Start a session and drive your assigned streets. • Review every session by date: duration, start time, distance and pay. • Check each session's status: pass, fail or still processing. • Pick any week to see approved earnings and a daily hours history. • Open the hourly coverage view and choose a weekday to see how the day looks hour by hour. • Check street segments on a map to see how many stops are available. • Upload your sessions and pictures from the home screen. • Report a problem from inside the app. • Get a prompt when a new version is available.

* **Interactive Availability Map:** Built high-performance custom overlays on Apple Maps to display real-time stop availability across street segments.
* **Hourly Activity Chart:** Developed a responsive (portrait/landscape) bar chart with a bottom picker sheet and time-of-day iconography (sun, sunset, moon).
* **Earnings & Session Carousel:** Created a 3-page carousel panel featuring summary figures, Blue Streets percentages, session links, and a daily Period History bar chart.
* **Drive History Log:** Implemented a date-grouped drive list tracking duration, start time, distance, and pay, complete with an upload action and color-coded status markers.
* **Custom Update Modal:** Designed an in-app version prompt modal with primary update and dismissal actions.
* **Third-Party Integrations:** Integrated Mixpanel, Branch, Typeform, and push notifications to support analytics, attribution, and user flows.
* **CI/CD Pipeline:** Streamlined builds and releases with Bitrise for faster, repeatable deployments.

<img width="1279" height="832" alt="street_mapping_app" src="https://github.com/user-attachments/assets/c6a5e321-d03b-47e0-b39e-31c4137740f6" />

##
