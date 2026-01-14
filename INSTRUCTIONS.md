# 🛠️ Cronograma de Circuitos Secuenciales / Zirkuitu Sekuentzialen Kronograma / Sequential Circuit Timing Diagram

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |

---

## 📌 Ejercicio / Ariketa / Exercice


**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena        | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                
 |  RS     |CD4044|<img width="228" height="178" alt="Captura de pantalla 2026-01-14 121814" src="https://github.com/user-attachments/assets/fb6b403f-092d-460f-a441-25ded6456052" />
|CD4044 txipa lau RS flip-flop independiente ditu, bakoitzak bit bat gordetzen du, eta bere irteera Set eta Reset sarreraren arabera aldatzen da.|





## Tabla de la verdad

| Entrada A | Entrada B | Entrada C | Salida    | Salida |
|-----------|-----------|-----------|-----------|--------|
| 0         | 0         | 0         | ░0░       | ░0░    |
| 0         | 0         | 1         | ░1░       | ░1░    |
| 1         | 1         | 0         | ░1░       | ░1░    |
| 1         | 1         | 1         | ░0░       | ░0░    |

----

## 🔲 Circuitos a Simular / Simulatzeko Zirkuituak / Circuits to Simulate

<img width="779" height="444" alt="Captura de pantalla 2026-01-14 122608" src="https://github.com/user-attachments/assets/713e419c-50bb-4a8e-b233-c8af388fb5f5" />




---

## 🔲 Resultado del Cronograma / Kronogramaren Emaitza / Timing Diagram Result
Circuito A

<img width="1033" height="580" alt="5  Ariketa" src="https://github.com/user-attachments/assets/730d1b85-6d38-4d82-9f1f-337ce6eb2051" />
<img width="1353" height="568" alt="4 Ariketa" src="https://github.com/user-attachments/assets/1f4215ef-a1a9-4daa-bb87-052ea01ef222" />
<img width="872" height="546" alt="3 Ariketa" src="https://github.com/user-attachments/assets/d8a74f77-1369-428e-98ab-a60808d89fb8" />
<img width="985" height="521" alt="2 Ariketa" src="https://github.com/user-attachments/assets/4f778af2-61e3-4cd4-8f44-515f7c282eca" />
<img width="830" height="535" alt="1  Ariketa" src="https://github.com/user-attachments/assets/806c3c90-26fc-427d-b9bc-f7aed6e832f2" />


---


## 🔲 Código del Cronograma / Kronogramaren Kodea / Timing Diagram Code
1. Ariketa

   
   {signal: [
{name: 'Set', wave: 'hl.h.lhl.h...l..h'},

{name: 'Reset', wave: 'l.h.l.h.lhlhl..h.'},

{},

{name: 'Q', wave: '0..1.0.1.0.1.x'},

{name: '-Q', wave: '1..0.1.0.1.0.x'}
]}

   

## 📤 Entrega / Igo / Upload  

➡️ **Instrucciones:**  

- **ES:** Sube los siguientes archivos. Todos los archivos subidos han de tener tu nombre.  
  - Una foto del símbolo.  
  - El archivo en Proteus y una captura de imagen de cada circuito en Proteus.  
  - Capturas de cada resultado del Wavedrom (solo el gráfico).  
  - **ATENCIÓN:** El código del cronograma TIENE que ser código, no una imagen.

- **EU:** Igo hurrengo fitxategiak. Igotako fitxategi guztiek zure izena eduki behar dute.  
  - Sinboloaren argazki bat.  
  - Proteus fitxategia eta zirkuitu bakoitzaren irudia (captura) Proteusen.  
  - Wavedrom bakoitzaren emaitzaren kaptura (grafikoa bakarrik).  
  - **KONTUZ:** Kronogramaren kodea kodea izan behar da, ez irudi bat.

- **EN:** Upload the following files. All uploaded files must include your name.  
  - A photo of the symbol.  
  - The Proteus file and an image capture of each circuit in Proteus.  
  - Uno capture of each Wavedrom result (graph only).  
  - **ATTENTION:** The schedule code MUST be real code, not an image.



