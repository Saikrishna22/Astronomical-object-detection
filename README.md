# Astronomy-object-detection
### Classifying Astronomical objects using SDSS - DR16 Data

---
### Data:
SDSS - DR16 :
	The Sloan Digital Sky Survey or SDSS is a major multi-spectral imaging and spectroscopic redshift survey using a dedicated 2.5-m wide-angle optical telescope at Apache Point Observatory in New Mexico, United States. 




---

### Variables description:

* objid = Object Identifier
* ra = J2000 Right Ascension (r-band)
* dec = J2000 Declination (r-band)
* u = u-band
* g = g-band
* r = r-band
* i = i-band
* z = z-band
* run = Run Number
* rerun = Rerun Number
* camcol = Camera column
* field = Field number
* specobjid = Object Identifier
* class = object class (galaxy, star or quasar object)
* redshift = Final Redshift
* plate = plate number
* mjd = MJD of observation
* fiberid = fiberID

---
### Results
| Model  | Accuracy(testing) |
| ------------- | ------------- |
| Logistic regression  | 97.8  |
| Logistic regression(grid-cv)  | 98.12  |
| Decision tree | 98.8 |
| Random forest | 99.1 |
| Random forest(grid-cv) | 99.6  |
