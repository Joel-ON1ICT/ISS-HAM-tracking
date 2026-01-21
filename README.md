![Created with Gemini](https://img.shields.io/badge/Created%20with-Google%20Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![Status](https://img.shields.io/badge/Status-Hobby%20Project-orange?style=for-the-badge)

# 🛰️ ISS HAM Control Center - Ultimate Edition

[🇳🇱 Nederlands](#-nederlands) | [🇬🇧 English](#-english) | [🇫🇷 Français](#-français) | [🇪🇸 Español](#-español) | [⚖️ License](#%EF%B8%8F-license)

---

## 🇳🇱 Nederlands

**ISS HAM Control Center** is een geavanceerde, web-based tool voor radioamateurs om het International Space Station (ISS) te volgen en real-time Doppler-correcties te berekenen voor satellietcommunicatie.

### 🚀 Functies
* **Real-time Tracking:** Live positie van het ISS op de kaart.
* **Doppler Correctie:** Berekent automatisch de RX (ontvangst) en TX (zend) frequenties op basis van je locatie.
* **Crossband Repeater Assistent:** Geeft aan welk geheugen-kanaal (ISS 1 t/m 5) je moet gebruiken op je radio.
* **Passage Voorspelling:** Berekent de volgende 5, 10, 15 of 20 passages voor jouw locatie (instelbaar).
* **AOS Alarm:** Speelt een dubbel "Ding-Dong" signaal af wanneer het ISS boven de horizon komt.
* **Geheugen:** Onthoudt automatisch je laatst gekozen locatie.

### 📻 De Zender Programmeren
Om via het ISS te werken, moet je rekening houden met het Doppler-effect. We programmeren geheugenkanalen voor de Crossband Repeater (ISS 1-5) en voor directe spraak (ISS 7).

**Algemene Instellingen:**
* **Mode:** FM (Narrow/Small indien beschikbaar)
* **Stapgrootte (Step):** 5 kHz

#### A. Crossband Repeater (Veelgebruikt)
*Het ISS ontvangt op 70cm (UHF) en zendt op 2m (VHF). Omdat de Doppler-verschuiving op 70cm groot is, gebruiken we 5 kanalen.*

| Kanaal Naam | Tijdstip | Ontvangst (RX) | Zenden (TX) | Tone (CTCSS) |
| :--- | :--- | :--- | :--- | :--- |
| **ISS 1 (AOS)** | Start passage (Opkomst) | **437.810 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 2** | Tussenin | **437.805 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 3 (MID)** | ISS recht boven je (TCA) | **437.800 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 4** | Tussenin | **437.795 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 5 (LOS)** | Einde passage (Ondergang) | **437.790 MHz** | 145.990 MHz | 67.0 Hz |

#### B. VHF Spraak (ISS 7)
*Gebruikt voor schoolcontacten en bemande gesprekken. Soms aangeduid als "ISS 7".*

| Kanaal Naam | Regio | Ontvangst (RX) | Zenden (TX) | Tone |
| :--- | :--- | :--- | :--- | :--- |
| **ISS 7 (EU/AF)** | Regio 1 (Europa/Afrika) | **145.800 MHz** | 145.200 MHz | -- |
| **ISS 7 (AM/AS)** | Regio 2&3 (Amerika/Azië) | **145.800 MHz** | 144.490 MHz | -- |

### 💻 Installatie
1.  Download het bestand `index.html`.
2.  Open het bestand in een moderne browser (Chrome, Edge, Firefox, Safari).
3.  Geen server of installatie nodig!

---

## 🇬🇧 English

**ISS HAM Control Center** is an advanced, web-based tool designed for Ham Radio operators to track the International Space Station (ISS) and calculate real-time Doppler shifts for satellite communication.

### 🚀 Features
* **Real-time Tracking:** Live position of the ISS on the map.
* **Doppler Correction:** Automatically calculates RX (receive) and TX (transmit) frequencies based on your location.
* **Crossband Repeater Assistant:** Indicates which memory channel (ISS 1 to 5) to select on your radio.
* **Pass Prediction:** Calculates the next 5, 10, 15, or 20 passes for your specific location.
* **AOS Alarm:** Plays a double "Ding-Dong" chime when the ISS rises above the horizon.
* **Memory:** Automatically remembers your last selected location.

### 📻 Programming Your Radio
To work the ISS, you must account for the Doppler effect. We program memory channels for the Crossband Repeater (ISS 1-5) and direct voice contacts (ISS 7).

**General Settings:**
* **Mode:** FM (Narrow if available)
* **Step:** 5 kHz

#### A. Crossband Repeater (Most common)
*The ISS receives on 70cm (UHF) and transmits on 2m (VHF). Since UHF Doppler shift is significant, we use 5 split channels.*

| Channel Name | Timing | Receive (RX) | Transmit (TX) | Tone (CTCSS) |
| :--- | :--- | :--- | :--- | :--- |
| **ISS 1 (AOS)** | Start of pass (Acquisition) | **437.810 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 2** | Approaching | **437.805 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 3 (MID)** | Overhead (Center freq) | **437.800 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 4** | Departing | **437.795 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 5 (LOS)** | End of pass (Loss) | **437.790 MHz** | 145.990 MHz | 67.0 Hz |

#### B. VHF Voice (ISS 7)
*Used for scheduled school contacts and crew chats. Often called "ISS 7".*

| Channel Name | Region | Receive (RX) | Transmit (TX) | Tone |
| :--- | :--- | :--- | :--- | :--- |
| **ISS 7 (EU/AF)** | Region 1 (Europe/Africa) | **145.800 MHz** | 145.200 MHz | -- |
| **ISS 7 (AM/AS)** | Region 2&3 (USA/Asia) | **145.800 MHz** | 144.490 MHz | -- |

### 💻 Installation
1.  Download the `index.html` file.
2.  Open the file in any modern web browser.
3.  No server or installation required!

---

## 🇫🇷 Français

**ISS HAM Control Center** est un outil web avancé conçu pour les radioamateurs afin de suivre la Station Spatiale Internationale (ISS) et de calculer le décalage Doppler en temps réel.

### 🚀 Fonctionnalités
* **Suivi en temps réel :** Position en direct de l'ISS sur la carte.
* **Correction Doppler :** Calcule automatiquement les fréquences RX (réception) et TX (émission).
* **Assistant Répéteur Crossband :** Indique quel canal mémoire (ISS 1 à 5) utiliser sur votre radio.
* **Prédiction de passage :** Calcule les 5, 10, 15 ou 20 prochains passages pour votre position.
* **Alarme AOS :** Joue un double "Ding-Dong" lors de l'apparition de l'ISS.
* **Mémoire :** Mémorise automatiquement votre dernière localisation.

### 📻 Programmer votre Radio
Pour contacter l'ISS, il faut compenser l'effet Doppler. Nous programmons des canaux pour le répéteur (ISS 1-5) et pour la voix directe (ISS 7).

**Réglages Généraux :**
* **Mode :** FM (Narrow si disponible)
* **Pas (Step) :** 5 kHz

#### A. Répéteur Crossband (Le plus courant)
*L'ISS reçoit sur 70cm (UHF) et émet sur 2m (VHF).*

| Nom du Canal | Moment | Réception (RX) | Émission (TX) | Tone (CTCSS) |
| :--- | :--- | :--- | :--- | :--- |
| **ISS 1 (AOS)** | Début de passage | **437.810 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 2** | Approche | **437.805 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 3 (MID)** | Au-dessus (Zénith) | **437.800 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 4** | Éloignement | **437.795 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 5 (LOS)** | Fin de passage | **437.790 MHz** | 145.990 MHz | 67.0 Hz |

#### B. VHF Voix (ISS 7)
*Utilisé pour les contacts écoles. Souvent appelé "ISS 7".*

| Nom du Canal | Région | Réception (RX) | Émission (TX) | Tone |
| :--- | :--- | :--- | :--- | :--- |
| **ISS 7 (EU/AF)** | Région 1 (Europe/Afrique) | **145.800 MHz** | 145.200 MHz | -- |
| **ISS 7 (AM/AS)** | Région 2&3 (USA/Asie) | **145.800 MHz** | 144.490 MHz | -- |

### 💻 Installation
1.  Téléchargez le fichier `index.html`.
2.  Ouvrez-le dans votre navigateur web.
3.  Aucune installation nécessaire !

---

## 🇪🇸 Español

**ISS HAM Control Center** es una herramienta web avanzada para radioaficionados que permite rastrear la Estación Espacial Internacional (ISS) y calcular el desplazamiento Doppler en tiempo real.

### 🚀 Características
* **Rastreo en tiempo real:** Posición en vivo de la ISS en el mapa.
* **Corrección Doppler:** Calcula automáticamente las frecuencias de RX (recepción) y TX (transmisión).
* **Asistente de Repetidor de Banda Cruzada:** Indica qué canal de memoria (ISS 1 a 5) usar en su radio.
* **Predicción de Pasos:** Calcula los próximos 5, 10, 15 o 20 pasos.
* **Alarma AOS:** Reproduce un doble sonido "Ding-Dong" cuando la ISS aparece en el horizonte.
* **Memoria:** Recuerda automáticamente su última ubicación.

### 📻 Programación de la Radio
Para trabajar con la ISS, debe tener en cuenta el efecto Doppler. Programamos canales para el repetidor (ISS 1-5) y para voz directa (ISS 7).

**Configuración General:**
* **Modo:** FM (Narrow si está disponible)
* **Paso (Step):** 5 kHz

#### A. Repetidor Crossband (Más común)
*La ISS recibe en 70cm (UHF) y transmite en 2m (VHF).*

| Nombre Canal | Momento | Recepción (RX) | Transmisión (TX) | Tono (CTCSS) |
| :--- | :--- | :--- | :--- | :--- |
| **ISS 1 (AOS)** | Inicio del paso | **437.810 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 2** | Acercándose | **437.805 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 3 (MID)** | Encima (Cénit) | **437.800 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 4** | Alejándose | **437.795 MHz** | 145.990 MHz | 67.0 Hz |
| **ISS 5 (LOS)** | Fin del paso | **437.790 MHz** | 145.990 MHz | 67.0 Hz |

#### B. VHF Voz (ISS 7)
*Usado para contactos escolares. A menudo llamado "ISS 7".*

| Nombre Canal | Región | Recepción (RX) | Transmisión (TX) | Tono |
| :--- | :--- | :--- | :--- | :--- |
| **ISS 7 (EU/AF)** | Región 1 (Europa/África) | **145.800 MHz** | 145.200 MHz | -- |
| **ISS 7 (AM/AS)** | Región 2&3 (USA/Asia) | **145.800 MHz** | 144.490 MHz | -- |

### 💻 Instalación
1.  Descargue el archivo `index.html`.
2.  Ábralo en su navegador web.
3.  ¡No requiere instalación!

---

*Disclaimer: This project is for educational and hobby purposes only. Do not use for critical operations.*

*Powered by [Leaflet.js](https://leafletjs.com/) & [Satellite.js](https://github.com/shashwatak/satellite-js).*# ISS-HAM-tracking
This tool is designed for HAM radio operators and space enthusiasts. It calculates real-time Doppler shifts for uplink/downlink frequencies, predicts upcoming passes based on your specific location, and visualizes the ISS orbit with high precision.
