# Project-appweb
El nostre projecte és un Gestor de Vehicles de Renting, una aplicació web que permet gestionar vehicles, clients i contractes de renting. L’objectiu és facilitar el control dels vehicles disponibles, els lloguers actius i l’historial de contractes, mitjançant una interfície clara i funcional.

# 🚗 Gestor de Vehicles de Renting

Aplicació web per gestionar vehicles d’un servei de renting. Desenvolupada com a projecte del mòdul de Desenvolupament d’Aplicacions Web (DAW).

## 📌 Descripció

Aquesta aplicació permet realitzar operacions bàsiques (CRUD) sobre vehicles, com afegir, consultar, modificar o eliminar-los. Està pensada per portar el control intern d’un parc de vehicles disponibles per renting.

Tecnologies utilitzades:
- HTML, CSS i JavaScript (frontend)
- Vue.js (frontend amb patró MVVM)
- Node.js + Express (backend)
- MongoDB + Mongoose (base de dades)

---

## 🧱 Arquitectura i estructura de carpetes
A DEFINIR


---

## ⚙️ Funcionalitats

- 🔧 Afegir nous vehicles al sistema
- 🔍 Consultar vehicles disponibles
- ✏️ Modificar dades d’un vehicle
- 🗑️ Eliminar vehicles

---

## 🧩 Classe principal

```plaintext
Vehicle
-------
- id
- marca
- model
- matrícula
- estat (disponible, llogat, manteniment)

