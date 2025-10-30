# 🛠️ DevOps CI/CD Demo

Mini-projekt pokazujący **Python + Flask** w kontekście **DevOps i CI/CD**.

---

## 🔹 Cel projektu

- Pokazać podstawy tworzenia aplikacji webowej w Python + Flask  
- Przygotować projekt pod **CI/CD** (testy + automatyzacja)  
- Mieć gotowe repozytorium do portfolio

---

## 📁 Struktura projektu

devops-ci-cd-demo/
├── app/
│ └── app.py # główny serwer Flask
├── tests/
│ └── test_app.py # testy pytest
├── venv/ # wirtualne środowisko (ignorowane przez git)
├── .gitignore
├── requirements.txt
└── README.md


---

## ⚡ Uruchomienie lokalnie

1. **Sklonuj repozytorium:**

```bash
git clone https://github.com/WParchanska/devops-ci-cd-demo.git
cd devops-ci-cd-demo

2.Stwórz i aktywuj wirtualne środowisko:

python3 -m venv venv
# Linux/macOS
source venv/bin/activate
# Windows
venv\Scripts\activate

3.Zainstaluj zależności:

pip install -r requirements.txt

4.Uruchom aplikację:

python app/app.py

5.Otwórz w przeglądarce: http://127.0.0.1:5000/

Powinieneś zobaczyć komunikat: "Hello from DevOps"


🧪 Testy

Uruchom testy przy użyciu pytest:

pytest
