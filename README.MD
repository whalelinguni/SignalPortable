# 🐋 Signal Portable

UPDATE: This is dumb. It doesn't work. I was lazy with my testing. Signal does a something so you can't move data. It will only run on whatever machine it was originally ran on. Trying to run it on another machine it will just complain about the data. So it's portable as long as you don't try to run it on any other computer. Super handy. Neat. kthxbye.

This is the **second revision of Signal Portable**, a fully self-contained version of the Signal Desktop messaging app.

The original release used the PortableApps.com format, which worked by physically moving files in and out on launch and exit. Unfortunately, this method was prone to issues—if Signal was ever closed improperly (such as during a system crash or power outage), it could result in corrupted, unrecoverable data.

This new version avoids that risk entirely by using **symlinks** to handle data, greatly improving reliability and stability. Also included is a built-in updater that automatically fetches the latest Signal release directly from signal.org.

### 📦 [**DOWNLOAD Signal Portable**](https://www.mediafire.com/file/2xizsbd87bfr98i/SignalPortable.7z/file)

---

## 🔄 Features

- Fully portable: no installation required
- Self-contained and runs from USB or any folder
- Uses **symlinks** instead of moving data folders
- Safer shutdowns and better data persistence
- Includes a built-in **updater** to fetch the latest Signal release

---

## 📂 Usage

Just extract the portable folder anywhere and run `SignalPortable.exe`.

To update, run `SignalUpdate.exe`.

---


## ✅ Recommended

- Always close Signal normally before unplugging your USB or shutting down
- Run the updater periodically to stay current

---

© Signal Foundation — This is an unofficial portable repackaging.
