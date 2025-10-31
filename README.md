# Tugas 2 — Laundry (Java + JavaDoc)

Proyek kecil OOP: `Job` (base), `LaundryJob` (turunan), dan `MainApp` (demo).  
Sudah diberi JavaDoc dan bisa digenerate ke HTML.

## Struktur
```text
Tugas2/
├─ src/
│  └─ tugas2/
│     └─ laundry/
│        ├─ Job.java
│        ├─ LaundryJob.java
│        └─ MainApp.java
├─ docs/                 ← output JavaDoc (setelah Generate)
└─ README.md
```

## Fitur Singkat
- `Job`: `detailedInfo()`, `checkStatus()`, `displayRoute()`, `displayEstimatedDuration()`, `slowDown()`, `speedUp()`
- `LaundryJob`: override `displayEstimatedDuration()` & `displayRoute()`
- `MainApp`: contoh pemakaian

## Jalankan
- **IntelliJ**: klik kanan `MainApp` → **Run**
- **CLI (opsional)**:
  ```bash
  javac -d out src/tugas2/laundry/*.java
  java -cp out tugas2.laundry.MainApp
Generate JavaDoc (IntelliJ)
Tools → Generate JavaDoc… → Scope: Whole project → Output: docs/ → Visibility: protected → Generate.
(Opsional args: -encoding UTF-8 -charset UTF-8 -docencoding UTF-8)


### Muhamad Robi Ardita😊





