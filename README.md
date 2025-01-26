# Always create user

Let `pm create-user` bypass some checks.

## Description

`isCreationOverrideEnabled` Android 14+

`canAddMoreProfilesToUser` Android 11 - 13 (Override by `isCreationOverrideEnabled`)

`isUserLimitReached` Android 7 - 13 (Override by `isCreationOverrideEnabled`)

`canAddMoreManagedProfiles` Android 6 - 10 (Move to `canAddMoreProfilesToUser`)

`isUserLimitReachedLocked` Android 4.2 - 6 (Rename to `isUserLimitReached`)

## Screenshot

![Island](https://testingcf.jsdelivr.net/gh/Xposed-Modules-Repo/io.github.icepony.alwayscreateuser@main/docs/img/Island.png) | ![Thanox](https://testingcf.jsdelivr.net/gh/Xposed-Modules-Repo/io.github.icepony.alwayscreateuser@main/docs/img/Thanox.png)
---|---

## Issuse

https://github.com/icepony/AlwaysCreateUser/issues