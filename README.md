# Fast-Fourier-Transform

Core points of the program:

- Random numbers generator (Gaussian);

- Converting a general Audiofile.ext to Number_file.dat

- Adding a gaussian noise and saving Number_file.dat (1° column times, 2° column Amplitude)

- FFT of the real input signal (in halfcomplex representation)

- Saving a file with frequencies (1° column) and the modules of Fourier coefficients (2° column)

- Filtering the halfcomplex signal

- Saving the results in 2 files (1 for frequency domain and 1 for time domain)

- Plots of the 4 files

Mancano:

-breve power point esplicativo


# Useful Adresses

*General notes on C/C++* : https://www.cplusplus.com/

*GSL-GNU Scientific Library* : https://www.gnu.org/software/gsl/

*GNU Manuals Online* : https://www.gnu.org/manual/manual.html

*Fast Fourier Transform* : https://www.gnu.org/software/gsl/doc/html/fft.html

*Random Numbers Generator* : https://www.gnu.org/software/gsl/doc/html/rng.html?highlight=random


# Assembly

sudo apt-get install ffmpeg (To install ffmpeg)

gcc -o file.out file.c -lgsl -lgslcblas -lm   (For compiling)

