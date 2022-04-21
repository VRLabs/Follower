# Follower
  
[![Generic badge](https://img.shields.io/badge/Version-1.2-orange.svg)](https://github.com/VRLabs/Follower/releases/latest)
[![Generic badge](https://img.shields.io/badge/Unity-2019.4.31f1-informational.svg)](https://unity3d.com/unity/whats-new/2019.4.31)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-informational.svg)](https://vrchat.com/home/download)
[![Generic badge](https://img.shields.io/badge/License-MIT-informational.svg)](https://github.com/VRLabs/Follower/blob/main/LICENSE)  

A constraint-based follower.

## How it works

[Avatars Dynamics](https://docs.vrchat.com/docs/avatar-dynamics) contact components are used to animate a series of constraints.

## Install guide

Merge the FX controller to your own FX controller, using the [Avatars 3.0 Manager](https://github.com/VRLabs/Avatars-3.0-Manager) tool.
 
"Follower.prefab" should go to the base of your Unity scene, which will give it base Unity scaling.

Unpack the prefab by right-clicking it.

Place "Follower" at the base of your avatar.

Remove "Follower Target" outside of "Follower" and place it anywhere in your avatar's hierarchy. Adjust the position transform to your taste.

## How to use

"Container" is where you place your objects that you want to follow.

To change the speed of the follower, you can edit the Follow.anim clip inside the Animations folder.

## Downloads

You can grab the latest version of the Follower in [Releases](https://github.com/VRLabs/Follower/releases/latest).

## License

Follower is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/Follower/blob/main/LICENSE).

## Contact us

If you need help, our support channel is on [Discord](https://discord.vrlabs.dev).
