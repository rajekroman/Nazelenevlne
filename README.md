# Lovec vltavínů: Zelená vlna — Reborn 5.1

Kompletní samostatná mobilní hra pro webový prohlížeč a GitHub Pages.

## Obsah hry

- pět rozdílných lokalit: Chlum, Ločenice, Nesměň, Besednice a Malše/Slávie;
- prostředí stylizované podle skutečných míst;
- dotykový joystick a jedno kontextové tlačítko;
- hledání, kopání, určování vzorků a zahrabávání profilů;
- hlídky, traktor, doprava, bossové a funkční ukazatel nebezpečí;
- vlastní hudební doprovod pro každou lokalitu;
- ukládání postupu, rekordy, offline režim a instalace na plochu telefonu.

## Spuštění lokálně

Hru nespouštějte dvojklikem přes `file://`. Ve složce projektu spusťte lokální server:

```bash
python3 -m http.server 8080
```

Potom otevřete `http://localhost:8080`.

## GitHub Pages

Repozitář už obsahuje workflow `.github/workflows/pages.yml`. Po nahrání souborů do větve `main` nastavte v GitHubu:

**Settings → Pages → Source → GitHub Actions**

Deployment se potom spustí automaticky při každém pushi do větve `main`.

Podrobný postup je v souboru [DEPLOY.md](DEPLOY.md).
