# Guia d'Ús Tècnica (Manual Operatiu)

# Guia d'Ús Tècnica – KeePassXC Portable

Aquesta guia explica pas a pas com utilitzar KeePassXC Portable per gestionar contrasenyes de manera segura dins l’equip tècnic.

---

## 1. Instal·lació i Configuració Inicial

### Descàrrega i ús portable

1. Accedeix a la pàgina oficial portable que he utlitzat: https://portableapps.com/downloading/?a=KeePassXCPortable&s=s&p=&d=pa&n=KeePassXC%20Portable&f=KeePassXCPortable_2.7.10.paf.exe
2. Descarrega la versió **Portable** segons windows en el meu cas.
3. Descomprimeix el fitxer `.zip` en una carpeta segura o a descarregues en el que he fet jo per exemple.

### Crear una nova base de dades (BBDD)

Quan obres KeePassXC Portable per primer cop, veuràs una pantalla com aquesta:

![Pantalla inicial de KeePassXC](img/kee_pass_inicial.png)

1. Fes clic a **"Create Database"**.
2. Introdueix un nom i una descripció per a la base de dades.
3. Defineix una **contrasenya mestra** segura (no la perdis!).
4. Desa la base de dades com a fitxer `.kdbx` en una ubicació segura.

---

## 2. Generació de Contrasenyes Segures

1. Obre la base de dades i crea una entrada nova (`+`).
2. Fes clic a la icona de clau 🔑 per obrir el **generador de contrasenyes**.
3. Ajusta els paràmetres:
   - Longitud (recomanat: 16 o més)
   - Lletres majúscules, minúscules, números i símbols
4. Clica **"Generar"** i copia la contrasenya generada.
5. Desa l’entrada amb el nom del servei i l’usuari.

*Captura d’exemple del generador → `img/generador_contrasenyes.png`*

---

## 3. Exemples d'Ús i Emplenament Automàtic

### Desar una credencial de correu electrònic

1. Crea una entrada amb el nom "Gmail", per exemple.
2. Omple els camps:
   - Nom d’usuari (ex: nom@gmail.com)
   - Contrasenya (pots generar-ne una)
   - URL (ex: https://mail.google.com)
3. Desa l’entrada.

*Captura → `img/gmail_credencial.png`*

### Desar una credencial d’un servei web o aplicació

Segueix els mateixos passos que a dalt, canviant el nom i l’URL pel servei concret (ex: Discord, Moodle...).

### Emplenament automàtic (opcional)

KeePassXC es pot integrar amb navegadors com Firefox o Chrome, però cal:

1. Instal·lar l’extensió **KeePassXC-Browser**.
2. Activar la integració des del menú `Eines > Configuració > Integració de Navegador`.
3. Connectar el navegador amb la base de dades oberta.

*Captura → `img/extensio_navegador.png`*

---

## 4. Gestió de Còpies de Seguretat (Backup)

### Fer una còpia de seguretat del fitxer `.kdbx`

1. Tanca KeePassXC per evitar errors.
2. Copia el fitxer `.kdbx` a un lloc segur:
   - USB xifrada
   - Carpeta protegida amb contrasenya
   - Servei al núvol amb xifratge (com MEGA, Tresorit…)

### Recomanacions

- No comparteixis mai el fitxer `.kdbx` sense contrasenya mestra.
- Fes còpies regulars (setmanals o mensuals).
- Desa sempre la còpia en un lloc diferent del fitxer original.

---

## 📁 Estructura de fitxers



