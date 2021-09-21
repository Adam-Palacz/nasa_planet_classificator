# nasa_planet_classificator

Dense neural networks predicting planet type with 98% accuracy

DATA:
* Temperature -- K 
* L -- L/Lo 
* R -- R/Ro 
* AM -- Mv
* Color -- General Color of Spectrum
* Spectral_Class -- O,B,A,F,G,K,M / SMASS - https://en.wikipedia.org/wiki/Asteroid_spectral_types \
* Type -- Red Dwarf, Brown Dwarf, White Dwarf, Main Sequence , Super Giants, Hyper Giants 

MATH: 
* Lo = 3.828 x 10^26 Watts \
(Avg Luminosity of Sun)
* Ro = 6.9551 x 10^8 m \
(Avg Radius of Sun)

Type:
* Red Dwarf - 0
* Brown Dwarf - 1
* White Dwarf - 2
* Main Sequence - 3
* Super Giants - 4
* Hyper Giants - 5

Dataset:
https://www.kaggle.com/brsdincer/star-type-classification
