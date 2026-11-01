# I-SUNS: Zadanie č. 2 — Air Quality

Stromy, stroje, hlasovania a redukcia dimenzie. Predpoveď koncentrácie oxidu uhoľnatého (`co`, mg/m³) vo vzduchu
na základe odoziev chemických senzorov, teploty, vlhkosti a času merania (regresia).

## Obsah

- `assignment.ipynb` — celé riešenie (príprava dát, modely, redukcia dimenzie, výber príznakov)
- `air_quality.csv` — dataset (9 507 záznamov, 14 stĺpcov)
- `Dokumentacia/` — dokumentácia v LaTeX (`zadanie.tex`, obrázky v `img/`)
- `requirements.txt` — použité knižnice

## Časti zadania

1. Príprava dát — čistenie (null, duplikáty, outliery), kódovanie, rozdelenie train/test, normalizácia
2. Modely — rozhodovací strom, ensemble model, SVM; vyhodnotenie pomocou MSE/RMSE, R² a rezíduí
3. Redukcia dimenzie — 3D graf vybraných príznakov vs. 3D graf po PCA
4. Výber podmnožiny príznakov — podľa korelačnej matice, dôležitosti z ensemble modelu a variancie (PCA)

## Spustenie

```powershell
uv venv --python 3.12 --prompt zadanie2
uv pip install -r requirements.txt
.venv\Scripts\activate
jupyter lab
```

## Autor

Ivan Yachmenov, FEI STU, 2026
