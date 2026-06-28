
<img width="2120" height="1280" alt="Features+Usage Rounded" src="https://github.com/user-attachments/assets/eee92cf6-ab4e-4c23-9c08-381a842262f3" />

## About
What is EPM-os? It means "Easy Password Manager", Easy to use, secure, and super benifical.\
I can't say im great at cryptography or cyber security but I honestly wanted to make my own and learn, and show what I learned with a result.\
This project is fully created using only python currently as well.

## Goals
Easy, Multiuse, Portiable, NO APPS, NO INTERNET, NEVER TRACKED, Local use, Fully encrypted\
Access anywhere anytime (Computer required for setup currently)

## How To Use
Don't Currently... Just don't.\
I'm trying to release a version that can handle updates...\
BUT most importantally I need to make myself like how easy it is to use on any device across all of them.\
So it's more of a matter on which features I need to cook with to make it easier for me.\
THEN it will release, meanwhile you can watch the update list change as features are added/tested/revised.\
I wish I was good at designing UI in python but for some reason it's somewhat difficult to get a good result

## What's New Next Version
PLEASE check out the "issues" tab to see improvements make along the way. Currently Under V0.90\
Details of V0.70-V0.80 is at the bottom of this page

---

<div>

## Features
<table>
  <tbody>
    <tr>
      <td>🖱️ <strong><code>Right/Left Click Drag</code></strong></td>
      <td>Easily move around users/passwords without coping</td>
    </tr>
    <tr>
      <td>🔀 <strong><code>Password Randomizer</code></strong></td>
      <td>Generate random passwords with tweakable settings for any combo needed</td>
    </tr>
    <tr>
      <td>➕ <strong><code>Add Accounts</code></strong></td>
      <td>Put in a passcode you want then create any account</td>
    </tr>
    <tr>
      <td>👥 <strong><code>Profiles</code></strong></td>
      <td>Separate profiles for work, school, personal, etc.</td>
    </tr>
   <tr>
      <td>🎨 <strong><code>Color Coded</code></strong></td>
      <td>Easily see each profile and amount of passwords per single profile</td>
    </tr>
    <tr>
      <td>💾 <strong><code>Autosaves/Updates</code></strong></td>
      <td>Easily update software and autosave vaults anywhere</td>
    </tr>
    <tr>
      <td>🔍 <strong><code>Search Menu</code></strong></td>
      <td>Quickly filter by domain, user, profile, and more</td>
    </tr>
    <tr>
      <td>🔐 <strong><code>Encrypted Vaults</code></strong></td>
      <td><strong>Fully encrypted</strong>. Only accessible via your master password.</td>
    </tr>
    <tr>
      <td>📡 <strong><code>Syncing Passwords</code></strong></td>
      <td>Easily sync your vault from other devices <em>(Refactoring Server Version Currently)</em></td>
    </tr>
    <tr>
      <td>🔁 <strong><code>Access on any device</code></strong></td>
      <td>Offline moble varient allows you to use anytime anywhere</td>
    </tr>
    <tr>
      <td>☁️ <strong><code>Easy Backups</code></strong></td>
      <td>Easy backups for saving to local or cloud-based storage securly</td>
    </tr>
    <tr>
      <td>⭐ <strong><code>Easy to Use</code></strong></td>
      <td>Intuitive UI to easily view, change, and keep any flow you need for managing</td>
    </tr>
    <tr>
      <td>🚀 <strong><code>More Coming Soon!</code></strong></td>
      <td>New features and upgrades are on the way!</td>
    </tr>
  </tbody>
</table>

</div>


<div>
  
---

## Current Version Confirmed Support
<table>
  <tr>
    <td style="vertical-align: top; padding-right: 40px;">
      <table border="1" cellspacing="0" cellpadding="6">
        <tr><th>Platform</th><th>Status</th></tr>
        <tr><td>Windows 10</td><td>✅ Confirmed</td></tr>
        <tr><td>Windows 11</td><td>✅ Confirmed</td></tr>
        <tr><td>Linux</td><td>❌ Unsupported</td></tr>
        <tr><td>macOS</td><td>❌ Unsupported</td></tr>
       <tr><td>ios</td><td>❌ Supporting Soon... Maybe... Hopfully</td></tr>
       <tr><td>Andriod</td><td>❌ Unsupported</td></tr>
      </table>
  </tr>
</table>

---

THIS IS CURRENT AS OF V0.80\
Will update when V0.90 is finished

<details>
<summary>
<h2>🔧 Fixes (10)</h2>
</summary>

<div>

- Fixed `Profile: None` not working for websites and filters.
- Fixed installer compatibility with server dependency.
- Fixed server process remaining active after closing the server window.
- Fixed editing entries creating duplicates when changing website/domain fields.
- Fixed autofill issues introduced after localhost communication merge.
- Fixed extension refresh/status updates before manager communication completes.
- Fixed extension version not updating in settings.
- Fixed password blur not applying to all passwords.
- Fixed native messaging extension hosting portability issues.
- Fixed update checking for app and extension.

</div>
</details>

<details>
<summary>
<h2>⚙️ Changes (15)</h2>
</summary>

<div>

- Increased profile filter box size.
- Upgraded encryption to **AES-256-GCM**.
- Added unique salts per user vault.
- Changed vault filenames to avoid hashing.
- Increased key derivation iterations from **100,000 → 1,000,000**.
- Enabled "Show Password" by default.
- Introduced a new UI across the application.
- Updated server to support new encryption methods.
- Simplified vault settings paths.
- Redesigned account creation and master password UI.
- Improved light theme styling.
- Simplified and minimized autofill banner UI.
- Redesigned logo and branding.
- Merged vault settings into encrypted vault files.
- Added version metadata directly into vault files.

</div>
</details>

<details>
<summary>
<h2>✨ Additions (31)</h2>
</summary>

<div>

- Added `Profile: None` to password manager filters.
- Added current version numbers to window titles.
- Added copy username/password actions.
- Added automatic clipboard clearing after 10 seconds.
- Added Dark Mode.
- Added default account settings.
- Added per-user settings.
- Added profile-specific settings.
- Added reset to defaults option.
- Added username and master password changes.
- Added view settings.
- Added password blur setting.
- Added date format settings.
- Added additional security components.
- Added account creation prompt for missing vaults.
- Added user display names.
- Added UI and settings for server dependency.
- Added quick-access server launch button.
- Added server download integration.
- Added timestamped vault export folders.
- Added profile opening options (`All`, `None`, and specific profiles).
- Added sortable columns for websites, emails, passwords, profiles, and dates.
- Added selectable date display columns.
- Added password generator customization options.
- Added "Open Website" to dropdown menus.
- Added encryption for local communication.
- Added extension autofill support without requiring the server.
- Added raw vault viewer/editor.
- Added offline server website support.
- Added password content searching with highlighting support.
- Added profile colors.

</div>
</details>
