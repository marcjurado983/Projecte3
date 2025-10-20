  # Projecte Gestor de Contrasenyes

## Fase 1: Anàlisi i Justificació (Informe tècnic) [Informe)](informe/informe.md)

Aquest informe ha de justificar tècnicament per què és necessari un gestor de contrasenyes i comparar les opcions disponibles.

### Què cal incloure?

1. **Introducció i Justificació**
   - Explicar per què les contrasenyes febles o reutilitzades són un risc crític (ex. atacs de diccionari, credential stuffing).
   - Destacar la funció d’un gestor de contrasenyes per mitigar aquests riscos.

2. **Comparativa Tècnica**
   - Realitzar una taula comparativa entre:
     - **Bitwarden (Online / Núvol):** sincronització, xifratge end-to-end, accés multiplataforma, cost i model freemium.
     - **KeePassX / KeePassXC (Offline / Escriptori):** emmagatzematge local (fitxer KDBX), independència del núvol, codi obert, portabilitat.

3. **Avantatges i Inconvenients**
   - Resumir els principals pros i contres de cada model (online vs offline) des de la perspectiva de seguretat, usabilitat i continuïtat del negoci.

4. **Recomanació**
   - Triar l’eina més adequada per a l’equip tècnic i justificar la decisió.

---

## Fase 2: Guia d’Ús Tècnica (Manual operatiu) [Guia](Guia/guia.md)

Crear una guia clara per a l’equip tècnic basada en l’eina escollida a la Fase 1 (Bitwarden, KeePassX, etc).

### Contingut obligatori

1. **Instal·lació i Configuració Inicial**
   - Descàrrega, instal·lació i creació del compte mestre o base de dades.

2. **Generació de Contrasenyes Segures**
   - Com utilitzar el generador de contrasenyes (paràmetres, longitud, caràcters especials).

3. **Exemples d’Ús i Emplenament Automàtic**
   - Desa una credencial d’un compte de correu electrònic.
   - Desa una credencial d’una aplicació o servei web.
   - Ús de l’extensió del navegador per emplenar automàticament.

4. **Gestió de Còpies de Seguretat (Backup)**
   - Com fer una còpia de seguretat de la base de dades.
   - Recomanacions per emmagatzemar la còpia de forma segura (USB xifrada, núvol xifrat).

---

## Notes finals

- La Fase 1 és un informe per a la direcció que justifica la decisió.
- La Fase 2 és un manual per als tècnics que els ajuda a usar l’eina escollida.
- Si tens dubtes sobre algun punt, pots demanar ajuda per aclarir-los.







