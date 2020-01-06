# Ariel-Machine-Learning-Training-Module-for-Exoplanets
Create your Machine Learning Neural Network to reduce the noise in exoplanet observations. (Ariel Telescope Data Simulation)
#  

Over 4,000 exoplanets have been discovered by space and ground-based telescopes. There may be billions or even trillions of these exoplanets in our galaxy alone. More space-based telescopes are coming up to accelerate this search for the exoplanets such as the Wide-Field Infrared Survey Telescope (WFIRST), the James Webb Space Telescope (JWST) and the Atmospheric Remote-sensing Infrared Exoplanet Large-survey (ARIEL) Space Mission.

More telescopes mean more opportunities for us to learn about the universe. But telescopes also generate a massive amount of digital data. As we receive this data, we will be eager to get answers to questions in our mind. Did we find new exoplanets? What is the radius and temperature of these planets? What are their atmospheric conditions? Is there water on them? Can we identify bio-signature of life?

To go to these answers, we need to sift through the data and analyze it to extract patterns and other important features. While data about our universe is increasing exponentially, the astronomy community is not. This means we need to rely more on complex algorithms and machine learning models to extract pertinent information from raw data. This may need to be done in almost real-time using massive computing power and developing custom algorithms and machine-learning models.

The Atmospheric Remote-sensing Infrared Exoplanet Large-survey (ARIEL) Space Mission is a European Space Agency (ESA) mission to be launched in 2028. During its 4-year mission, ARIEL will study what exoplanets are made of, how they formed and how they evolve, by surveying a diverse sample of about 1000 extrasolar planets, simultaneously in visible and infrared wavelengths. It is the first mission dedicated to measuring the chemical composition and thermal structures of hundreds of transiting exoplanets, enabling planetary science far beyond the boundaries of the Solar System and put our Solar System in the galactic context.

To find what elements exist in the oberved exoplanet's atmosphere, the telescope will measure the dip in light created by the planet transiting the star in 55 different wavelengths. 

When a planet goes in front or transits its parent star, its main body blocks out some light of the star creating a dip in the light curve. But the atmosphere surrounding the planet around will also absorb some of this light depending on the gas molecules present in the atmosphere. This light is absorbed to different degrees at different wavelengths depending on the different gasses present in the atmosphere. ie the depth of the transit varies for different wavelengths.

![Dip In light varies over different wavelengths](https://github.com/Artash-N/Ariel-Machine-Learning-Training-Module-for-Exoplanets/blob/master/wavelenghts%20lightcurve.png)

But accurately predicting the radius ratio of the exoplanet to the star is a complex task, as there will be noise in the light curve data cause by stellarspots on the star's surface. 

![Stellar Spots interfering with light curve measurment](https://github.com/Artash-N/Ariel-Machine-Learning-Training-Module-for-Exoplanets/blob/master/stellar%20spot%20interference.png)

In this module, you will create a machine learning model that predicts the ratio between the radius of the planet to the radius of the star for every wavelength.

The database we will use contains 148 thousand training examples contaning the observed light curve of exoplanets in 55 different wavelenghts
The participating teams were given a dataset of 147,000 simulated light curves, spread over 55 different wavelengths. For each of the wavelengths, the ratio of the radius of the parent star to the radius of the planet (or the relative radii) was given. The reason the radius of a planet is different over different wavelengths is because of its atmosphere, about which we will talk in the next section.

Another dataset was given: the test database. It consisted of 63,000 simulated light curves, again spread over 55 different wavelengths. The ratio of the radius of the stars to the radius of the planet was not given for this dataset.

The goal of the competition was to accurately predict the relative radii or ratio of the radius of the star to the radius of the planet for each of the light curves in the test database.

#

For more information, please visit : https://hotpoprobot.com/2019/09/15/predicting-exoplanetary-atmosphere-using-machine-learning-the-ariel-data-challenge-2019/   
