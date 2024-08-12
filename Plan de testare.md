# itgalaxy

**Test Plan:              IT Galaxy**
</br><br>
**Proiect:             Jira Functional Testing**
</br><br>
**Versiunea:                  1. 01**
</br><br>
**Data:                14.08.2024**
</br><br>
**Autor:              Danea Vasile Sebastian**
</br><br>

Test Plan ....................................................
<br></br>
<br>1. Introducere............................................</br>
<br>1.1.Scopul................................................</br>
<br>1.2. Functionalitati in Scop..............................</br>
<br>1.3. Functionalitati in afara scopului....................</br>
<br>2. Procesul de testare....................................</br>
<br>2.1. Planificarea testarii................................</br>
<br>2.2. Analiza testarii.....................................</br>
<br>2.3. Designul de testare..................................</br>
<br>2.4. Implementarea testului...............................</br>
<br>2.5. Executarea testelor..................................</br>
<br>2.6. Concluzia testarii...................................</br>
<br>2.7. Monitorizarea testului si control....................</br>
<br>3. Livrabile de testare...................................</br>
<br>3.1. Test plan............................................</br>
<br>3.2. Conditii de testare..................................</br>
<br>3.3. Cazuri de testare....................................</br>
<br>3.4. Rapoarte zilnice.....................................</br>
<br>3.5. Matricea de trasabilitate............................</br>
<br>3.6. Rezultate test case-uri..............................</br>
<br>3.7. Raportari de bug-uri.................................</br>
<br>3.8. Raport de testare completa...........................</br>
   
**1. Introducere**
</br><br>
Obiectivul principal al acestui proiect JIRA este de a testa și valida în mod aprofundat funcționalitatea, utilizabilitatea și performanța magazinului online . Scopul este de a se asigura că pagina web si magazinul online itgalaxy aflat la: https://www.itgalaxy.ro/ îndeplinește cerințele definite, oferă o experiență de utilizare fără probleme și este lipsită de orice defecte sau probleme critice
</br><br>
##1.1. Scopul
</br><br>
Obiectivul principal al acestui proiect JIRA este de a testa și valida în mod aprofundat funcționalitatea, utilizabilitatea și performanța magazinului online
<br></br>
##1.2.Functionalitati in scop
<br>Domeniul de aplicare al acestui proiect JIRA poate fi ajustat în funcție de cerințele, prioritățile și constrângerile specifice ale proiectului</br>
<br>Se verifica faptul ca pot sa fie urmati pasii pentru a ajunge in diferitele parti care trebuiesc testate in ceea ce priveste modul in care utilizatorul foloseste site-ul</br>
<br></br>
Viteza de incarcare a site-ului este una buna si acesta se comporta potrivit pe laptop, dar pe telefonul mobil pot aparea anumite inconveniente din punct de vedere al aspectului 
</br><br>
**1.3.Functionalitati in afara scopului**
</br><br>
Proiectul se concentrează pe testarea aspectelor  funcționale ale magazinului online, care sunt completarea campurilor, trimiterea mesajelor, și modul in care utilizatorul poate sa vada informatiile din interfata in cadrul metodelor de livrare si verificare a produselor
</br><br>
Cerințele nefuncționale, cum ar fi performanța, securitatea și utilizabilitatea, ar fi considerate în afara domeniului de aplicare al acestui proiect specific.
</br><br>
##2. Procesul de testare
</br><br>
**2.1. Planificarea testarii**
<br></br>
<br>/Verificam sectiunea “Livrare” din pagina web "itgalaxy" daca aceasta contine informatiile utile necesare atat navigarii cat si orientarii in pagina, dar si din punct de vedere al informatiilor afisate pentru utilizatori</br>
<br>/Verificam sectiunea “support online” din pagina web "itgalaxy" in ceea ce priveste cazurile  de testare din cadrul epicului Livrare</br>
<br>/Se verifica  sectiunea “Modalitati livrare” din cadrul epicului “Livrare”</br>
<br>/Se verifica formularele din cadrul sectiunii de suport online care sunt structurate pe diferite departamente</br>

