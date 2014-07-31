XO-igrica
=========
Rana varijanta XOX igre je igrata jos u Rimskom carstvu, oko prvog veka pre nove ere. Postoje razliciti nazivi ove igre i oni su novijeg datuma na pr. Tic-tac-toe, Tri musko moris...
Godine 1952. je igra XOX za EDSAC racunar postala jedna od prvih poznatih video igara, gde racuna igrac igra protiv coveka igraca.
Uprkos ociglednoj jednostavnosti XOX igra zahteva detaljnu analizu da se utvrde cak i neke elementarne cinjenice kao sto su najinteresantniji broj mogucih igara i broj mogucih pozicija. Pozicija je samo stanje odabira, dok igra se obicno odnosi na nacin na koji se dobija pozicija.
Naivno brojanje dovodi do 19.683 mogucih rasporeda odoabira (39 jer svako od 9 polja moze biti X, O ili prazno i 362.880 tj.9!)  mogucih razlicitih igara za stavljanje X i O na tabeli. Medjutim, dve stvari mogu mnogo da smanje ove brojeve to su: 
1)	igra se zavrsava kada su three in a row se dobija
2)	broj X je uvek jednak ili za 1 vise od O ako X pocne prvi.
Opis igre
XOX igra sadrzi 9 praznih polja (kvadrata) postavljenih u mrezu 3x3. Igrac popunjava polja bilo sa X ili O (prema svom izboru znaka). U sledecem potezu racunar bira prazno polje. Cilj je da se postigne neko konacno stanje (pobeda). Stanje pobede je kada se zauzmu 3 uzastopna polja u nekoj vrsti, koloni ili dijagonali, dok je u suprotnom nereseno.
Igra XOX ima sledece klase:
1)	tabli
2)	igraca
3)	coveka
4)	racunara
5)	igra
1)	Klasa tabli sadrzi graficku plocu (Panel) na kojoj je prikazano 3x3 polja. Polja mogu biti prazna ili mogu sadrzati oznaku igraca koji je zauzeo dato polje. Moze da se postavi oznaka nekog od igraca na dato polje (greska je ako to polje nije prazno) i da se dohvati oznaka na datom polju, da se isprazne oznake svih polja i da se zatrazi indeks polja koje je pritisnuto na graficki korisnickoj povrsi.
2)	Klasa igrac ima oznaku i potez izvodi na tabli. Izvodjenje poteza se sastoji od izbora polja i pokusaja postavljanja svoje oznake na to polje sve dok postavljanje oznake ne uspe.
3)	Klasa covek je igrac koji polja bira tako da od table zatrazi indeks pritisnutog polja.
4)	Klasa racunar je igra koji nasumice bira indeks polja
5)	Klasa igra upravlja igrom dva igraca na zadatoj tabeli i prikazuje oznaku pobednika na zadatoj grafickoj komponenti tipa Label. Igraci naizmenicno stavljaju svoje oznake na slobodna polja. Pobednik je onaj koji prvi zauzme 3 uzastopna polja u nekoj vrsti, koloni ili dijagonali, a u suprotnom igra je neresena.


