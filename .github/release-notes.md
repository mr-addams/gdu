## gdu ${TAG} — Linux amd64 + arm64 / aarch64

Unofficial Linux packages for [gdu ${TAG}](https://github.com/dundee/gdu/releases/tag/${TAG}).
Source code is unmodified — cross-compiled from the upstream tag.

### Installation

**Debian / Ubuntu / Raspberry Pi OS (amd64):**
```bash
dpkg -i gdu_*_amd64.deb
```

**Debian / Ubuntu / Raspberry Pi OS (arm64):**
```bash
dpkg -i gdu_*_arm64.deb
```

**Alpine Linux (amd64):**
```bash
apk add --allow-untrusted gdu_*_x86_64.apk
```

**Alpine Linux (arm64):**
```bash
apk add --allow-untrusted gdu_*_aarch64.apk
```

**RPM — amd64 (Fedora / RHEL / openSUSE):**
```bash
rpm -i gdu-*x86_64.rpm
```

**RPM — arm64 (Fedora / RHEL / openSUSE):**
```bash
rpm -i gdu-*aarch64.rpm
```

**Raw binary:**
```bash
# amd64
install -m755 gdu_linux_amd64 /usr/local/bin/gdu
# arm64
install -m755 gdu_linux_arm64 /usr/local/bin/gdu
```

---

Неофициальные Linux-пакеты (amd64 + arm64). Код не изменён — кросс-компиляция из апстрим-тега.
