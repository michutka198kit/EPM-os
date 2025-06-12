# Security Policy

| Version | Algorithm | Derivation | File Name |
| ------- | -------- | ----------- | --------- |
| 0.67   | ⭐ 4.5/5 | ⭐ 4/5 | ⭐ 2/5 |

## New Features For Higher Security On The Table
- Switch to AES-256-GCM From AES-128-CBC
- Possible unique salt along with users vault
- Avoid hashing in filename

## WARNING
 In the next update files will no longer be saved into vaults under program files, now it's going under appdata\local for less issues, this means your vault will have to be moved if you were using a previous version.
 If you were using version 0.67, and are going to update, you will lose all of you information if you're not careful, this is caused to to the switch from AES-128-CBC to AES-256-GCM. You will need to completly rewrite everything currently (but still easily drag and drop passwords from the old manager to the new) and I'm not going to create a method to encode everything from a old method to a new method. STAY SAFE

## Reporting a Vulnerability
[Go Here And Add The Lable Vulnerability](https://github.com/michutka198kit/EPM-os/issues/new)
