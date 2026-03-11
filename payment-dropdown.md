# Bug report: Dropdown „Způsob platby“ se na mobilu otevírá mimo viewport

## Shrnutí

Na mobilním zařízení se při otevření pole **„Způsob platby“** (select / dropdown) zobrazí nabídka mimo viditelnou část obrazovky.  
Stránka se zároveň rozšíří do šířky a objeví se **horizontální scroll**, což zhoršuje použitelnost formuláře na mobilu.

---

## Prostředí

- Chrome DevTools – mobilní emulace
- Android zařízení – Chrome
- iPhone zařízení – Safari / Chrome

---

## Kroky k reprodukci

1. Otevřít stránku s objednávkovým formulářem na mobilním zařízení.
2. Najít pole **„Způsob platby“**.
3. Kliknout na select / dropdown.

---

## Očekávaný výsledek

Dropdown by měl být zobrazen **uvnitř viewportu** a být plně čitelný bez nutnosti horizontálního scrollování stránky.

---

## Skutečný výsledek

Dropdown se otevře **mimo viewport** a způsobí **horizontální scroll stránky**, což ztěžuje výběr možnosti na mobilním zařízení.

<img width="649" height="745" alt="image" src="https://github.com/user-attachments/assets/0e805d95-b36e-485e-92b9-81a78ce79225" />
