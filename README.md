Port LabZSK na Linuxa

Port został stworzony na podstawie plików z tego repozytorium: https://github.com/Konrad-Ziarko/LabZSK

Testy były przeprowadzone na Kali Linux Rolling, x86_64, Mono 6.14.1, GNOME
Ze względu na wykorzystanie Mono, port powinien działać również na innych dystrybucjach Linuxa, szczególnie Debian i Ubuntu ale nie były one testowane.

Potrzebne są: Mono, GTK2, libgdiplus

Pobieranie: 

```bash
git clone https://github.com/hellman305/LabZSK_LinuxPort.git
cd LabZSK_LinuxPort
```

Kompilacja: 
```bash
TERM=dumb xbuild LabZKT/LabZSK.csproj
```
Uruchamianie:
```bash
TERM=dumb mono LabZKT/bin/Debug/LabZSK.exe
```


LabZSK version 1.2.3.0
