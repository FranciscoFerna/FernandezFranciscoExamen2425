# Examen - RA6: Creació i Gestió d'un Projecte Web amb Git i Desplegament en Vercel

## 1. Configuració inicial
1. Comprova la versió instal·lada de Git i fes captura del terminal.  
   **Captura:** ![Logo](git-version.png)

2. Configura Git al teu sistema (nom i email). Mostra la configuració actual per verificar-ho.  
   **Captura:** ![Logo](git-config.png)

3. Inicia un nou repositori Git al directori `Cognom1Cognom2Examen2425`. Fes el primer commit.  
   **Captura:** ![Logo](mkdir-git.png)
   ![Logo](git-commit.png)

---

## 2. Creació del projecte web
1. Crea els fitxers següents al directori del projecte:  
   - `index.html`  
   - `testunitari.html`  
   - `style.css`  
   - `main.js`  
   Afegeix contingut bàsic a cada fitxer.
   ![Logo](testunitari-html.png)
   ![Logo](styles-css.png)
   ![Logo](main-js.png)

2. Verifica l’estat del repositori després d’afegir els fitxers.  
   **Captura:** ![Logo](git-status.png)

3. Elimina `testunitari.html` del staging i fes un commit amb el missatge **"2 - Estructura bàsica"**.  
   **Captura:** ![Logo](git-restore.png)
   ![Logo](git-commit.png)

4. Consulta l’historial de commits.  
   **Captura:** ![Logo](git-log.png)

---

## 3. Creació de branques i documentació
1. Crea una branca nova anomenada `documentacio`.  
   **Captura:** ![Logo](git-branch-doc.png)

2. Torna a la branca `main` i fes un merge amb la branca `documentacio`.  
   **Captura:** ![Logo](git-checkout.png)

---

## 4. Remot i publicació
1. Configura un repositori remot a GitHub amb el nom `Cognom1Cognom2Examen2425`.  
   **Captura:** ![Logo](git-create-repo.png)

2. Puja els canvis al repositori remot.  
   **Captura:** `captures/git-push.png`

3. Publica el projecte a Vercel i copia l’enllaç generat.  
   **Enllaç de la pàgina publicada:** [Pàgina publicada](https://fernandez-francisco-examen2425.vercel.app/)  
   **Captura:** ![Logo](vercel-published-1.png)

---

## 5. Verificació final
1. Penja totes les captures i aquest document a la branca `documentacio`.  
2. Comprova que tots els commits i fitxers estan al repositori remot.  
   **Captura:** ![Logo](published-1.png)
   ![Logo](published-2.png)

---

## Estructura del projecte
El directori hauria de contenir:  
- Fitxers del projecte (`index.html`, `style.css`, `main.js`)  
- Fitxer `README.md` completat.  
- Carpeta `captures/` amb les captures corresponents.

