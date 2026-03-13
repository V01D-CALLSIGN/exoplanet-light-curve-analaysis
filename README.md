# Exoplanet Transit Detection with Kepler Data

I used data from NASA’s Kepler telescope and Python to detect a tiny drop in a star’s brightness caused by a planet passing in front of it, confirming the transit of the exoplanet Kepler-10b and estimating its size.

This project analyzes photometric data from the Kepler Space Telescope to detect the transit of the exoplanet **Kepler-10b**.

Using Python and the Lightkurve library, the Kepler light curve was cleaned, processed, and phase-folded to reveal the periodic dip in brightness caused by the planet passing in front of its host star.

## Result

The phase-folded light curve reveals a clear transit signal.  
From the measured transit depth (~0.00015), the planet-to-star radius ratio is:

$$
\frac{R_p}{R_*} \approx 0.012
$$

This means **Kepler-10b’s radius is about 1.2% of its host star’s radius**, consistent with it being an Earth-sized rocky exoplanet.

## Notebook

The full analysis is contained in the Jupyter notebook:

`exoplanet_lightcurve_project.ipynb`

The notebook includes:
- Data retrieval from the Kepler archive
- Light curve cleaning and preprocessing
- Trend removal and normalization
- Phase folding and transit detection
- Estimation of the planet-to-star radius ratio

## Tools Used

- Python
- Google Colab
- Lightkurve
- NumPy
- Matplotlib

---

© 2026 Aarush Bagchi
