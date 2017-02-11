# Simple Sprite Packer Fix

**Simple Sprite Packer**: [Unity Asset Store](https://www.assetstore.unity3d.com/en/#!/content/23276).

当前 Unity Asset Store 中的版本为`1.9`，已经很久没有更新了，由于 Unity 内置的图片打包工具已完全免费，所以作者应该也不会进行更新了，随着 Unity 的版本不断更新，API 会出现不兼容的情况，一些特殊情况下，此工具还是有一定的价值，进行一些修复还可继续使用。


## Changelog

### Version 1.9f1

修复 Unity 5.3 后，`EditorApplication` 被移除，使用 `EditorSceneManager` 代替后，所引发的 API 变更所产生的问题。