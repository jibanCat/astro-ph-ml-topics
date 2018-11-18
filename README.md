# astro-ph-ml-topics

Using arxiv API to analysis neural network paper in astro-ph 

- Simple N-grams analysis on abstract
- Try to find the common topics in astro that used neural network.
- Basic scraping function is adapted from TIMHEAD, http://betatim.github.io/posts/analysing-the-arxiv/, with some modifications.

## Basic Information

- Number of total astro-ph papers from arxiv API 2010 - 2018: **234975**
- The ratio of neural net or machine learning papers in astro-ph: **0.00258**
- How many of them are about galaxy: **0.224**

## The Growing Trend of Neural Net and Machine Learning Papers in Astro-ph

![](images/time_line.png)

## Most Mentioned Categories in Astro-ph (limited to neural net and machine learning related papers)

![](images/category.png)

## N-Grams in Astro-ph (limited to neural net and machine learning related papers)

- 1 grams
![](images/1grams.png)

- 2 grams
![](images/2grams.png)

- 3 grams
![](images/3grams.png)

## Topic Modeling on Astro-ph's Abstracts 

A naive with maximum 10 topics, 

- Topic 0 : radio, sources, optical, infrared, observations, source, jet, emission, objects, telescope, images, survey, band, near, detected
- Topic 1 : data, model, using, models, solar, results, analysis, method, parameters, new, used, light, based, time, present
- Topic 2 : field, magnetic, matter, dark, energy, model, scale, cosmological, density, non, large, fields, universe, models, simulations
- Topic 3 : line, emission, lines, alpha, region, velocity, molecular, km, spectra, absorption, regions, high, ii, temperature, observed
- Topic 4 : stars, cluster, clusters, stellar, ngc, dwarf, metallicity, star, galactic, galaxy, abundance, fe, halo, distance, population
- Topic 5 : ray, energy, gamma, emission, flux, 10, spectrum, high, kev, source, spectral, power, observed, thermal, cosmic
- Topic 6 : black, accretion, hole, rm, period, star, neutron, wind, binary, rate, sim, mass, frequency, 10, state
- Topic 7 : galaxies, galaxy, redshift, sample, luminosity, survey, function, correlation, relation, 10, type, evolution, high, mass, local
- Topic 8 : mass, stellar, stars, masses, star, systems, 10, planet, planets, massive, evolution, low, core, simulations, models
- Topic 9 : gas, formation, star, disk, dust, agn, galaxy, rate, galactic, regions, central, stellar, accretion, model, infrared.