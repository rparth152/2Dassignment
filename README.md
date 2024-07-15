# 2Dassignment
 I understand your app is a multiplayer 2D application using Photon for networking. You mentioned you intended to enable audio and video chat when players collide, but encountered an issue with the agora_gaming_rtc and IRtcEngine namespace in the Agora Video SDK. Despite downloading all available versions of the SDK, the namespace was missing in each version. Additionally, reimporting the Agora SDK did not resolve the issue, resulting in these two errors.

1.Assets\Scripts\AgoraManager.cs(2,7): error CS0246: The type or namespace name 'agora_gaming_rtc' could not be found (are you missing a using directive or an assembly reference?)

2.Assets\Scripts\AgoraManager.cs(8,13): error CS0246: The type or namespace name 'IRtcEngine' could not be found (are you missing a using directive or an assembly reference?)


-----------------------------------------------Steps to Test the Functionality--------------------------------------------------------
1.Open the project in Unity.
2.Press Ctrl+B to build the game.
3.Open the UnityParthAssignment.exe file.
4.Create a room with a random name.
5.In the build instance, enter the same room name and click on the "Join" button.
6.You will now be able to play together.
Make sure the following prerequisites are met before testing:

*Ensure that Photon and Agora SDKs are correctly set up in the project.
*Verify that your network settings allow connections between players.
*Ensure that the build is correctly configured to connect to Photon servers.
By following these steps, you can test the multiplayer functionality of your Unity project.
