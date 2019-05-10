# mvce-expo-av-android

1. yarn + yarn android
2. Hit full screen button on video player
3. should crash

```

05-10 16:41:16.072 17091 17091 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke interface method 'boolean org.unimodules.core.interfaces.services.KeepAwakeManager.isActivated()' on a null object reference
05-10 16:41:16.072 17091 17091 E AndroidRuntime: 	at expo.modules.av.video.FullscreenVideoPlayer$KeepScreenOnUpdater.run(FullscreenVideoPlayer.java:45)

```
