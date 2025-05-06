
```
𝗖 𝗢 𝗗 𝗘 𝗫 
```

## Installation & Usage

1. Push file to device:
```bash
adb push codex /data/local/tmp/
```

2. Set permissions:
```bash
adb shell
su
chmod 777 /data/local/tmp/CODEX
```
3. Run:
```bash
cd /data/local/tmp
./CODEX <package_name>
```

Example:
```bash
./CODEX com.example.app
```

Note: Root access required to run this tool.

Output files will be saved in:
```
/data/local/tmp/dex_dump_[package_name]/
```
# Alternative Run

Copy file to /data/local/tmp/

Give permission manual

![Preview](screenshots/permission.jpg)

open your terminal 

```bash
su
```
```bash
cd /data/local/tmp/CODEX
```
```bash
./CODEX com.example.app
```
Telegram Information 
---
@Qwanwin | @codex4444
```
