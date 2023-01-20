# UWP-Twitter-iOS-Splash-Screen-Recreation
Shows how to create a splash screen animation that is similar Twitter iOS app in your own UWP app.

![Application Demo](img/twitterIOSSplashRecreation.gif)

Update: This was a lazy way of doing this. If you want to improve on this, you'd use a transparent mask on the Twitter logo.
You can find the assets you need in Twitter's brand assets page or on FontAwesome.
This app called [Code Writer](https://apps.microsoft.com/store/detail/code-writer/9WZDNCRFHZDT?hl=en-gb&gl=gb&rtc=1) does the splash screen animation effect the proper way.


## Summary:
1. App starts, blue background with twitter logo as splash screen
2. App moves on to extended splash screen, keeping the same assets with the splash screen
3. When app "finishes loading" (Delay was added to simulate loading time), a scale animation is first applied to the splash screen image, zooming out a little bit then, another scale animation is applied, zooming into the twitter logo.
4. App then navigates to a new page and immediately animations cause the page to scale in and out to create a bouncing effect.
