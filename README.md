<p align="center">
<b>Policija</b> <br></br>
Sveučilište Jurja Dobrile u Puli <br></br>
Fakultet Informatike u Puli
Kolegij: Baze Podataka 2 <br></br>
</p>
<hr>

**Mentori:** 
 <ul>doc. dr. sc. Goran Oreški</ul>
 <ul>Romeo Šajina, mag. inf.</ul>

<br></br>
**Članovi (abecednim redom):** 
<ol>Maja Ajhorn</ol>
<ol>Nika Horvat</ol>
<ol>Antonio Labinjan</ol>
<ol>Petar Prenc</ol>
<ol>Ana Rogalo</ol>
<ol>Anastazija Širol</ol>
<hr>
Tema projekta je "Policija". <br></br>
Na ovom se repozitoriju nalazi projektni zadatak tima 7.
<hr>

<h4>Deliverables</h4>
<ul><b>Tablice:</b>
- Podrucje_uprave
<ol>Mjesto</ol>
<ol>Zgrada</ol>
<ol>Radno_mjesto</ol>
<ol>Odjeli</ol>
<ol>Osoba</ol>
<ol>Zaposlenik</ol>
<ol>Vozilo</ol>
<ol>Predmet</ol>
<ol>Kaznjiva_djela</ol>
<ol>Pas</ol>
<ol>Slucaj</ol>
<ol>Evidencija_dogadaja</ol>
<ol>Kaznjiva_djela_u_slucaju</ol>
<ol>Izvjestaji</ol>
<ol>Zapljene</ol>
<ol>Sredstvo_utvrdivanja_istine</ol>
<ol>Sui_slucaj</ol>
</ul>

<hr>

<ul><b>Upiti:</b>
 <ol>Ispiši prosječan broj godina osoba koje su prijavile digitalno nasilje</ol>
 <ol>Prikaži osobu čiji je nestanak posljednji prijavljen</ol>
<ol>Prikaži najčešću vrstu kažnjivog djela</ol>
<ol>Ispišimo sve voditelje slučajeva i slučajeve koje vode</ol>
<ol>Ispišimo slučajeve i evidencije za određenu osobu</ol>
<ol>Ispišimo sve osobe koje su osumnjičene za određeno kažnjivo djelo</ol>
<ol>Pronađimo sve slučajeve koji sadrže KD i nisu riješeni</ol>
<ol>Izračunajmo iznos zapljene za svaki pojedini slučaj</ol>
<ol>Pronađi prosječnu vrijednost zapljene za pojedina KD</ol>
<ol>Pronađi sve odjele i broj zaposlenika na njima</ol>
<ol>Pronađi ukupnu vrijednost zapljena po odjelu i sortiraj ih po vrijednosti silazno</ol>
<ol>Pronađi osobu koja mora odslužiti najveću ukupnu zatvorsku kaznu</ol>
<ol>Prikaži sva vozila i broj slučajeva u kojima su se pojavila</ol>
<ol>Pronađi mjesto s najviše slučajeva</ol>
<ol>Pronađi mjesto s najmanje slučajeva</ol>
<ol>Pronađi policijskog službenika koji je vodio najviše slučajeva</ol>
<ol>Ispiši sva mjesta gdje nema evidentiranih kažnjivih djela u slučajevima</ol>
</ul>

<hr>

