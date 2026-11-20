# merwrepo — Sileo / Cydia source

Общий репозиторий твиков merwleem. Работает и в Sileo, и в Cydia.

## Адрес источника

```
https://merwleem.github.io/merwrepo/
```

**Sileo:** Sources → `+` → Enter URL → вставить ссылку → Refresh.

**Cydia:** Sources → Edit → Add → вставить ссылку → Add Source → Refresh.

Если Cydia или Sileo ругается на отсутствие подписи — подтвердите добавление вручную (репозиторий без GPG-подписи, но с контрольными суммами в `Release`).

## Сейчас в репозитории

- **iOS13 Volume HUD** 1.9.1 — rootful iOS 12, MobileSubstrate, PreferenceLoader, arm64 (A7–A11). [Deb](https://merwleem.github.io/merwrepo/com.local.ios13volumehud_1.9.1_iphoneos-arm.deb).

## Файлы

- `Packages`, `Packages.gz`, `Packages.bz2` — метаданные для Sileo и Cydia;
- `Release` — MD5/SHA1/SHA256 контрольные суммы;
- `com.local.ios13volumehud_1.9.1_iphoneos-arm.deb` — пакет.

## Как добавить следующий твик

1. Положить `.deb` в корень.
2. Добавить запись в `Packages`.
3. Пересобрать `Packages.gz` и `Packages.bz2`, обновить `Release`.
4. Запушить — GitHub Pages обновится сам.

Пакеты собраны с meow by sqmrak, https://github.com/sqmrak/meow.
