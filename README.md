# 2Dassignment
 I understand your app is a multiplayer 2D application using Photon for networking. You mentioned you intended to enable audio and video chat when players collide, but encountered an issue with the agora_gaming_rtc and IRtcEngine namespace in the Agora Video SDK. Despite downloading all available versions of the SDK, the namespace was missing in each version. Additionally, reimporting the Agora SDK did not resolve the issue, resulting in these two errors.

1.Assets\Scripts\AgoraManager.cs(2,7): error CS0246: The type or namespace name 'agora_gaming_rtc' could not be found (are you missing a using directive or an assembly reference?)

2.Assets\Scripts\AgoraManager.cs(8,13): error CS0246: The type or namespace name 'IRtcEngine' could not be found (are you missing a using directive or an assembly reference?)
