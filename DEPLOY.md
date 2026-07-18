# Nasazení do nového GitHub repozitáře

## Varianta přes web GitHubu

1. Vytvořte nový veřejný repozitář bez automatického README.
2. Otevřete repozitář a zvolte **Add file → Upload files**.
3. Nahrajte celý rozbalený obsah balíčku, včetně skryté složky `.github` a souboru `.nojekyll`.
4. Potvrďte commit do větve `main`.
5. Otevřete **Settings → Pages**.
6. U položky **Source** zvolte **GitHub Actions**.
7. V kartě **Actions** sledujte workflow **Deploy Lovec vltavínů Reborn**.
8. Po dokončení bude hra dostupná na adrese `https://UZIVATEL.github.io/NAZEV-REPOZITARE/`.

## Důležité

- Na GitHub nenahrávejte samotný ZIP. Nahrajte jeho rozbalený obsah.
- `index.html` musí být přímo v kořeni repozitáře.
- Složka `.github/workflows` musí zůstat zachovaná.
- Po aktualizaci hry na iPhonu může být nutné zavřít starou kartu nebo odstranit starou ikonu PWA z plochy a přidat ji znovu.
