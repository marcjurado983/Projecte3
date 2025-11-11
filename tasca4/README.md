# Implementació d’OpenLDAP a Innovatech

## 2. Requeriments d'Infraestructura Inicial:
## 3. Tasques d'Implementació i Configuració del Servidor LDAP:
## 4. Integració de Client (Client Ubuntu Desktop):

## Descripció del projecte

**Innovatech**, una *start-up* tecnològica emergent, està experimentant un ràpid creixement i pateix un **caos en la gestió dels seus usuaris i accessos**.

Actualment, cada servei intern (servidor de fitxers, wiki de documentació, etc.) utilitza la seva pròpia base de dades d’usuaris i contrasenyes, i a més, als ordinadors clients s’usa **autenticació local**.  

Aquesta situació genera diversos problemes crítics:

###  Problemes actuals

- **Ineficiència Operativa:**  
  Cada cop que s’incorpora o marxa un empleat, l’equip tècnic ha de crear o eliminar el compte en múltiples sistemes.

- **Risc de Seguretat:**  
  Els usuaris sovint acaben reutilitzant contrasenyes entre serveis per evitar l’oblit.

- **Manca d’Escalabilitat:**  
  A mesura que Innovatech afegeix nous serveis, el problema es fa insostenible.

---

##  Objectiu del projecte

El **CEO d’Innovatech** ha contactat amb **EverPia** per implementar una **solució d’autenticació centralitzada**.

La solució proposada és utilitzar **OpenLDAP (Lightweight Directory Access Protocol)**, ja que és una eina **robusta i de codi obert**, alineada amb la filosofia d’Innovatech, que utilitza **GNU/Linux** a tots els seus sistemes.

---

##  Tasques a realitzar

La missió del projecte és **implementar el servei OpenLDAP** en un servidor Linux.

Les principals fases del projecte són:

1.  **Instal·lació del servei OpenLDAP.**  
2.  **Configuració del domini base.**  
3.  **Creació de la jerarquia d’unitats organitzatives (OUs).**  
4.  **Integració d’usuaris i grups** per gestionar els accessos a altres serveis de xarxa.  
5.  **Configuració d’un equip client** perquè autentiqui els usuaris mitjançant el directori.

---

##  Documentació i recursos

S’ha redactat un document on s’especifica clarament la feina que s’ha de desenvolupar.  
Aquest document està disponible al **plec de condicions tècniques** i també al **Moodle de l’assignatura**.

###  Material de classe (disponible al Moodle)

- **UD04.AA1:** Serveis de Directori  
- **UD04.AA2:** Instal·lació OpenLDAP  
- **UD04.AA3:** Configuració del directori  
- **UD04.AA5:** Agregar client al directori  

---


---

##  Autors

Projecte desenvolupat per l’equip tècnic d’**EverPia** per a **Innovatech**.

---

##  Llicència

Aquest projecte utilitza una llicència de codi obert compatible amb l’esperit d’Innovatech.  
Consulta el fitxer [`LICENSE`](./LICENSE) per a més detalls.

