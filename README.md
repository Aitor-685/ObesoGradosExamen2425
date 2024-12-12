#1. Configuració inicial
	1.1 Comprova la versió instal·lada de Git, fes captura del terminal.
	Use el comando git --version para comprobar la version del git

	1.2 Mostra la configuració actual per verificar-ho, fes captura del terminal. Explica com veig que he configurat correctament el email i el nom.
	Use el comando git config --global user.email y git config --global user.name para comprobar la configuracion y la muestra que lo he configurado bien sera que el repositorio local 
	se pueda conectar con el repositorio remoto

	1.3 Inicia un nou repositori Git al directori de treball on consideris. El nom del directorio ha de ser Cognom1Cognom2Examen2425.
	Use el comando mkdir Cognom1Cognom2Examen2425 y despues el git init para iniciarlo 

	1.4 Crea un document README.md, afegeix el document i fes un primer commit que amb el missatge 1 - Git init
	Use el comando touch README.md, lo añadi con el git add README.md y despues hice el git commit -m "1 - Git init"

#2. Creació del projecte web
	2.1 Crea els fitxers següents al directori del projecte:
	Use el comando mkdir projecte-web y despues dentro de la carpeta cree los archivos con el comando touch index.htmly los demas 
	
	2.2 Afegeix contingut bàsic a cada fitxer.
	Use el comando nano para meterle contenido a los archivos 
	
#### **Examen - RA6: Creació i Gestió d'un Projecte Web amb Git i Desplegament en Vercel**

#### **Durada máxima**: 1 hora i 30 minuts

---

### **Objectiu**  
Crear un projecte web amb documents HTML, CSS i JavaScript. 
Gestionar amb Git, utilitzar branques i publicar un projecte.

---

### **Documentació**  
Has de crear un document en format **Markdown** amb les imatges i l'explicació necessària que es demana a l'examen.  

En acabar l'últim pas de l'examen, hauràs de penjar aquest document a la branca de **documentació**, incloent-hi les fotografies corresponents.

---

### **Instruccions**

#### **1. Configuració inicial**

1. Comprova la versió instal·lada de Git, fes captura del terminal.

2. Configura Git al teu sistema (opcional)

3. Mostra la configuració actual per verificar-ho, fes captura del terminal. Explica com veig que he configurat correctament el email i el nom.

5. Inicia un nou repositori Git al directori de treball on consideris. El nom del directorio ha de ser `Cognom1Cognom2Examen2425`.

6. Crea un document README.md, afegeix el document i fes un primer commit que amb el missatge `1 - Git init`
---

#### **2. Creació del projecte web**

1. **Crea els fitxers següents al directori del projecte:**  
   - `index.html`
   - `testunitari.html`
   - `style.css`  
   - `main.js`  

2. Afegeix contingut bàsic a cada fitxer.

---

#### **3. Gestió amb Git**

1. **Afegir fitxers:**  
   - Utilize el comando git add *.html *.css  
   
2. **Verifica l'estat del repositori, fes captura del terminal** 
   - Utilize el comando git status

3. **Elimina `testunitari.html` del staging**
   - Utilize el comando git reset testunitari.htm

4. **Fes un commit que amb el missatge '2- Estructura bàsica'**  
   - Utilize el comando git commit -m "2 - Estructura bàsica"
 
5. **Consulta l'historial de commits, fes captura del terminal.**  
   - Utilize el comando git log --oneline
---

#### **4. Creació de branques i documentació**

1. **Crea una nova branca per a la documentació** 
   - Utilize el comando git commit -m "2 - Estructura bàsica"

2. **Crea un fitxer `README.md` si es necessari:**  
   - Explica dins del fitxer el propòsit del projecte.  

3. **Afegeix i fes commit dels canvis a la branca `documentacio`.**
El missatge del commit ha de ser "3 - README.md amb documentació inicial"
   - Utilize el comando git commit -m "2 - Estructura bàsica"

4. **Torna a la branca principal (`main`) i fes un merge** 
   - Utilize el comando git commit -m "2 - Estructura bàsica"
---

#### **5. Remot i publicació**

1. Configura un remot per al repositori que has de crear en GitHub, el nom del repositorio de GitHub ha de ser `Cognom1Cognom2Examen2425`. Fes captura al terminal de com has configurat el repositori remot.

2. **Puja els canvis al remot desde terminal**.Fes captura al terminal.

4. **Publica el projecte a Vercel i indica l'enllaç en el document Markdown del examen.**

# Projecte Web

Aquest és el projecte web per a la creació d'un sistema de documentació amb un entorn bàsic de desenvolupament utilitzant Git.

## Propòsit

L'objectiu d'aquest projecte és proporcionar una estructura bàsica per al desenvolupament web, incloent HTML, CSS, i JavaScript, així com la seva gestió amb Git.

## Contingut

1. **HTML**: Pàgines bàsiques amb estructura.
2. **CSS**: Full d'estils per a la presentació visual.
3. **JavaScript**: Funcionalitats per a la interactivitat.
4. **Git**: Gestió del codi font amb Git i control de versions.

Aquest projecte és ideal per als usuaris que volen aprendre com gestionar un projecte web amb Git i controlar els canvis de manera eficient.

