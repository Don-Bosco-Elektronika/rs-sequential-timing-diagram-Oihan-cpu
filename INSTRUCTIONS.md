# 🛠️ Cronograma de Circuitos Secuenciales / Zirkuitu Sekuentzialen Kronograma / Sequential Circuit Timing Diagram

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |

---

## 📌 Ejercicio / Ariketa / Exercice


**Ariketa (EU): (ZENBAKIA IDATZI)**  
1 ----> Izena        
2 ----> Txip Zenbakia    
3 ----> Sinboloa        
4 ----> Funtzionamenduaren Describapena       



1---->  RS     
 
2----> CD4044 
 
3 ----> 

<img width="111" height="116" alt="Captura de pantalla 2026-01-20 125815" src="https://github.com/user-attachments/assets/4722852c-5224-4fe7-9cfd-1e717231de55" />

 
4 ---->4044 txipa 4 biteko latch erregistroa da. Lau seinale digital (0 edo 1) gordetzeko balio du, eta egoera hori mantentzen du aldatzeko agindua jaso arte.

🔹 Adibide laburra:
4 botoi 4044 txipera konektatzen dituzu. “Gorde” botoia sakatzean, txipak botoien egoera gordetzen du eta 4 LED piztuta edo itzalita mantentzen ditu, botoiak askatu arren.|





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
1. ARIKETA

{signal: [

{name: 'Set', wave: 'l..hl.h.l.h.lhl.h'},

{name: 'Reset', wave: 'lh.l.hl.hlh..l..h'},
{},

{name: 'Q', wave: '0..1.0.1.0.1.X'},

{name: '-Q', wave: '1..0.1.0.1.0.X'}

]}

2.ARIKETA

{signal: [

 {name: 'clk', wave: 'P................'},
  
 {name: 'Set', wave: '0101.0...1.0..1.0'},
  
 {name: 'Reset', wave: '1...0.1..0....101'},
  
 {},
  
 {name: 'Q', wave: '01...0...1....0.1'},
  
 {name: '-Q', wave: '10...1...0....1.0'}
 
]}

3.ARIKETA

{signal: [

{name: 'clk', wave: 'n................'},

{name: 'Set', wave: '0..1010.1..01010.'},

{name: 'Reset', wave: '1...0..1.0..1..01'},

{},

{name: 'Q', wave: '0......X.01..X.0.'},

{name: '-Q', wave: '1......X.10..X.1'}

]}

4.ARIKETA

{signal: [

{name: 'clk', period:2, wave: 'p................'},

{name: 'Set', wave: '010.....1..0..1.0'},

{name: 'Reset', wave: '1...0..1.0..1..01'},

{},

{name: 'Q', wave: '0.1...........0.1..'},

{name: '-Q', wave: '1.0..........1.0..'}

]}

5.ARIKETA

{signal: [
{name: 'clk', wave: 'n................'},

{name: 'Set', wave: '0..1010.1..01010.'},

{name: 'Reset', wave: '1...0..1.0..1..01'},

{},

{name: 'Q', wave: '0..1.x1...0x10.1'},

{name: '-Q', wave: '1..0.x0...1x01.0'}

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



