# Enkratna podloga in napadi nanjo

Laboratorijska vaja pri predmetu Varnost podatkov je namenjena sprotnemu
tedenskemu delu in učenju. Spoznali boste delo z bajti, šifro enkratne podloge
(OTP), napad ob večkratni uporabi ključa in gnetljivost tajnopisa.

## Priprava okolja

Potrebujete sodobni Python (priporočeno 3.12 ali novejši) in pakete
`jupyterlab`, `matplotlib` ter `cryptography`. Namestite jih z:

```sh
pip install jupyterlab matplotlib cryptography
```

Nato iz korena repozitorija odprite zvezek:

```sh
jupyter lab assignment.ipynb
```

## Delo z nalogo

- Navodila in prostor za rešitve so v **`assignment.ipynb`**.
- Tajnopisi so v **`data/ct_0.bin`–`data/ct_9.bin`**. Imenik `data/` ohranite
  poleg zvezka, saj zvezek uporablja relativne poti do teh datotek.
- Dopolnite celice z oznako `# VAŠA REŠITEV`. Ohranite podpise funkcij, navodila,
  priložene teste in metapodatke celic.
- Rešitve preverjajte s priloženimi testi, s poskušanjem in opazovanjem rezultatov.
  `NotImplementedError` v nedopolnjeni funkciji pomeni, da jo morate še napisati.
- Pri nalogi 5.4 ključ ugotovite s poskušanjem in sklepanjem o vsebini sporočil.
  `complete_key(cipher_texts)` naj zgolj vrne končni ključ kot `bytearray`;
  algoritma za iskanje manjkajočih bajtov ni treba implementirati.
- Po potrebi dodajte celice za raziskovanje. Pred oddajo ponovno zaženite zvezek
  od začetka, da preverite, ali je rešitev ponovljiva brez predhodnega stanja jedra.

Oddajte samo izpolnjeni **`assignment.ipynb`**. Podatkovnih datotek in razvojnega okolja ni treba oddajati.
