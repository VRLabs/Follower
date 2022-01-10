<div>
  <h1>Follower</h1>
  <p>
     A constraint-based follower.
  </p>

  <a href="https://github.com/VRLabs/Follower/releases/latest">
    <img src="https://img.shields.io/github/v/release/VRLabs/Follower.svg?style=flat-square">
  </a>
  <a href="https://github.com/VRLabs/Follower/releases/latest">
    <img src="https://img.shields.io/badge/Unity-2019.4-green.svg?style=flat-square">
  </a>
  <br />
  <a href="https://github.com/VRLabs/Follower/issues">
    <img src="https://img.shields.io/github/issues-raw/VRLabs/Follower.svg?style=flat-square">
  </a>
  <a href="https://github.com/VRLabs/Follower/issues?q=is%3Aissue+is%3Aclosed">
    <img src="https://img.shields.io/github/issues-closed-raw/VRLabs/Follower.svg?style=flat-square">
  </a>
  <a href="https://github.com/VRLabs/Follower/pull">
    <img src="https://img.shields.io/github/issues-pr-raw/VRLabs/Follower.svg?style=flat-square">
  </a>
  <a href="https://github.com/VRLabs/Follower/pulls?q=is%3Apr+is%3Aclosed">
    <img src="https://img.shields.io/github/issues-pr-closed-raw/VRLabs/Follower.svg?style=flat-square">
  </a>
  <br />
</div>

## How it works

[Particle Driver](https://github.com/VRLabs/Particle-Driver) is used to animate a series of constraints.

## Install guide

Merge the FX controller to your own FX controller, using the [Avatars 3.0 Manager](https://github.com/VRLabs/Avatars-3.0-Manager) tool.
 
"Follower.prefab" should go to the base of your Unity scene, which will give it base Unity scaling.

Unpack the prefab by right-clicking it.

Place "Follower" at the base of your avatar.

Remove "Follower Target" outside of "Follower" and place it anywhere in your avatar's hierarchy. Adjust the position transform to your taste.

Use the [Layer Weight Tool](https://github.com/VRLabs/Layer-Weight-Tool/). Open VRLabs from the menu bar. Click "Apply Weight Controls".

## How to use

Testing in Unity requires the [3.0 emulator by Lyuma](https://github.com/lyuma/Av3Emulator). (Tip: To debug your FX controller, enable the emulator, enter play mode, select the controller file you intend to debug, and then select the avatar. Leave "Animator To Debug" at Base.)

"Container" is where you place your objects that you want to follow.

To change the speed of the follower, you can edit the Local and Remote Follow.anim clips inside the Animations folder.

## Downloads

You can grab the latest version of the Follower in [Releases](https://github.com/VRLabs/Follower/releases/latest).

## License

Follower is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/Follower/blob/main/LICENSE).

## Contact us

If you need help, our support channel is on [Discord](https://discord.vrlabs.dev).
