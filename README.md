Programa nuskaito vartotojų įvedamus reikiamus duomenis (struktūros elementai):
studento vardą ir pavardę;
namų darbų ir egzamino rezultatą;
Baigus duomenų įvedimą, suskaičiuoja galutinį balą ir juos pateikia į ekraną tokiu ar panašiu pavidalu (kur galutinis apskaičiuotas balas pateikiamas dviejų skaičių po kablelio tikslumu):
Ji veiktia ir tokiu atveju, kai namų darbų ir įrašų skaičiai (n, m) yra nežinomi iš anksto, t.y. tik įvedimo metu vartotojas nusprendžia kuomet jis jau įvedė visų namų darbų rezultatus ir kada jis baigią žmonių įvedimą. Šią dalį realizuoti reiktų dviem būdais, kur namų darbų rezultatus saugant į:

C  masyvą;
std::vector  tipo konteinerį.

Du *.cpp kreipiasi į mylib.h:
Kodas masyvas.cpp naudoja dinaminius masyvus;
Kodas vekotorius.cpp naudojant vektorius;
