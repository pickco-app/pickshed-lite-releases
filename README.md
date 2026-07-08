# PickShed Lite — Downloads

Public release downloads for **PickShed Lite** (free, offline-first Horticulture Award compliance companion).

Installers and the update manifest (`pickshed-lite-manifest.json`) are published here as GitHub Releases. The application source lives in a separate private repository.

Grab the latest build from the [Releases](https://github.com/pickco-app/pickshed-lite-releases/releases) page.

---

## Installing / updating

PickShed Lite is a free tool and its installers are **not yet code-signed**. The app is safe, but because
it isn't signed with a paid Apple/Microsoft certificate, your operating system shows a one-time warning the
first time you open a new install or a new version. Here's how to get past it.

> ⚠️ **Temporary:** installers aren't code-signed yet. Once they are, this warning (and this section) goes
> away — nothing else about installing or updating changes.

### macOS

When you open the `.dmg` and drag **PickShed Lite** to Applications, the first launch may say *"PickShed
Lite can't be opened because Apple cannot check it for malicious software"* or *"…is damaged."*

**The easy way (recommended):**
1. In **Applications**, find **PickShed Lite**.
2. **Right-click** (or Control-click) the app icon → choose **Open**.
3. In the dialog that appears, click **Open** again.
4. That's it — every launch after this opens normally.

**If macOS says the app is "damaged"** (this can happen on downloads that picked up the quarantine flag),
open **Terminal** and run:

```bash
xattr -dr com.apple.quarantine "/Applications/PickShed Lite.app"
```

Then open the app normally. This applies the same way after installing an update.

### Windows

When you run the installer, **Windows SmartScreen** may show a blue *"Windows protected your PC"* screen.

1. Click **More info**.
2. Click **Run anyway**.
3. The installer proceeds as normal; later launches don't show the warning.
