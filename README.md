# project-swift-viewer

An iOS native GMetri Viewer

### About the Project

GMetri runs as a URL on most browsers natively. However, on iOS there are a [lot of limitations](https://docs.gmetri.com/guidelines-compatibility/compatibility/limitations/ios-support).

Create an iOS app to circumvent these limitations.

- The UI would be similar to that of a GMetri deployment.
- You can use [SceneKit](https://developer.apple.com/documentation/scenekit](https://developer.apple.com/documentation/scenekit) to replicate the redering of GMetri’s rjson.
- Additional features like audio chat, text chat can be implemented using the native [Agora SDK](https://docs.agora.io/en/voice-calling/get-started/get-started-sdk?platform=ios).

### **Technology Stack**

SwiftUI, SceneKit, GMetri SDK (APIs), AgoraSDK

### **Resources**

* [https://developer.apple.com/documentation/scenekit](https://developer.apple.com/documentation/scenekit)  
* [https://docs.agora.io/en/voice-calling/get-started/get-started-sdk?platform=ios](https://docs.agora.io/en/voice-calling/get-started/get-started-sdk?platform=ios)

### **Evaluation Criteria**

You need to create an iOS App. The total list of features in GMetri is very exhaustive. So we aren’t targeting that. But the following should work:

1) A 360 scene + images + videos
2) Rules that show/hide images and videos, and trigger play / pause for videos
3) Text and Audio chat
