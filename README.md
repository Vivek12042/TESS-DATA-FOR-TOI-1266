TESS Data Collection for TOI-1266

I have collected observational data of TOI-1266 using the Transiting Exoplanet Survey Satellite (TESS) from Sector 76 (2024 observations). The target has TESS Target ID: 467179528.  

To retrieve the data, I used the Lightkurve library in Python. This library facilitates the acquisition and analysis of TESS data, allowing us to work with Target Pixel Files (TPFs).  

Understanding Target Pixel Files (TPFs)

TESS observes stars for extended periods, typically just under a month per sector, capturing their brightness variations over time. However, not all stars within a sector have their full-frame images recorded. Instead, TESS selects specific pixels around targeted stars, creating Target Pixel Files (TPFs).  

By summing the flux from the pixels corresponding to the star, we can construct a light curve, representing the star’s brightness over time. This data is crucial for detecting exoplanets, studying stellar variability, and conducting astrophysical analyses.  

