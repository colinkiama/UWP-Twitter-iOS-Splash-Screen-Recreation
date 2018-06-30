# UWP-Twitter-iOS-Splash-Screen-Recreation
Shows how to get the similar splash screen animation as the Twitter iOS app in your app!

![Application Demo](img/twitterIOSSplashRecreation.gif)

## Summary:
1. App starts, blue background with twitter logo as splash screen
2. App moves on to extended splash screen, keeping the same assets with the splash screen
3. When app "finishes loading" (Delay was added to simulate loading time), a scale animation is first applied to the splash screen image, zooming out a little bit then, another scale animation is applied, zooming into the twitter logo.
4. App then navigates to a new page and immediately animations cause the page to scale in and out to create a bouncing effect.
