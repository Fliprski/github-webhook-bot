# github-webhook-bot

KROK 1: Ustawienie w GitHubie (Sekret)
1. Wejdź w swoje repozytorium na GitHub.
2. Kliknij u góry Settings.
3. W menu po lewej: Secrets and variables -> Actions.
4. Kliknij zielony przycisk New repository secret.
5. Wpisz nazwę: DISCORD_WEBHOOK_URL
6. Wklej link do webhooka z Discorda w pole Secret.
7. Kliknij Add secret.

KROK 2: Wklejenie Kodu (Workflow)
1. Wróć do zakładki Code (główna strona repozytorium).
2. Kliknij Add file -> Create new file.
3. W polu nazwy pliku wpisz: .github/workflows/discord-bot.yml
4. Wklej kod z pliku ```discord-bot.yml``` w całości (zastąp wszystko, co tam ewentualnie masz):
5. Kliknij przycisk Commit changes... (w prawym górnym rogu).
6. Wpisz wiadomość (np. "Naprawa bota") i kliknij Commit changes.