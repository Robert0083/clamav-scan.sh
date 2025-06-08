# clamav-scan.sh

Ez a Bash script automatikusan lefuttatja a ClamAV vírusellenőrzőt egy megadott könyvtárban, naplóba írja az eredményeket, és időzíthető cron segítségével.

## Jellemzők
- `freshclam`: adatbázis frissítés
- `clamscan -r`: rekurzív vírusellenőrzés
- Napló: `/var/log/clamav_scan.log`
- Időzítés: napi cron futtatás

## Telepítés és használat
```bash
chmod +x clamav-scan.sh
./clamav-scan.sh

