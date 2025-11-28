# PVA4 - Programování a vývoj aplikací

## PHP WebApp – Výchozí projekt

Tento repozitář slouží jako **výchozí šablona** pro vaši semestrální aplikaci.

V průběhu roku budeme aplikaci **postupně rozšiřovat** na hodinách podle témat uvedených v moodlu.

Každé rozšíření bude zadáváno formou **samostatného úkolu** v GitHub Classroom.  
Vaším úkolem bude tyto části implementovat přímo v tomto repozitáři.

---

## 🧩 Požadavky na kvalitu kódu

Kód v tomto repozitáři musí splňovat základní pravidla kvality a přehlednosti.  
Tato pravidla se kontrolují při opravách i v rámci automatických testů.

### ✔ 1. Struktura a organizace kódu
- Jeden soubor = jedna zodpovědnost. (Např. připojení k DB nepatří do index.php.)
- Nesmí vznikat duplikovaný kód. Pokud používáte něco opakovaně, přesuňte to do funkce nebo samostatného souboru.

### ✔ 2. Čitelnost
- Odsazení pomocí **tabulátoru** (ne mezer).
- Dodržujte prázdné řádky mezi logickými bloky kódu.
- Pište názvy funkcí a proměnných smysluplně a výstižně.:
  - `getUser()` je lepší než `g_u()`  
  - `$totalPrice` je lepší než `$p1`

### ✔ 3. Komentáře
- Komentujte tam, kde je to potřeba.  
- Komentáře **nevysvětlují co**, ale **proč**:
  ```php
  // Limitujeme počet výsledků kvůli výkonu databáze
  $sql = "SELECT ... LIMIT 100";
  ```
### ✔ 4. Git a verzování

- Odevzdávejte čisté commity – každý commit má mít jasný popis.
- Neposílejte do repozitáře soubory, které tam nepatří (např. vendor/, .idea/).
- Commitujte postupně, ne až před deadlinem.