<br>Se fac verificari in diverse aspecte in instrumentul de gestionare Jira in ceea ce priveste aceasta sectiune si pagina avand epicul:</br>
![image](https://github.com/user-attachments/assets/02276e41-7c1b-4c43-b8e9-734b9f23c5e4)
<br></br>
/Se verifica daca pagina web afișează mesaje de eroare utile dacă utilizatorul introduce date nevalide în orice câmp al formularelor din pagina de suport online 
<br></br>
/Se verifica  dacă pagina web afișează mesaje de eroare utile dacă utilizatorul introduce date nevalide într-un camp evidentiat al formularului
<br></br>
/Testare in cadrul formularelor daca sunt afișate toate opțiunile valide
<br></br>
/Testarea faptului că utilizatorii nu pot trimite formulare pe pagina web fără a completa toate câmpurile
<br></br>
/Testam daca informatiile sunt vizibile in datele de contact ale formularelor
<br></br>
Testam daca formularul afișează mesaje de eroare clare dacă un câmp obligatoriu este lăsat necompletat
<br></br>
/Testam daca informatiile esentiale pot fi vizibile in mod corespunzator
<br></br>
##2.1.2.Identificarea cazurilor de testare
</br><br>
**Preconditii: utilizatorul nu trebuie sa fie neaparat logat pentru a utiliza facilitatile si resursele necesare care se incadreaza la procesele de testare
<br></br>
**Postcondiții:  fiecare camp sau informatie vizata din pagina trebuie sa fie vizibila in cazul acestui magazin online, iar completarea campurilor si trimiterea diverselor informatii ar trebui sa functioneze in mod corespunzator
<br></br>
Utilizam testarea manuala si folosim in cadrul acestui site tehnici de testare black box si testare functionala in ceea ce priveste vizibilitatea si completarea campurilor din cadrul departamentelor din sectiunea de suport online. Utilizam testarea acceptantei utilizatorului in cadrul formularelor de contact pentru a vedea daca sunt indeplinite criteriile in ceea ce priveste nevoile utilizatorilor si ghidarea acestora si validarea campurilor de completat din cadrul departamentelor de suport online si testarea exploratorie, fiind siguri ca aceste campuri functioneaza corect in anumite conditii.

<br>Se efectueza numerose task-uri pentru a evidentia procesul de testare:</br>

![image](https://github.com/user-attachments/assets/81071c9c-f8de-4222-a631-fe6254de8841)
<br></br>
![image](https://github.com/user-attachments/assets/94b657c3-2104-434d-bb59-d5dd6ea02ed1)
<br></br>
![image](https://github.com/user-attachments/assets/2e1f52de-bcc0-4eab-8f85-a65a7e9e2ddf)
<br></br>
![image](https://github.com/user-attachments/assets/8855138c-37cd-43ac-832a-60d62022c4ec)
<br></br>
![image](https://github.com/user-attachments/assets/bc028596-9b7d-4e2e-8ee7-f8aa8f7af494)
<br></br>
![image](https://github.com/user-attachments/assets/fdf2a421-b5ab-497f-8cd1-567e918bf659)
<br></br>
![image](https://github.com/user-attachments/assets/49b67f63-7724-4f31-a5fc-5db590b98d8b)
<br></br>
![image](https://github.com/user-attachments/assets/ed8b4ed0-cb23-4621-af0f-5e17e3fc7271)
<br></br>
![image](https://github.com/user-attachments/assets/aa5afc5b-8ab7-46cc-9f19-8b06be6384fd)
<br></br>
![image](https://github.com/user-attachments/assets/0616efbf-c79d-4a90-ba7c-63acb567b081)
<br></br>
![image](https://github.com/user-attachments/assets/4e37b9c5-8b09-444b-9e15-081d88e200e1)
<br></br>
![image](https://github.com/user-attachments/assets/10cb8ab9-1413-4f5d-9a5b-a29bcc9ee54d)
</br><br>
##2.1.3. Identificarea test case-urilor
<br></br>
Test case-urile sunt stabilite in functie de ceea ce se considera a fi testat in cadrul task-urilor:
<br></br>
![image](https://github.com/user-attachments/assets/706243a3-b993-4812-a772-2ac896b7fb7f)
<br></br>
2.1.4.Alocarea resurselor pentru cazurile de testare
</br><br>
Se aloca resursele necesare in ceea ce priveste cazurile de testare:

![image](https://github.com/user-attachments/assets/e6a947a6-277e-4f81-8e27-7108bad57200)
</br><br>
Acestea sunt cazurile de testare care cuprind diverse aspecte supuse testelor care vor fi efectuate in Jira si gestionate corespunzator
</br><br>
**2.2. Analiza testarii**
<br></br>
##2.2.1. Intelegerea requirement-urilor, a proprietatilor si a potentiale riscuri
</br><br>
/Se revizuieste si se analizeaza în detaliu story-urile create, cerințele funcționale și orice altă documentație din acest proiect.
</br><br>
/Se identifica principalele caracteristici, funcționalități și comportamente așteptate care trebuie validate prin testare precum campurile si alte functionalitati vizuale
<br></br>
S-au efectuat executii ale testelor :
</br><br>
![image](https://github.com/user-attachments/assets/85dcca7e-bff2-4799-8074-517ebe5d3dbf)
<br></br>
In mod implicit avem 9 teste valide si unul la care a fost observata o eroare 
In cazul erorii putem sa spunem ca este o prioritate mare in ceea ce priveste rezolvarea imediata a acesteia.
<br></br>
**2.2.2. Impartirea story-urilor in scenarii de testare**
</br><br>
Se precizeaza si se descompun urmatoarele story-uri:
<br></br>
![image](https://github.com/user-attachments/assets/93616aed-ac33-4e9e-94a6-a56fcf88cba8)
![image](https://github.com/user-attachments/assets/ef501768-2f46-4b1f-ac9b-b180f6f5178e)
![image](https://github.com/user-attachments/assets/6048b45d-25de-4aa5-8135-54e23808098f)
<br></br>
##2.3. Designul de testare
</br><br>
**2.3.1.Crearea cazurilor de testare detaliate cu pasi clari si asteptari anticipate**
</br><br>
Cazurile de testare din zephyr squad sunt:
<br></br>
![image](https://github.com/user-attachments/assets/4594ad0f-7ef8-495a-bdfb-761bf60e037f)
![image](https://github.com/user-attachments/assets/d2ea01b3-3f98-46bc-81d4-c299399bcbb7)
![image](https://github.com/user-attachments/assets/2d36b641-c353-4c78-b260-6ed2b36b28e1)
<br></br>
Acestia sunt pasii specifici fiecarui caz de testare din cadrul acestui magazin online:
<br></br>
![image](https://github.com/user-attachments/assets/001a06d5-057a-465a-b0d3-b40417b844ea)
<br></br>
![image](https://github.com/user-attachments/assets/8e583eb4-3456-4dec-b8c1-8e8fb6ea8f3d)
<br></br>
![image](https://github.com/user-attachments/assets/841a6a56-5f74-406a-bade-f956dca9c5e0)
<br></br>
![image](https://github.com/user-attachments/assets/2b9979fe-ae6e-46b7-be5e-f3cf95564c48)
<br></br>
![image](https://github.com/user-attachments/assets/be29c349-e8d1-4dee-946b-5b95758e0e8a)
<br></br>
![image](https://github.com/user-attachments/assets/844bc4a0-479b-45ae-8ec8-5ae3b5f4caa2)
<br></br>
![image](https://github.com/user-attachments/assets/5a3c4750-be56-433e-a2a2-ba02581824fe)
<br></br>
![image](https://github.com/user-attachments/assets/9c2b11f7-ed82-448c-8c22-e2ed6e803956)
<br></br>
![image](https://github.com/user-attachments/assets/f94edd52-1dc8-4d39-a130-a1e381ea0832)
<br></br>
S-au creat urmatoarele cazuri de testare:
<br></br>
![image](https://github.com/user-attachments/assets/2a08727e-11b1-42e0-9687-69ed6a1b4c42)
![image](https://github.com/user-attachments/assets/5edefcca-cd01-4d33-89f8-a69f50ff1ec7)
![image](https://github.com/user-attachments/assets/60bf4a30-0738-4cfc-969a-3e4676a81194)
<br></br>
**2.3.2.Definirea conditiilor de testare**
</br><br>
Testarea se face pe conditii de testare
<br></br>
2.4. Implementarea testului
<br></br>

![image](https://github.com/user-attachments/assets/deaea02d-5122-49cc-a7cb-a080ea4ac2f0)
![image](https://github.com/user-attachments/assets/04b8f347-e0af-4aae-ac9e-9e71682b183b)
![image](https://github.com/user-attachments/assets/cf1aee86-5e9d-40df-8d56-d1813849f621)
![image](https://github.com/user-attachments/assets/93af94c9-20ff-4221-9a83-3e9345f4f2bb)
![image](https://github.com/user-attachments/assets/619a1460-af0d-448d-b87e-5f448fe0fb36)
![image](https://github.com/user-attachments/assets/45844d1d-df62-4352-9768-4ddd49164d66)
![image](https://github.com/user-attachments/assets/b410541d-da4b-483d-80d9-15a0ea2693e3)
![image](https://github.com/user-attachments/assets/ac9aafa2-1844-451a-b908-d17a8cc39083)
![image](https://github.com/user-attachments/assets/31f94a9b-c4a4-4303-9461-abff7d9e2aef)
![image](https://github.com/user-attachments/assets/2ce38651-0369-4a0a-9cd7-33de48590b84)

</br><br>
##2.5. Executarea testelor
</br><br>
Configuratia testelor si rularea acestora cu rezultat:

![image](https://github.com/user-attachments/assets/2cfa905c-7760-4f69-97d5-323f91c5b6e0)

<br>1.Rezultatul testului care verifica daca pagina cu puncte de fidelitate are campuri care contin informatii despre punctele de fidelitate si conditiile despre cum sa fie folosite si verificam daca datele sunt actualizate in pagina</br>
![image](https://github.com/user-attachments/assets/dbc7ab82-c988-4c6d-b28c-6c0cad71fc2a)

<br></br>

<br>.2Rezultatul testului care verifica daca in departamentul financiar din pagina de suport online , formularul poate fi completat in campul cu email introducand adresa de email a utilizatorului, aceasta fiind validata </br>
![image](https://github.com/user-attachments/assets/d62ec054-227f-453a-9804-4cb374c7b16f)
![image](https://github.com/user-attachments/assets/746c8a38-bed4-418a-a705-a1d094c3dace)

<br></br>

<br>3.Rezultatul testului care verifica daca in departamentul de logistica din cadrul suportului online, campul cu numele poate fi completat adecvat, introducand numele utilizatorului si fiind validat</br>
![image](https://github.com/user-attachments/assets/b339b037-93ef-45c1-8106-bba0356ce535)
![image](https://github.com/user-attachments/assets/7d212cab-978c-49b1-9cbd-ec11983e8b92)

<br></br>

<br>4.Rezultatul testului care verifica daca pagina de suport online contine informatii despre sectiunea de suport, un sumar concis si ca departamentele de suport online sunt vizibile </br>
![image](https://github.com/user-attachments/assets/a8e2d778-5826-4135-bd83-45c69fa25a44)
![image](https://github.com/user-attachments/assets/1258838a-8295-44c8-886f-3f36aec16435)

<br></br>

<br>5.Rezultatul testului care verifica daca pagina "Verificarea coletului la livrare"  contine informatii despre verificarea pachetului, are informatii despre posibilitatea de a returna produsele si are o descriere despre costurile de expeditie</br>
![image](https://github.com/user-attachments/assets/2f978c9d-622a-48ef-be6f-56cf98573e3a)
![image](https://github.com/user-attachments/assets/96def13d-f797-4e94-90d3-427515013d16)

<br></br>

<br>6.Rezultatul testului care verifica daca pagina "Modalitati de Livrare" din cadrul epicului "Livrare" continte informatii despre cum sunt livrate produsele si are o sectiune despre posibilitatile de livrare</br>
![image](https://github.com/user-attachments/assets/b517a3ef-3b27-4178-9f35-1de941fb1c2f)
![image](https://github.com/user-attachments/assets/9a11475a-4460-4815-88cc-c78310b8a7e2)

<br></br>

<br>7.Rezultatul testului care verifica daca utilizatorul poate da click pe "Product Management" din sectiunea de suport online ,aparand astfel formularul si campul cu mesaje sa poate <fi completat adecvat introducand mesajul utilizatorului, acesta fiind validat si trimis la adresa specifica/br>
![image](https://github.com/user-attachments/assets/5712eccf-cfde-4acd-b73e-73c1f7d8043b)
![image](https://github.com/user-attachments/assets/a5d4fd1c-ba1c-4a89-855e-ebf1ad8b7a45)

<br></br>

<br>8.Rezultatul testului care verifica daca in departamentul de vanzari la formular, campul cu locatia poate fi completat introducand locatia utilizatorului si fiind validata</br>
![image](https://github.com/user-attachments/assets/1f69689a-332e-4945-817e-6bb5eb42f9ab)
![image](https://github.com/user-attachments/assets/d335dcaa-a30c-4b56-b812-2c76780c9d7e)

<br></br>

<br>9.Rezultatul testului care verifica daca in departamentul de marketing, campul cu telefonul poate fi completat introducand numarul de telefon al utilizatorului si fiind validat</br>
![image](https://github.com/user-attachments/assets/2bc6f493-fad8-4a65-aac2-20e3b58957f9)
![image](https://github.com/user-attachments/assets/7c9220a6-2757-4da7-950e-a85fcf4e6cf6)

<br></br>

<br>10.Rezultatul testului care verifica daca in departamentul de vanzari un camp cu numele poate fi completat introducant un nume al utilizatorului dintr-o combinatie de litere si cifre</br>
![image](https://github.com/user-attachments/assets/bbd200a0-9e89-4a01-8909-c9bad4a13b23)
![image](https://github.com/user-attachments/assets/666e51c8-a932-4a13-9e1a-fe1abf8bed4e)

</br><br>
**2.6. Concluzia testarii**
</br><br>
In urma executarii acestor pasi din zephyr, se poate observa ca nu avem erori semnificative asa cum erau prezentate mai sus atat testele fail, cat si pass si se poate observa o eroare in cadrul departamentului de vanzari din suportul online care are un camp ce nu poate fi completat sub forma de username ca si combinatie de litere si cifre, ci trebuie completat cu numele in litere al utilizatorului

</br><br>
![image](https://github.com/user-attachments/assets/869c4f76-11b9-4074-b8e2-c10cae67c319)
![image](https://github.com/user-attachments/assets/fb8743ad-f34b-4817-8313-005ef05ad807)
![image](https://github.com/user-attachments/assets/dcc21068-8250-4c5c-b8f3-87e3724e613e)

</br><br>

##2.7. Monitorizarea testului si control
</br><br>
Se evaluaza și furnizeaza feedback continuu asupra activităților de testare si se monitorizeaza traficul pe site și indicatorii de angajament a utilizatorilor, ca si numărul de vizualizări de pagini, rata de bounce, timpul petrecut pe site.Se monitorizeaza eficienta paginilor in ceea ce priveste organizarea si orientarea utilizatorului si se urmaresc eventuale erori din cadrul campurilor care trebuie completate sau a unor erori de compatibilitate.
<br></br>
**3. Livrabile de testare**
<br></br><br></br>
##3.1.Test plan
</br><br>
Se verifica funcționalitatea întregului site, se valideaza exactitatea și completitudinea datelor despre suport online, formularele de contact din cadrul departamentelor online si modul de completare al acestora. 
</br><br>
In cadrul site-ului se verifica si modul in care utilizatorul vede informatia in cadrul modalitatilor de livrare din cadrul epicului "Livrare" si se urmareste daca datele sunt actuale si imbunatatite in cazul in care sunt necesare explicatii mai amanuntite.
</br><br>
**3.2.Conditii de testare**
</br><br>
Hardware: Testul facut pe un calculator windows 10, cu 8gb ram,procesor i3 sau asemanator si un hard drive sau ssd cu macar 20gb spatiu liber
Software: Se foloseste google chrome sau mozilla firefox pentru testare.
Capacitate retea: se asigura o viteza de internet stabila si o largime de banda minima cu un minim de 4mbps download si 2mbps upload
</br><br>
Roluri: se testeaza cu utilizatorul neinregistrat sau inregistrat.
Configuratii de sistem: se configureaza sistemul pentru testarea functionalitatii in cadrul suportului online, al formularelor si al modalitatilor de livrare.
</br><br>
##3.3.Cazuri de testare
</br><br>
<br>Cazurile de testare pozitive (9) si negative(1) care cuprindeau pasii care au fost explicati inainte, ca exemplu:</br>

![image](https://github.com/user-attachments/assets/5a718a34-feab-4c48-93b9-b85f406a7059)

<br>Avem aceste 10 cazuri de testare:</br>

![image](https://github.com/user-attachments/assets/94ac8eb9-e291-4632-b61a-ca50bebef02c)

<br>Aceste 10 cazuri de testare verifica si se asigura de urmatoarele:</br>

<br>1. Verifică dacă pagina de Suport Online conține suficiente informații legate de magazin, asigurându-te că utilizatorul poate accesa toate departamentele de suport enumerate și că are posibilitatea de a accesa departamentele de suport în funcție de alegerea făcută.</br> 
<br>2. Verifică dacă în categoria "Departamentul logistică" un câmp poate fi completat corespunzător prin introducerea numelui utilizatorului și că acesta este validat. </br>
<br>3. Verifică dacă în categoria de suport "Departamentul financiar" un câmp poate fi completat corespunzător prin introducerea adresei de email a utilizatorului și că acesta este validat. </br>
<br>4. Verifică dacă categoria de suport "Departamentul Marketing" are un câmp care poate fi completat corespunzător prin introducerea numărului de telefon al utilizatorului și că acesta este validat </br>
<br>5. Verifică dacă categoria de suport "Departamentul Vânzări" are un câmp care poate fi completat corespunzător prin introducerea locației utilizatorului după nume și că acesta este validat</br>
<br>6. Verifică dacă secțiunea "Puncte de fidelitate" are câmpuri care conțin informații despre descrierea punctelor de fidelitate, condițiile aferente acestora și modul de utilizare, și verifică dacă datele sunt actualizate. </br>
<br>7. Verifică dacă categoria de suport "Managementul produselor" are un câmp care poate fi completat corespunzător prin introducerea mesajului utilizatorului și că acesta poate fi trimis către suportul specific pentru managementul produselor</br>
<br>8. Verifică dacă categoria "Modalități de livrare" are o pagină care conține multiple informații despre expedierea produselor.</br>
<br>9. Verifică dacă formularul "Departamentul Vânzări" din categoria de suport online are un câmp în secțiunea de date de contact care poate fi completat cu numele utilizatorului, scris și ca nume de utilizator, inclusiv cifre (aici avem bug-ul)</br>
<br>10. Verifică dacă secțiunea "Verificarea coletului la livrare" conține informații despre verificarea produselor</br>

##3.4. Rapoarte zilnice
</br><br>
Se intocmesc rapoarte in vederea urmaririi eventualelor defecte sau erori
<br></br>
![image](https://github.com/user-attachments/assets/841cd9c4-61a9-4f97-89a5-77d5b1985d11)
![image](https://github.com/user-attachments/assets/20e2d3f0-b6a5-4aae-a999-7dd609aba626)

</br><br>
**3.5. Matricea de trasabilitate**
</br><br>
Se realizeaza o matrice de trasabilitate avand in vedere cele prezentate:

![image](https://github.com/user-attachments/assets/cd69bd33-6729-416f-bc15-1565b4a4813f)
![image](https://github.com/user-attachments/assets/f8210209-7482-4090-9e28-ce1bdd8d67d8)

</br><br>
##3.6. Rezultate test case-uri
</br><br>
Rezultatele cazurilor de testare in urma executarii testelor : 9 cazuri de testare pass si 1 fail

![image](https://github.com/user-attachments/assets/ab0355c5-6c00-4eaf-85f6-eaa5c46cb338)
![image](https://github.com/user-attachments/assets/d440099e-16a4-48f3-bc5c-f9b5868fe99e)
![image](https://github.com/user-attachments/assets/c807be1c-ca50-40a0-8300-a1ce6fb9d2c1)


</br><br>
**3.7. Raportari de bug-uri**
</br><br>
Aplicația ar trebui sa aiba un camp pentru introducerea username-ului unui utilizator la formularul de contact din cadrul departamentului de vanzari ,dar utilizatorul nu are permisiunea sa introduca numele ca si o combinatie intre litere si cifre, astfel ca avem un bug.

![image](https://github.com/user-attachments/assets/4a7caab5-8bca-47f8-951d-c770c87eb168)

</br><br>
##3.8. Raport de testare completa
</br><br>
![image](https://github.com/user-attachments/assets/39080fee-6721-4b0d-b81e-cce16d72a5a6)
![image](https://github.com/user-attachments/assets/7e6082ba-e748-4d33-a014-82446695cfcb)
![image](https://github.com/user-attachments/assets/df6bef96-49f9-4d29-995c-8eba929bee22)
![image](https://github.com/user-attachments/assets/f4a9796e-d11d-4156-83fa-e65e68791114)
</br><br>

In cadrul acestui magazin online se vor efectua si alte teste si vor fi imbunatatite anumite aspecte si functionalitati in ceea ce priveste diverse puncte de vedere.

































