<div align="center">

# Follower

[![Generic badge](https://img.shields.io/github/downloads/VRLabs/Follower/total?label=Downloads)](https://github.com/VRLabs/Follower/releases/latest)
[![Generic badge](https://img.shields.io/badge/License-MIT-informational.svg)](https://github.com/VRLabs/Follower/blob/main/LICENSE)
[![Generic badge](https://img.shields.io/badge/Unity-2019.4.31f1-lightblue.svg)](https://unity3d.com/unity/whats-new/2019.4.31)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-lightblue.svg)](https://vrchat.com/home/download)

[![Generic badge](https://img.shields.io/discord/706913824607043605?color=%237289da&label=DISCORD&logo=Discord&style=for-the-badge)](https://discord.vrlabs.dev/)
[![Generic badge](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dvrlabs%26type%3Dpatrons&style=for-the-badge)](https://patreon.vrlabs.dev/)

Make something slowly follow you and look at you

![Follower](https://github.com/VRLabs/Follower/assets/76777936/3bb764a3-27ae-40b3-a595-6353ff30634a)


### ⬇️ [Download latest Unitypackage](https://github.com/VRLabs/Follower/releases/latest)

<!-- 
### 📦 [Add to VRChat Creator Companion]() -->

</div>

---

## How it works

* Using a [Damping Constraint](https://github.com/VRLabs/Damping-Constraints) inside of a [World Constraint](https://github.com/VRLabs/World-Constraint) we can make an object slowly follow the player.
* By using Contact Senders and Contact Receivers we can dynamically change the speed of the follower over time.

## Install guide

https://github.com/VRLabs/Follower/assets/76777936/eee1dcbb-0e9d-4f92-bb69-9bcbe50d9948

* Merge the Animator Controller ``Follower FX`` to your own FX Controller, using the [Avatars 3.0 Manager](https://github.com/VRLabs/Avatars-3.0-Manager) tool.
* Drag & Drop the ``Follower`` prefab into the base of your Hierarchy.
* Right click and unpack the prefab, then drag & drop it onto your avatar.
* Expand the prefab hierarchy and find ``Follower Target``.
* Move ``Follower Target`` outside of ``Follower`` and place it anywhere in your avatars hierarchy as needed.

## How to use

* Place the objects you want to follow you inside ``Container``.
  * Alternatively you can constrain the objects to ``Container``.
* Editing the ``Follow`` animation clip will let you change the speed of the follower.

## Performance stats

```c++
Constraints:        5
Contact Receivers:  1
Contact Senders:    1
```

## Hierarchy layout

```html
Follower
|-Container
|  |-Cube
|-Look Constraint
|-Follower Target
|  |-Look Target
```

## Contributors

* [lin](https://github.com/oofdesu)

## License

Follower is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/Follower/blob/main/LICENSE).

​

<div align="center">

[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/VRLabs.png" width="50" height="50">](https://vrlabs.dev "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Discord.png" width="50" height="50">](https://discord.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Patreon.png" width="50" height="50">](https://patreon.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Twitter.png" width="50" height="50">](https://twitter.com/vrlabsdev "VRLabs")

</div>

---
