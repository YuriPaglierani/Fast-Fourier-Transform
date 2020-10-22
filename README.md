# Fast-Fourier-Transform
Prima di iniziare a programmare leggi velocemente la guida di Github sulle repository, in questo modo miglioreremo l'amministrazione del lavoro.

Dobbiamo poi decidere come procedere, i punti fondamentali che secondo me bisogna tenere in considerazione sono: leggere il libro del C, capire quali librerie utilizzare, capire esattamente come funziona l'algoritmo di FFT nei suoi vari punti e infine dividere il lavoro tra generazione del segnale in input (segnale pulito + rumore gaussiano) e algoritmo di FFT.

Nota: Github usa il Markdown come linguaggio di formattazione (tipo Latex ma più facile).

Mancano:

-segnale da mp3 a dati

-plot: segnale + trasformata di Fourier

-filtraggi vari

-breve power point esplicativo


# Indirizzi utili

*Note generali sul C/C++* : https://www.cplusplus.com/

*GSL-GNU Scientific Library* : https://www.gnu.org/software/gsl/

*GNU Manuals Online* : https://www.gnu.org/manual/manual.html

*Fast Fourier Transform* : https://www.gnu.org/software/gsl/doc/html/fft.html

*Random Numbers Generator* : https://www.gnu.org/software/gsl/doc/html/rng.html?highlight=random


# La Bibbia dell'Assembly
*Comandi in Assembly che potrebbero servirci*

sudo apt-get install nameprog   Per installare programmi nuovi

gcc -o file.out file.c -lgsl -lgslcblas -lm   Per compilare i file che ci servono

./file.out    Per eseguire i file compilati
