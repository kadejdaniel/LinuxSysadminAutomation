# Linux Server Administration & Automation

**Projekt praktyczny skupiający się na implementacji kluczowych zadań administracji systemami Linux (bez GUI), z naciskiem na bezpieczeństwo, automatyzację i zdalne zarządzanie.**

---

## Cele Projektu

Celem projektu była praktyczna implementacja umiejętności w zakresie administracji serwerem Linux poprzez konfigurację środowiska wirtualnego, zabezpieczenie dostępu oraz automatyzację rutynowych zadań operacyjnych za pomocą skryptów Bash.

---

##  Kluczowe Osiągnięcia i Kompetencje

### I. Konfiguracja i Hardening Systemu

Demonstracja umiejętności w zakresie konfiguracji sieciowej i zabezpieczania podstawowych usług dostępu zdalnego.

* **Zdalny Dostęp (SSH):** Ustanowienie i weryfikacja stabilnych połączeń SSH z różnych platform klienckich (OpenSUSE, Windows 11) do wirtualnej maszyny (VM).
* **Konfiguracja Sieci:** Skonfigurowanie karty sieciowej w VirtualBox w trybie mostkowanym (Bridged Adapter) w celu zapewnienia pełnej widoczności serwera w sieci LAN.
* **Wzmocnienie Bezpieczeństwa (Hardening):** Podstawowa konfiguracja firewalla oraz zabezpieczenie dostępu SSH (np. zmiana portu, wyłączenie logowania jako root).

### II. Automatyzacja Procesów (Bash Scripting)

Rozwój i implementacja skryptów automatyzujących rutynowe i powtarzalne zadania administracyjne.

* **Skrypt Backupujący:** Automatyczne tworzenie i zarządzanie kopiami zapasowymi wskazanych katalogów.
* **Zarządzanie Użytkownikami:** Skrypt do automatyzacji procesu tworzenia nowych kont użytkowników, włączając tworzenie katalogów domowych i przypisywanie do określonych grup systemowych.
* **Kontrola Wersji (Git):** Skrypt do automatycznego zatwierdzania (commit) i wysyłania (push) lokalnych zmian do zdalnego repozytorium na GitHubie.
* **Aktualizacje Systemu:** Skrypt do automatycznego wykonywania pełnego cyklu aktualizacji systemu (instalacja pakietów, usuwanie niepotrzebnych zależności).
* **Diagnostyka Serwera:** Skrypt wyświetlający podstawowe metryki i stan działania systemu (CPU, RAM, użycie dysku).

### III. Środowisko Technologiczne

| Narzędzie | Rola w Projekcie |
| :--- | :--- |
| **VirtualBox** | Środowisko wirtualizacyjne do izolacji i testowania konfiguracji serwera (Linux VM bez GUI). |
| **OpenSSH** | Protokół i narzędzia do bezpiecznego zdalnego zarządzania serwerem. |
| **Bash Scripting** | Język wykorzystany do automatyzacji zadań operacyjnych i administracyjnych. |
| **Git / GitHub** | Kontrola wersji, dokumentacja kodu i konfiguracji. |

---

##  Plan Rozwoju (Future Scope)

Projekt jest w fazie ciągłego rozwoju, planowane kolejne kroki obejmują:

* Implementacja narzędzi do monitorowania **wolnego miejsca na dysku** z systemem generowania alertów.
* Konfiguracja monitorowania kluczowych **procesów systemowych** i zużycia zasobów.

---
