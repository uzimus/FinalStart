# Start Today (Începe Azi) - Ghid de Utilizare

Bine ai venit! Am creat un site web complet, în limba română, pentru ONG-ul tău Start Today. Iată tot ce trebuie să știi.

## 📁 Ce Conține

Site-ul tău are 6 pagini:
1. **index.html** - Pagina de acasă cu secțiune hero, misiune și programe
2. **despre.html** - Povestea organizației și valorile tale
3. **programe.html** - Detalii despre Campanii de Sterilizare și Educație
4. **echipa.html** - Membrii echipei (Mihaela Gheorghe, Ștefania Gheorghe, Vlad Grigore)
5. **doneaza.html** - Pagina de donații
6. **contact.html** - Formular de contact
7. **style.css** - Tot stilul și culorile într-un singur fișier

## 🎨 Tema de Culori

Site-ul folosește o paletă verde/turcoaz calmantă:
- **Verde Principal (#52B788)** - Butoane, accenturi
- **Teal (#40916C)** - Secțiuni, linkuri
- **Turcoaz (#6DB6B4)** - Gradienți
- **Verde Deschis (#74C69D)** - Detalii
- **Mint (#95D5B2)** - Accente

## 🚀 Cum să Începi

### Opțiunea 1: Deschide Direct (Cea Mai Rapidă)
1. Descarcă toate fișierele într-un folder pe computerul tău
2. Dă dublu-click pe `index.html` pentru a-l deschide în browser
3. Gata! Site-ul funcționează local.

### Opțiunea 2: Pentru Editare
1. Descarcă toate fișierele într-un folder
2. Deschide folderul într-un editor de text:
   - **VS Code** (recomandat, gratuit)
   - Notepad++ (Windows)
   - Sublime Text
   - Chiar și Notepad simplu funcționează!
3. Editează fișierele HTML și CSS
4. Salvează și reîmprospătează browser-ul pentru a vedea modificările

## ✏️ Cum să Personalizezi

### Schimbă Culorile
Deschide `style.css` și găsește această secțiune la început (în jurul liniilor 10-20):
```css
:root {
  --primary-green: #52B788;
  --primary-teal: #40916C;
  --primary-light-green: #74C69D;
  --primary-turquoise: #6DB6B4;
  --primary-mint: #95D5B2;
}
```
Înlocuiește aceste coduri de culoare cu propriile tale! Folosește un site de alegere a culorilor pentru a găsi coduri hex.

### Schimbă Conținutul Text
1. Deschide orice fișier `.html`
2. Găsește textul pe care vrei să-l schimbi
3. Editează-l direct (totul între `>` și `<`)
4. Salvează fișierul

**Exemplu:**
```html
<h1>Fă primul pas</h1>
```
Schimbă "Fă primul pas" cu propriul tău slogan!

### Adaugă Statistici Reale
În `index.html`, găsește secțiunea Impact Stats:
```html
<div class="stat-number">[Număr]</div>
<div class="stat-label">Animale Sterilizate</div>
```
Înlocuiește `[Număr]` cu statisticile reale ale organizației tale!

### Actualizează Informații de Contact
În footer-ul fiecărui fișier HTML, găsește:
```html
<li>📧 [Adresa de email]</li>
<li>📱 [Număr de telefon]</li>
<li>📍 București, România</li>
```
Înlocuiește cu informațiile tale reale de contact!

### Adaugă Poze și Descrieri la Echipă
În `echipa.html`, găsește cardurile membrilor echipei:
```html
<h3>Mihaela Gheorghe</h3>
<div class="team-role">Președinte</div>
<p>[Poți adăuga aici descrierea și experiența]</p>
```
Adaugă descrieri pentru fiecare membru. Pentru poze reale:
1. Pune pozele în folderul site-ului
2. Înlocuiește emoji-ul cu `<img src="nume-poza.jpg" alt="Nume Persoană">`

### Înlocuiește Imaginile
Site-ul folosește imagini gratuite de la Unsplash. Pentru a folosi propriile tale:
1. Găsește URL-urile imaginilor în HTML (caută `https://images.unsplash.com/...`)
2. Înlocuiește-le cu propriile tale URL-uri sau căi locale
3. Pentru imagini locale: pune imaginile în folderul site-ului și folosește `nume-imagine.jpg`

## 📱 Responsive pentru Mobil

Site-ul se ajustează automat pentru telefoane și tablete! Meniul de navigare se transformă într-un meniu hamburger pe ecrane mici.

## 🎯 Caracteristici Cheie

✅ **Design Calm Verde/Turcoaz** - Plăcut pentru ochi, potrivit pentru protecția animalelor
✅ **Animații Fluide** - Efecte fade-in și hover
✅ **Mobil Friendly** - Funcționează perfect pe toate dispozitivele
✅ **Cod Curat** - Extrem de comentat pentru ușurință în înțelegere
✅ **Ușor de Editat** - Tot textul și imaginile pot fi schimbate simplu
✅ **Layout Profesional** - Carduri, grid-uri și secțiuni bine organizate
✅ **În Română** - Tot conținutul în limba română

## 🔧 Editări Comune

### 1. Adaugă Mai Multe Detalii la Programe
În `programe.html`, poți adăuga mai multe informații despre campaniile tale de sterilizare și programele educaționale.

### 2. Personalizează Secțiunea "Despre"
În `despre.html`, poți adăuga povestea completă a organizației și detalii despre valorile voastre.

### 3. Actualizează Opțiunile de Donație
În `doneaza.html`, poți schimba sumele sugestate și exemplele de impact pentru a reflecta costurile reale.

## 💡 Sfaturi pentru Editare

1. **Fă o schimbare odată** - Salvează și reîmprospătează pentru a vedea rezultatul
2. **Păstrează backup-uri** - Salvează copii înainte de modificări mari
3. **Testează pe mobil** - Redimensionează fereastra browser-ului pentru a vedea cum arată pe telefoane
4. **Folosește instrumentele de dezvoltare** - Click dreapta > Inspect pentru a experimenta cu stilurile
5. **Nu șterge class-urile CSS** - Numele class-urilor conectează HTML-ul cu stilizarea

## 🌐 Publicarea Site-ului

Când ești mulțumit(ă) de editările tale:

1. **Opțiuni de Hosting Gratuit:**
   - GitHub Pages (gratuit, recomandat)
   - Netlify (plan gratuit disponibil)
   - Vercel (plan gratuit disponibil)

2. **Încarcă toate fișierele** pe serviciul ales
3. Site-ul tău va fi live pe internet!

## 📝 Structura Generală

```
Folderul Site-ului/
├── index.html          (Pagina de acasă)
├── despre.html         (Despre noi)
├── programe.html       (Programele noastre)
├── echipa.html         (Echipa)
├── doneaza.html        (Donații)
├── contact.html        (Contact)
└── style.css           (Tot stilul)
```

Toate paginile folosesc același fișier `style.css`, deci o schimbare CSS afectează tot site-ul!

## 🐾 Specific pentru Start Today

Site-ul este adaptat pentru misiunea ta:
- **Focus pe Sterilizare** - Programele evidențiază campaniile de sterilizare
- **Educație și Advocacy** - Secțiune dedicată pentru educație
- **București** - Referințe la locație în tot site-ul
- **Emoji Relevante** - 🐾 pentru branding
- **Culori Calmante** - Verde/turcoaz potrivit pentru protecția animalelor

## ✨ Pași Următori

1. Descarcă toate fișierele
2. Deschide `index.html` în browser pentru a vedea site-ul
3. Începe să personalizezi conținutul cu informații reale despre ONG-ul tău
4. Adaugă statistici și date reale
5. Încarcă propriile tale imagini și poze
6. Testează totul pe mobil
7. Publică pe web!

**Mult succes cu site-ul ONG-ului tău! 🐾**

Dacă întâmpini probleme sau ai întrebări, nu ezita să revii și să întrebi!
