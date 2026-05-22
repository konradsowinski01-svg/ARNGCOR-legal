# ARNGCOR — dokumenty prawne (publiczne)

Pliki `.txt` — ten sam tekst co w aplikacji (`assets/legal/`).

## Linki do wklejenia (Google, App Store)

Po wypchnięciu **publicznego** repo na GitHubie zamień `TWOJ_USER` i nazwę repo:

- **Strona główna:**  
  `https://raw.githubusercontent.com/TWOJ_USER/arngcor-legal/main/index.txt`

- **Polityka prywatności:**  
  `https://raw.githubusercontent.com/TWOJ_USER/arngcor-legal/main/privacy.txt`

- **Regulamin:**  
  `https://raw.githubusercontent.com/TWOJ_USER/arngcor-legal/main/terms.txt`

Te adresy otwierają się w przeglądarce jako zwykły tekst (bez HTML).

Alternatywa — podgląd na GitHubie (z menu repo):  
`https://github.com/TWOJ_USER/arngcor-legal/blob/main/privacy.txt`

## GitHub Pages — nie jest wymagane

Wystarczy publiczne repo + linki `raw.githubusercontent.com` powyżej.

## W aplikacji (opcjonalnie)

W `dart_defines.supabase.json`:

```json
"LEGAL_PRIVACY_URL": "https://raw.githubusercontent.com/TWOJ_USER/arngcor-legal/main/privacy.txt"
```
