# Manual d'Ús de GitHub Copilot: Eina d'Intel·ligència Artificial per al Desenvolupament de Projectes de Codi en Informàtica i Ciberseguretat

## Les Aplicacions de la IA ![Github Copilot](https://gotrialpro.com/wp-content/uploads/edd/2024/08/GitHub-Copilot-Free-Trial.png)

**GitHub Copilot** és un assistent de programació impulsat per intel·ligència artificial, desenvolupat conjuntament per GitHub i OpenAI. Utilitza algoritmes avançats de processament del llenguatge natural per suggerir línies de codi i funcions senceres a mesura que l'usuari escriu, millorant l'eficiència i productivitat en el desenvolupament de programari.

### Característiques Principals

- **Autocompletat Intel·ligent**: Suggeriments en temps real de línies de codi basats en el context del projecte.
- **Generació de Funcions**: Pot generar funcions senceres a partir de comentaris o descripcions en llenguatge natural.
- **Suport a Múltiples Llenguatges**: Compatible amb una àmplia gamma de llenguatges de programació com Python, JavaScript, TypeScript, Ruby, Go, entre d'altres.
- **Integració amb Editors**: S'integra amb editors populars com Visual Studio Code, Neovim i JetBrains IDEs.
- **Aprenentatge Continu**: Millora els suggeriments a mesura que s'utilitza, adaptant-se al estil de codificació de l'usuari.
  ![](https://www.amitmerchant.com/images/copilot-chat-fix-error-code.png)
  
## Utilizacio de Copilot
***Per utilizar github copilor haurem de seguir el seguents pasos:***

### Configuracio Inicial
#### Asegurarte de tenir un compte a Github
- si encara no la tens ves a [Github](https://github.com/)
- Es necesari tenir un compte en Github amb una subscripcio activa per Github Copilot (individual o Empresarial)
#### Descaregar en editor compatible
Github Copilot funciona amb varis editors, els principals son:
- Visual Studio Code ([Descarga VSC](https://code.visualstudio.com/download))
- Neovim ([Descarga NV](https://sourceforge.net/projects/neovim.mirror/))
- JetBrains IDEs ([IntelliJ IDEA](https://www.jetbrains.com/idea/download/?section=linux), [PyCharm](https://www.jetbrains.com/pycharm/download/?section=linux) )
#### Instala la extenció de Github Copilot
- Obre el editor que estes utilizant.
- Ves al MarketPlace de Extensions.
- Busca "Github Copilot"
- Instala la extensió corresponen.
  
### Configuracio de Github Copilot
- Inicia sesio en la teva sessio de github.
#### Activa Github Copilot
- Ve a [Github Copilot Dashboard](https://github.com/features/copilot)
- Asegurat de tenir activa la subscripcio.
- Configura les teves preferencies si es necesari.

### Utilizació de Copilot
#### Escriu codi per rebre sugerencies
Github Copilor comença a oferir sugerencies automaticament mentres escrius codig.
##### Exemple:
- Abre en archivo en ru editor (ex: script.py para python)
- Escribe lo que quieres hacer:
```python
#funcion para calcular la suma de dos numeros
```
-Github Copilor et generara automaticament el codig corresponent:
```python
def suma(a, b):
  return a + b
```
#### Navega per les sugerencies
- si hi ha moltes sugerencies pots utiilzar:
    - Tab: Acepta la sugerencia actual
    - Ctrl + ] (Windows/Linux): veure la seguent opcio
    - Ctrl + [ (Windows/Linux): Veure la opcio anterior
      
### Personalizació de Copilot
#### Ajustar les preferencies 
- En VS Code, ves a ***settings*** i busca "Copilot"
- Configura opcions com:
    - Habilitar/Desabilitar en algus llenguatlles
    - Aceptar sugerencies automaticament o manualment
#### Limita el ambit de les sugerencies
si estas treballant en proyectes especifics, Copilot pot ajustarse per tal de oferir nomes sugerencies relevants.

Per a més informació sobre les funcionalitats de GitHub Copilot, visita el seu [lloc web oficial](https://copilot.github.com/).

## Impacte al Sector

L'arribada de GitHub Copilot ha tingut un impacte significatiu en el sector del desenvolupament de programari i la ciberseguretat.

### Beneficis Clau per al Sector

- **Augment de la Productivitat**: Redueix el temps necessari per escriure codi, permetent als desenvolupadors centrar-se en aspectes més complexos del projecte.
- **Facilitació de l'Aprenentatge**: Ajuda als nous programadors a aprendre patrons de codi i bones pràctiques a través de suggeriments.
- **Detecció de Vulnerabilitats**: Pot ajudar a identificar possibles vulnerabilitats en el codi suggerint millors pràctiques de seguretat.
- **Estàndards de Codificació**: Promou la consistència en l'estil de codi dins d'un equip o projecte.
- **Innovació**: Allibera temps dels desenvolupadors per centrar-se en la innovació i resolució de problemes complexos.

### Reptes i Consideracions

- **Seguretat del Codi**: Hi ha preocupacions sobre la possibilitat que Copilot suggereixi codi amb vulnerabilitats o codi propietari filtrat.
- **Dependència Excessiva**: Els desenvolupadors poden arribar a confiar massa en l'eina, afectant la seva capacitat per escriure codi de qualitat de manera independent.
- **Privacitat i Compliment Normatiu**: L'ús de dades de codi públic per entrenar l'eina planteja qüestions sobre drets d'autor i privacitat.

## Impacte Ambiental
![logo reciclaje](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQdh_TJZHNw5juE-RbMJnV9Ab9XEdRuzKaIIg&s)

L'ús de GitHub Copilot també té implicacions ambientals que cal considerar.

### Factors d'Impacte

- **Consum Energètic dels Servidors**: El model de llenguatge darrere de Copilot, OpenAI Codex, requereix una gran potència de computació per processar les peticions dels usuaris, contribuint al consum energètic.
- **Entrenament de Models de IA**: L'entrenament inicial i actualitzacions del model consumeixen una quantitat significativa d'energia, ja que requereixen recursos computacionals intensius.
- **Emissions de Carboni Associades**: Si l'energia utilitzada prové de fonts no renovables, això augmenta l'empremta de carboni.

Un estudi publicat per [MIT Technology Review](https://www.technologyreview.com/2019/06/06/239031/training-a-single-ai-model-can-emit-as-much-carbon-as-five-cars-in-their-lifetimes/) assenyala que l'entrenament de grans models de IA pot emetre tantes emissions de carboni com cinc cotxes al llarg de la seva vida útil.

## Propostes per Minimitzar els Impactes Ambientals

Per reduir l'impacte ambiental associat a l'ús de GitHub Copilot, es poden prendre les següents mesures:

### Estratègies per a una IA Sostenible

1. **Optimització de l'Ús**: Utilitzar l'eina de manera eficient, evitant peticions innecessàries que puguin augmentar la càrrega dels servidors.

2. **Pressió per a Pràctiques Sostenibles**: Com a usuaris, podem encoratjar GitHub i OpenAI a utilitzar centres de dades alimentats per energies renovables i a optimitzar l'eficiència dels seus models.

3. **Suport a la Investigació en IA Verda**: Promoure i donar suport a iniciatives que busquen desenvolupar models de IA més eficients energèticament.

4. **Educació i Sensibilització**: Formar els desenvolupadors sobre l'impacte ambiental de les seves eines i fomentar pràctiques de programació sostenibles.

5. **Col·laboració amb Proveïdors Sostenibles**: Triar serveis i proveïdors que estiguin compromesos amb la sostenibilitat ambiental.

### Recursos Addicionals

- **OpenAI's Environmental Initiatives**: Informació sobre els esforços d'OpenAI per reduir l'impacte ambiental. (Visita el [lloc web d'OpenAI](https://openai.com/) per a més detalls.)
- **Article sobre IA Sostenible**: [Towards Sustainable AI](https://arxiv.org/abs/1907.05417) (arXiv)

## Conclusions

GitHub Copilot representa un avanç significatiu en com la intel·ligència artificial pot assistir els desenvolupadors de programari, millorant la productivitat i potenciant el desenvolupament de projectes en informàtica i ciberseguretat. No obstant això, és important abordar els reptes associats, incloent-hi les preocupacions de seguretat, ètica i l'impacte ambiental. Mitjançant pràctiques responsables i un compromís amb la sostenibilitat, és possible aprofitar els avantatges de Copilot tot minimitzant els efectes adversos.

---

*Aquest manual està disponible al nostre [repositori de GitHub](https://github.com/nomdelusuari/nomdelrepositori) per a més detalls i actualitzacions.*