<ul><b>Pogledi:</b>
<ol>Pronađimo sve osumnjičenike i njihova vozila</ol>
<ol>Pronađimo sve policijske službenike koji su vlasnici vozila starijih od 10 godina</ol>
<ol>Pronađimo sve osobe koje su počinile kažnjivo djelo pljačke i pri tome koristile pištolj</ol>
<ol>Pronađimo sva evidentirana kažnjiva djela i njihov postotak pojavljivanja u slučajevima</ol>
<ol>Pronađimo sva evidentirana sredstva utvrđivanja istine i broj slučajeva u kojima je svako od njih korišteno</ol>
<ol>Pronađimo sve slučajeve i sredstva utvrđivanja istine u njima, te računamo trajanje svakog od slučajeva</ol>
<ol>Pronađimo sve slučajeve i izvještaje vezane uz njih</ol>
<ol>Pronađimo sve osobe i njihove odjele. Ukoliko osoba nije policijac i stoga nema svoj odjel, uz nju se ispisuje odgovarajuća obavijest</ol>
<ol>Pronađimo sve voditelje slučajeva, ukupan broj slučajeva koje vode, ukupan broj riješenih slučajeva, ukupan broj neriješenih slučajeva i postotak riješenosti za svakog voditelja</ol>
<ol>Pronađimo statistiku zapljena za svaku vrstu kažnjivog djela (prosjek, minimum, maksimum i broj vrijednosti)</ol>
<ol>Izračunajmo ukupnu zatvorsku kaznu za svaki slučaj uz ograničenje da ona u RH ne smije prelaziti 50 godina</ol>
<ol>Izračunajmo za svakog policijskog službenika dob i godine staža, te dohvatimo obavijest je li umirovljen ili ne</ol>
<ol>Pronađimo sve osumnjičenike i kažnjiva djela za koja su osumnjičeni</ol>
<ol>Pronađimo sve pse, broj slučajeva na kojima su radili, broj riješenih slučajeva i postotak rješenosti za svakog psa</ol>
<ol>Nadogradimo prethodni pogled tako da dohvatimo najeikasnijeg psa, s najvećim postotkom riješenosti</ol>
<ol>Pronađimo broj kazni zbog brze vožnje u zadnjih mjesec dana u svakom gradu</ol>
<ol>Pronađimo sve osobe koje su skrivile više od 2 prometne nesreće u zadnjih godinu dana</ol>
<ol>Pronađimo sva kažnjiva djela koja su se događala u slučajevima</ol>
<ol>Pronađimo sve osobe, slučajeve u kojima su okrivljene i kažnjiva djela u njima</ol>
<ol>Dohvatimo sve događaje koji su vezani uz slučajeve koji u sebi sadrže određeno kažnjivo djelo</ol>
<ol>Dohvatimo sve slučajeve koji su se dogodili u posljednjih n dana</ol>
<ol>Dohvatimo sve slučajeve koji sadrže određeno kažnjivo djelo i sortirajmo ih po vrijednosti zapljene silazno</ol>
<ol>Dohvatimo sve slučajeve, njihovog voditelja i ukupnu vrijednost zapljena za svaki. Ako nema pronađenih slučajeva, dobivamo prikladnu obavijest</ol>
</ul>

<hr>

<ul><b>Trigeri:</b>
<ol>Onemogućimo da se na slučaju koristi pas koji nije zadužen za kažnjiva djela u tom slučaju</ol>
<ol>Zabranimo da se obriše područje uprave s više od 5 mjesta, a ako se obriše područje s manje od 5 mjesta, onda dobivamo upozorenje da je u tim mjestima provotno područje uprave obrisano i da moramo povezati mjesto s novim područjem</ol>
<ol>Onemogućimo da se iz tablice osoba brišu osobe koje su aktivni zaposlenici</ol>
<ol>Postavimo kažnjivo djelo psa na NULL ukoliko je kažnjivo djelo za koje je zadužen obrisano iz baze</ol>
<ol>Zabranimo brisanje predmeta koji služe kao dokazi u aktivnim slučajevima</ol>
<ol>Zabrana brisanja osoba koje su počinitelji u aktivnim slučajevima</ol>
<ol>Zabrana brisanja izvještaja za nezavršene slučajeve i slučajeve koji su završili u manje od zadnjih 10 godina</ol>
<ol>Osiguravanje točnosti spola pri unosu osoba</ol>
<ol>Kreiranje stupca za praćenje ukupne vrijednosti zapljena kod svakog slučaja</ol>
<ol>Premještanje završenih slučajeva u arhivu (pretvoreno u proceduru zato što ne želimo da netko slučajno automatski arhivira slučaj krivim updateom u bazi)</ol>
<ol>Provjera da osoba nije nadređena sama sebi</ol>
<ol>Provjera da su datumi početka i završetka slučaja različiti</ol>
<ol>Časno umirovljenje pasa starijih od 10 godina</ol>
<ol>Zabrana uporabe umirovljenih pasa u slučajevima</ol>
<ol>Dodavanje posebne napomene za maloljetnike</ol>
<ol>Onemogućavanje da maloljetnici budu vlasnici vozila</ol>
<ol>Postavljanje datuma završetka slučaja na današnji pri izmjeni statusa u završeno</ol>
<ol>Provjera da su počinitelj i svjedok različite osobe</ol>
<ol>Provjera pravilne strukture e-maila</ol>
<ol>Ograničenje broja slučajeva po zaposleniku</ol>
<ol>Zabrana da isti voditelj otvara više slučajeva protiv iste osobe ukoliko su neki riješeni</ol>
<ol>Osiguranje provođenja poligrafskog ispitivanja</ol>
<ol>Zabrana promjene zgrade zaposlenika izvan njegovog područja uprave</ol>
</ul>
<hr></hr>

