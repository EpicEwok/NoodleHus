# NoodleHus

A hus for Noodles in VRC (collaberation welcome and needed)

## Setup

This repository uses [UnityYAMLMerge](https://docs.unity3d.com/Manual/SmartMerge.html) to solve merge conflicts.

Before you begin contributing,add the following text to your `.git` or `.gitignore` file:

```
    [merge]
    tool = unityyamlmerge

    [mergetool "unityyamlmerge"]
    trustExitCode = false
    cmd = '<path to Unity 2018.4.20f1>\Editor\Data\Tools\UnityYAMLMerge.exe' merge -p "$BASE" "$REMOTE" "$LOCAL" "$MERGED"
```