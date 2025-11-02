# Diagnosi Avançada amb DIG i NSLOOKUP
### Linux / macOS  MARC JURADO 2N SMX

---

## Descripció del Projecte
Pràctica de diagnosi avançada de DNS utilitzant les eines DIG i NSLOOKUP per analitzar registres, servidors de noms, consultes autoritatives i mes

---
## Introduccio i coses a saber abans de començar
![Consulta bàsica A](./img/captura99.png)

![Consulta bàsica A](./img/captura98.png)

#### Que em de fer:
principalment per començar hem de fer un apt update per actualitzar i seguidament instalar el dig en aquest cas dnsutils -y I JA PODEM COMENÇAR

---

## A. Diagnosi Avançada amb DIG

### Consulta Bàsica de Registre A

#### Captura:
![Consulta bàsica A](./img/captura100.png)

#### Anàlisi:

#### Explicació
xtec.cat és el domini que es consulta.  
El tipus de registre és A, que retorna la seva adreça IP que ens dona.

#### 🧠 Has d’identificar:
- **IP de resposta:** 83.247.151.214  
- **TTL:** 3600 segons  és el temps que el registre es guarda en memòria cau.  
- **Servidor que ha respost:** el que surt després de SERVER, en aquest cas 8.8.8.8.


---

### Consulta de Servidors de Noms (NS)

#### Captura:
![Consulta NS tecnocampus](./img/captura101.png)
![Consulta NS tecnocampus](./img/captura101,5.png)
#### Anàlisi:
_(Escriu aquí la teva anàlisi sobre quins són els servidors de noms autoritatius del domini.)_

---

### Consulta Detallada SOA

#### Captura:
![Consulta SOA escolapia](./img/captura102.png)

#### Anàlisi:
_(Escriu aquí la teva anàlisi sobre la informació del correu de l’administrador i el número de sèrie del domini.)_

---

### Consulta de Resolució Inversa

#### Captura:
![Consulta inversa](./img/captura103.png)
![Consulta inversa](./img/captura103.5.png)

#### Anàlisi:
_(Escriu aquí la teva anàlisi sobre la informació obtinguda dels registres inversos.)_

---

## Comprovació de Resolució amb NSLOOKUP

L’eina **NSLOOKUP** permet fer consultes DNS tant en mode directe com interactiu, i és multiplataforma.

---

### Consulta Bàsica no Autoritativa

#### Captura:
![Consulta bàsica no autoritativa](./img/captura104.png)

![Consulta bàsica no autoritativa](./img/captura104.5.png)
#### Anàlisi:
_(Escriu aquí la teva anàlisi sobre per què la resposta és no autoritativa.)_

---

### Consultes Autoritatives

#### Captura:
![Consulta autoritativa](./img/captura105.png)

![Consulta autoritativa](./img/captura105.5.png)

![Consulta autoritativa](./img/captura105.6.png)

![Consulta autoritativa](./img/captura105.7.png)
#### Anàlisi:
_(Escriu aquí la teva anàlisi sobre les diferències observades respecte a la consulta no autoritativa.)_

---
### Resolucions locals

![Consulta autoritativa](./img/captura105.5.png)

Farem un ping al server, aixo permet comprovar el funcionament útil per entorns de xarxa local on no es disposa de servidor de noms propi i que evita haver d’accedir a equips o recursos per la seva IP.

