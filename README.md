# GrammarToolLinux

This is the **Linux** release version of the [GrammarTool](https://github.com/MarekLampas/GrammarToolSln) project.

[Avalonia](https://docs.avaloniaui.net/#supported-platforms) is supported on the following platforms:
- Debian 9 (Stretch) and higher
- Ubuntu 16.5 and higher
- Fedora 30 and higher

## Installation

1. Download this repository folder using *Code->DownloadZIP* button.

![alt text](https://github.com/MarekLampas/DiplomovaPracaLatex/blob/main/sablona-cze/obrazky/releaseDownload.png "Download app")

2. Open Terminal and go to **Downloads** or other folder, where downloaded ZIP is located.

```bash
cd ~/Downloads
```

3. Install unzip if needed.
- Check unzip version

```bash
unzip --v
```
- If unzip do not exist, install it

```bash
sudo apt get install unzip
```

4. Unzip Downloaded folder.

```bash
unzip GrammarToolLinux-main.zip
```

5. Go to unzipped folder.

```bash
cd GrammarToolLinux-main/linux-x64
```

6. Run application.

```bash
./GrammarTool
```

7. If you received **Permission denied**, you need to add permission and run the app again.

```bash
sudo chmod +x ./GrammarTool
```

```bash
./GrammarTool
```
