# Rolling Tab Target
![Release](https://img.shields.io/badge/release-v0.0.1-blue "Release")
### Description
This addon is for [uMMORPG CE](https://assetstore.unity.com/packages/templates/systems/ummorpg-components-edition-159401 "uMMORPG CE"). A simple rolling tab target, with a build in customizable range checker in for UMMORPG CE in the unity editor. The current intentions whit this is to some extend mimic the tabtarget behaviors of World of Warcraft.

### Features

- Rolling tab target.
- Range  checker
- Easy to use


### How to implement

- Take the BauTabTargeting Folder and drop into [uMMORPG CEs](https://assetstore.unity.com/packages/templates/systems/ummorpg-components-edition-159401 "uMMORPG CEs") Addons folder

- Find PlayerTabTargeting.cs and change it to a partial class

```javascript
public class PlayerTabTargeting 
```
```javascript
public partial class PlayerTabTargeting
```

- Find and comment out the following

```javascript
TargetNearest();
```
- After that insert this:

```javascript
MMOTabTarget();
```

