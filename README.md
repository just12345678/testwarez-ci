# TESTWAREZ 2025 – Automatyzacja Testów w CI/CD: Praktyczne Warsztaty z Jenkins i GitHub Actions

Drogi Uczestniku,  

Cieszę się, że wybrałeś mój warsztat :)  

Aby zweryfikować środowisko, którego będziemy używać podczas warsztatu, proszę wykonaj kroki opisane w sekcji **INSTRUKCJE DO WARSZTATU**.

---

## INSTRUKCJE DO WARSZTATU

Upewnij się, że przychodzisz na warsztat z **laptopem** – najlepiej z systemem **Windows**.  
Twój laptop nie powinien mieć ograniczeń, takich jak:

- brak uprawnień administratora (potrzebne do instalacji narzędzi),  
- ograniczony dostęp do internetu (VPN, firewall, proxy itp.).  

---

## Wymagania wstępne

### Umiejętności
- Podstawowa znajomość testowania oprogramowania i systemu kontroli wersji  
- Konto GitHub oraz podstawowa wiedza o Git  

### Wymagania techniczne

#### 1. Zainstaluj VS Code IDE  
Pobierz i zainstaluj z:  
👉 [https://code.visualstudio.com/download](https://code.visualstudio.com/download)  

#### 2. Zainstaluj Java JDK (wersja 11 lub nowsza)  
Pobierz z:  
👉 [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/)  

Po instalacji otwórz **CMD** i sprawdź instalację:
```bash
java -version
javac -version
```

Obie komendy powinny zwrócić zainstalowaną wersję JDK.  

#### 3. Zainstaluj Python (wersja 3.13.2)  
Pobierz z:  
👉 [https://www.python.org/downloads/](https://www.python.org/downloads/)  

Podczas instalacji upewnij się, że zaznaczyłeś opcję:  
`Add python.exe to PATH`  

Następnie sprawdź instalację:
```bash
python --version
```

Powinieneś zobaczyć zainstalowaną wersję Pythona.  

---

## GitHub i konfiguracja projektu

#### 4. Forkuj repozytorium  
Przejdź do:  
[https://github.com/tklepacki/hustef-ci](https://github.com/tklepacki/hustef-ci)  

Kliknij **Fork**, aby utworzyć kopię w swoim koncie GitHub.  

> Nie masz konta na GitHubie? Najpierw utwórz je na [https://github.com](https://github.com)  

#### 5. Sklonuj swoje sforkowane repozytorium  
Sklonuj repozytorium na swój komputer lokalny:
```bash
git clone https://github.com/TWOJ_USERNAME/hustef-ci.git
```

#### 6. Otwórz projekt w VS Code  
Przejdź do sklonowanego folderu i otwórz go w VS Code.  

---

## Docker i Jenkins

#### 7. Zainstaluj Docker Desktop  
Pobierz z:  
[https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)  

Po instalacji sprawdź wersję:
```bash
docker -v
```

Powinieneś zobaczyć zainstalowaną wersję Dockera.  

#### 8. Pobierz obraz Dockera z Jenkinsem  
Uruchom w terminalu:
```bash
docker pull jenkins/jenkins:lts
```

---

## Wszystko gotowe!

Upewnij się, że wszystko jest zainstalowane i działa **przed warsztatem**, aby zapewnić płynny przebieg zajęć.  
Do zobaczenia wkrótce!  