<ul><b>Procedure:</b>
 
 <h4>Trivijalne insert procedure:</h4>
     <ol>Unos područja uprave</ol>
     <ol>Unos mjesta</ol>
     <ol>Unos zgrade</ol>
     <ol>Unos radnog mjesta</ol>
     <ol>Unos odjela</ol>
     <ol>Unos osobe</ol>
     <ol>Unos zaposlenika</ol>
     <ol>Unos predmeta</ol>
     <ol>Unos kažnjivog djela</ol>
     <ol>Unos psa</ol>
     <ol>Unos novog slučaja</ol>
     <ol>Unos događaja u evidenciju</ol>
     <ol>Unos kažnjivog djela u slučaju</ol>
     <ol>Unos izvještaja</ol>
     <ol>Unos zapljene</ol>
     <ol>Unos sredstva utvrđivanja istine</ol>
     <ol>Unos sredstva utvrđivanja istine u slučaju</ol>

 <h4>Naprednije procedure:</h4>
       <ol>Unos vozila uz napomenu o vlasništvu</ol>
       <ol>Godišnje nagrađivanje pasa</ol>
       <ol>Godišnje nagrađivanje zaposlenika</ol>
       <ol>Provjera nekažnjvanja</ol>
       <ol>Izmjena kontakt informacija</ol>
       <ol>Izmjeni kaznu</ol>
       <ol>Izmjeni novčanu kaznu</ol>
       <ol>Unaprijedi policijskog službenika</ol>
       <ol>Ažuriraj podatke zatvor + event Dnevno odbrojavanje</ol>
       <ol>Projveri istek zatvorske kazne + event Provjera isteka kazni</ol>
       <ol>Nagodba</ol>
       <ol>Broj zapljena u zgradi</ol>
       <ol>Umirovi sluzbenika</ol>
       <ol>Provjeri okrivljenika</ol>
       <ol>Izracunaj starost vozila</ol>
</ul>     
<hr></hr>
<ul><b><h3>Funkcije + upiti:</h3></b>
 <ol>KDInfo</ol>
 <ol>Informacije o osobi po telefonu</ol>
 <ol>Dohvati slučaj i osobu</ol>
 <ol>Izracunaj postotak rješenosti</ol>
 <ol>Provjera vozila</ol>
 <ol>Podaci o području</ol>
 <ol>Broj kažnjivih djela u slučaju</ol>
 <ol>Broj slučajeva po statusu</ol>
 <ol>Informacije o slučaju</ol>
 <ol>Zaposlenik slučaj</ol>
 <ol>Osoba oštećenik</ol>
 <ol>Uloge osobe u slučajevima</ol>
 <ol>Sumnjivost osobe</ol>
 <ol>Broj zaposlenih 6mj</ol>
 <ol>Avg slucaj osoba odjel</ol>
</ul>
<hr></hr>
<ul><b><h3>Transakcije:</h3></b>
 <ol>Minimalno opterećenje psa</ol>
 <ol>Broj izvještaja za slučaj</ol>
 <ol>Događaji u zadnje 3 godine</ol>
 <ol>Dodavanje kažnjivih djela</ol>
 <ol>Pregled službenih vozila</ol>
</ul>
<hr></hr>
<ul><b><h3>Korisnici:</h3></b>
 <ol>admin</ol>
 <ol>hr</ol>
 <ol>fizicka osoba</ol>
 <ol>detektiv</ol>
</ul>
<hr></hr> 
