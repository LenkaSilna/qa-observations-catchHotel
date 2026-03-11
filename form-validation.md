# Bug report: Nekonzistentní validace formuláře – pole „Jméno“

## Shrnutí
Při odeslání prázdného objednávkového formuláře na mobilním zařízení se zobrazí validační chyby u většiny povinných polí.

Pole **„Jméno“**, které je označeno jako `required`, však validační chybu nezobrazí.

Zároveň u polí, kde se validační chyba zobrazí, **chyba nezmizí ani po zadání hodnoty**, což naznačuje problém s aktualizací validačního stavu formuláře.

---

## Prostředí

- Chrome DevTools – mobilní emulace
- Android zařízení – Chrome
- iPhone zařízení – Safari / Chrome

---

## Kroky k reprodukci

1. Otevřít stránku s objednávkovým formulářem na mobilním zařízení.
2. Nechat všechna pole prázdná.
3. Odeslat formulář.
4. Zobrazí se validační chyby u většiny povinných polí.
5. Pole **„Jméno“**, které je označeno jako `required`, validační chybu nezobrazí.
6. Do polí, kde je zobrazena validační chyba, zadat validní hodnotu.

---

## Očekávaný výsledek

- Pole **„Jméno“** by mělo zobrazit validační chybu při odeslání prázdného formuláře.
- Po zadání validní hodnoty do pole by měla validační chyba zmizet.

<img width="670" height="748" alt="image" src="https://github.com/user-attachments/assets/88f18160-a6e0-4829-831f-1bb15a8bb5d8" />

