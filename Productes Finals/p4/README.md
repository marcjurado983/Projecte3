# P04: Documentació servidor DNS

https://docs.google.com/document/d/1fMJzYdi-sVFpDed3UAGxCwd74Gs3P4lMx9WUXKfB3qc/edit?usp=sharing

# 🌐 Publicació de Configuracions de Servidor a GitHub

## 👨‍💻 Benvinguts, consultors!

Molt benvinguts a la vostra nova tasca dins d’**EverPia**.

Com a membres de l’equip de sistemes, ja heu superat un primer repte important:

# 🧩 Configurar un servidor de noms (DNS)

Aquesta configuració s’ha desenvolupat com a:

- prova de concepte,
- validació tècnica,
- i proposta d’infraestructura

per al nostre client:

# 🏢 Digicore

---

# ⚠️ Situació actual

Ara mateix, tota la configuració es troba únicament:

- dins d’una màquina virtual,
- en un entorn local,
- i sense control de versions.

Això representa diversos problemes:

- ❌ difícil replicació,
- ❌ manca de traçabilitat,
- ❌ risc de pèrdua de configuració,
- ❌ poca escalabilitat,
- ❌ dependència de la màquina original.

---

# 🎯 Objectiu de la tasca

L’objectiu és:

# 🚀 Publicar les configuracions a GitHub

Per tal de convertir la configuració del servidor en:

- reutilitzable,
- documentada,
- versionada,
- i fàcilment desplegable.

---

# 💡 Beneficis de treballar amb GitHub

Publicar les configuracions ens permet:

## ✅ Replicar servidors ràpidament
Sense haver de començar des de zero.

## ✅ Mantenir control de versions
Cada canvi queda registrat.

## ✅ Facilitar el treball en equip
Diversos tècnics poden col·laborar.

## ✅ Documentar la infraestructura
Configuració i documentació al mateix lloc.

## ✅ Recuperació ràpida
En cas d’error o desastre.

---

# 🛠️ Funcionament esperat

Quan sigui necessari desplegar un nou servidor:

## El procés hauria de ser:

### 1️⃣ Clonar el repositori

```bash id="git-clone-dns"
git clone URL_DEL_REPOSITORI
