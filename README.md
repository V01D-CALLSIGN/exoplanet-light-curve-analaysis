# Exoplanet Transit Detection with Kepler Data

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ipqyS1S3BlXL6XFeoJTtHS4_xK-UOjRN?usp=sharing)

I used data from NASA's Kepler telescope and LightKurve Python library to detect tiny drops in star's brightness caused by a planet passing in front of it. 

This project uses photometric data from Kepler Space Telescope to find the transit of the exoplanet **Kepler-10b**. Using Python and the Lightkurve library, I cleaned the data by removing NaNs, outliers, normalizing the data points, flattening the graph, folding the dips in flux and removing extra noise by binning. The resulting light curve showed the periodic dip in brightness that was caused by Kepler-10b passing infront of Kepler-10. 

I produced a lightcurve that looks like this. 

<img width="791" height="398" alt="image" src="https://github.com/user-attachments/assets/fed0803c-860e-4e61-b5d9-7bc73886209c" />
