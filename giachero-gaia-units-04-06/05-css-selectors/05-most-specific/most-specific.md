# __SPECIFICITY__

## 1️⃣ ul li {}
**Specificity -> (0, 0, 2)**  
Questo selettore contiene solo due elementi HTML, ul e li. Non ci sono classi né ID, quindi conta solo come due elementi.    

## 2️⃣ ul > li {}
**Specificity -> (0, 0, 2)**  
È uguale al precedente perché il simbolo > non influisce sulla specificità. Vengono contati solo i due elementi.  

## 3️⃣ body > #main.mobile a:hover {}
**Specificity -> (1, 2, 2)**  
Qui c’è un ID, una classe e una pseudo-classe, oltre a due elementi. La presenza dell’ID lo rende molto forte.  

## 4️⃣ div p > span {}
**Specificity -> (0, 0, 3)**  
Il selettore contiene tre elementi HTML. Non ha classi né ID, quindi il peso è dato solo dai tag.  

## 5️⃣ .users .name {}
**Specificity -> (0, 2, 0)**  
Sono presenti due classi. Non ci sono elementi o ID che aumentano ulteriormente il peso.  

## 6️⃣ [href$='.pdf'] {}
**Specificity -> (0, 1, 0)**  
È un selettore di attributo, che vale come una classe. Non sono presenti né ID né elementi aggiuntivi.  

## 7️⃣ :hover {}
**Specificity -> (0, 1, 0)**  
La pseudo-classe :hover conta come una classe. Non sono coinvolti ID o elementi.  

## 8️⃣ div .name {}
**Specificity -> (0, 1, 1)**   
Qui troviamo un elemento (div) e una classe (.name). Non ci sono ID.  

## 9️⃣ a[href$='.pdf'] {}
**Specificity -> (0, 1, 1)**  
Il selettore include un elemento (a) e un attributo. L’attributo vale come una classe.  

## 1️⃣0️⃣ .pictures img:hover {}
**Specificity -> (0, 2, 1)**  
Sono presenti una classe e una pseudo-classe, più un elemento. Non ci sono ID.  

## 1️⃣1️⃣ .news.breaking.featured {}
**Specificity -> (0, 3, 0)**  
Ci sono tre classi nello stesso selettore. Questo lo rende più forte di selettori con una o due classi.  

## 1️⃣2️⃣ .user #name {}
**Specificity -> (1, 1, 0)**  
Il selettore contiene un ID e una classe. La presenza dell’ID aumenta molto la specificità.  

## 1️⃣3️⃣ #name span {}
**Specificity -> (1, 0, 1)**  
Qui troviamo un ID e un elemento. È più forte di qualsiasi selettore senza ID.  

## 1️⃣4️⃣ nav#nav > li:hover {}
**Specificity -> (1, 1, 2)**  
Contiene un ID, una pseudo-classe e due elementi. È un selettore molto specifico.  

## 1️⃣5️⃣ li:nth-child(2n+1):hover {}
**Specificity -> (0, 2, 1)**  
Sono presenti due pseudo-classi e un elemento. Non avendo ID, è meno forte dei selettori che li contengono.