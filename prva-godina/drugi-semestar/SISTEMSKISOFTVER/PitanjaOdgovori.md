# Pitanja i odgovori

## Koliko ima ciklusa i koji je drugi ciklus?

- Ima 4 ciklusa i drugi je decode ciklus

## Šta je TLB keš?

- TLB je keš koji drži fizičku adresu (memorijske) stranice radi bržeg memorijskog pristupa

## Kolika je dužina instrukcije kod pipeline-a? Kakva isntrukcija treba da bude?

- Dužina instrukcije mora da bude uniformna, veličine je 32 bita i mora biti prosta za memorijski pristup

## Šta je superskalarni procesor?

- Superskalarni procesor može da izvršava više instrukcija istovremeno

## Šta je prost statički prediktor?

- Kod prostog statičkog prediktora uslovno grananje se neće izvršiti

## Šta je prostorni lokalitet?

- Prostorni lokalitet je mali kontinualni podskup podataka koji se koristi u kontinuitetu

## Kako je organizovana keš memorija?

- Keš memorija je organizovana u 3 nivoa i ona komunicira sa memorijom,
adresna organizacija linije je TAG : Skup : OFFSET

## Kako je organizovana virtuelna memorija?

- Virt. memorija se deli na stranice, postoje tabele koje pokazuju na te stranice,
mora postojati prevođenje iz virtuelne u fizičku adresu memorije,
najbolje rešenje je keširanje preko TLB keša

## Koliko najmanje nivoa bezbednosti mora da bude kod virtualizacije?

- Dva???

## Šta je hypervisor?

- Hipervizor je softver/firmver/hardver koji kreira i pokreće virtuelne mašine.

## Šta je MMU?

- Memory management unit koji se nalazi na procesoru kao podsistem za
upravljanje memorijom

## Koje su dve osnovne vrste keša?

- Direktno i asocijativno mapirani keš
- Skupovno asocijativni keš je kombinacija ova dva

## Kako brzi memorijski uređaji pristupaju memoriji?

- Direktno

## Kako povećati propusnu moć memorije?

- Danas se koristi integrisani mem kontroler na procesoru

## Navedi neke korisnike memorije?

- Grafički podsistem, disk i memorijski kontroleri

## Kakav je način izvršavanja instrukcija?

- Sekvencijalan

## Šta je spekulativno izvršavanje?

- Izvršavanje instrukcija unapred

## Kada se dešava dinamički a kada statički branch prediction?

- Statički compile time, dinamički runtime
