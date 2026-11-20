# merwrepo — Sileo source

Общий репозиторий твиков merwleem.

## Адрес источника

```
https://merwleem.github.io/merwrepo/
```

Sileo → Sources → `+` → Enter URL → вставить ссылку → обновить.

## Сейчас в репозитории

- **iOS13 Volume HUD** 1.9.1 — rootful iOS 12, MobileSubstrate, PreferenceLoader, arm64 (A7–A11). [Прямая ссылка на deb](https://merwleem.github.io/merwrepo/com.local.ios13volumehud_1.9.1_iphoneos-arm.deb).

## Как добавить следующий твик

1. Положить `.deb` в корень репозитория.
2. Добавить запись в `Packages` (Package / Name / Version / Architecture / Filename / Size / SHA256 / Description).
3. Пересобрать `Packages.gz` и обновить контрольные суммы в `Release`.
4. Запушить — GitHub Pages обновится сам.

Пакеты собраны с meow by sqmrak, https://github.com/sqmrak/meow.
