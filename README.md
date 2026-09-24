# MI – kockázatok és mérés

Quarto-alapú weblap RStudio-projektként. Két fő oldala:

- **Figyelmeztetők** (`veszelyek.qmd`) – kik és mikor hívták fel a figyelmet a mesterséges intelligencia veszélyeire, Samuel Butlertől (1863) a 2026-os International AI Safety Reportig, a magyar vonatkozások (Karinthy Frigyes, Neumann János, EU MI-rendelet) kiemelésével.
- **Mérőeszközök** (`meroeszkozok.qmd`) – az MI-vel kapcsolatos attitűd-, szorongás-, bizalom- és MI-jártasság-skálák, a magyar adaptációk és hazai felmérések, valamint nemzetközi indexek és benchmarkok.

## Használat

1. Nyisd meg a `MI_honlap_01.Rproj` fájlt RStudióban.
2. Telepítsd a csomagokat: `install.packages(c("knitr", "rmarkdown"))`
3. Build panel → **Render Website** (vagy `quarto render` a terminálban).
4. Az eredmény a `_site/` mappában lesz.

Részletek: `projekt.qmd` („A projektről" oldal).
