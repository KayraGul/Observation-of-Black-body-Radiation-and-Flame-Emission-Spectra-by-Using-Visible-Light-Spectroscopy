# Observation of Black-body Radiation and Flame Emission Spectra of Alkali Metals

**Author:** Yusuf Kayra Gül  
**Affiliation:** Department of Physics, Bilkent University  
**Date:** May 13, 2025  
**Contact:** [kayra.gul@ug.bilkent.edu.tr](mailto:kayra.gul@ug.bilkent.edu.tr)

---

## 🧠 Abstract

This project investigates two key phenomena that demonstrate the quantization of energy: **black-body radiation** and **flame emission spectra** of alkali metals.  
Using a **home-built visible light spectrometer**, the emission spectra of **Li**, **Na**, and **K** were analyzed and compared with theoretical predictions and literature data.  
The experiment successfully confirmed the **shift of Planck’s distribution** with temperature and observed the **quantized emission lines** of alkali metals within a precision of ±5 nm.

---

## 🧪 Experimental Overview

### Apparatus
- Custom-built **visible light spectrometer**
- **Tungsten filament** light bulb (24 W)
- **Bunsen burner**
- **CD surface** used as a reflection diffraction grating (1510 nm groove spacing)
- **Modified webcam** (IR filter removed, 2K resolution)
- **Theremino Spectrometer** software for real-time spectral analysis
- **Python (NumPy, Matplotlib, SciPy)** for data processing and curve fitting

### 🎥 Demonstration Video

[![Spectrometer Demonstration Video](https://img.youtube.com/vi/a2NhYbi8bzY/0.jpg)](https://www.youtube.com/watch?v=a2NhYbi8bzY)

*A short demonstration of the homemade visible-light spectrometer setup and operation.*

### Methods
1. Constructed a light-tight spectrometer with a precision slit formed by razor edges.  
2. Calibrated the spectrometer using **532 nm** and **655 nm** laser lines and validated it with an AMOLED screen spectrum.  
3. Measured the **black-body radiation** of a tungsten filament by varying the applied voltage (10–22 V) and calculating the filament temperature via:
   \[
   T = \left(\frac{P_c}{4.516\times10^{-13}}\right)^{1/4}
   \]
4. Recorded **flame emission spectra** of LiCl, NaCl, and KBr solutions using the same setup.  
5. Compared measured wavelengths with theoretical values from literature tables.

---

## 📊 Results Summary

| Element | Expected Peak (nm) | Measured Peak (nm) | Error (± nm) | Observation |
|----------|-------------------:|-------------------:|--------------:|-------------|
| Li       | 670.784 | 672 | ±2 | Single peak, consistent with theory |
| Na       | 588.995 / 589.592 | 588 | ±2 | Two close peaks merged due to resolution |
| K        | 766.491 / 769.898 | 773 | ±4 | Peaks merged, still consistent |

### Black-body Radiation
- The measured distributions align with **Planck’s law** at low and medium temperatures.  
- As temperature increased, the curve **shifted left** (toward shorter wavelengths) in accordance with **Wien’s displacement law**.  
- Deviations at high temperatures were attributed to **non-ideal emissivity** and **camera sensor limits**.

### Spectra Precision
- Achieved an experimental precision of approximately **±5 nm**, validating the spectrometer’s effectiveness despite low-cost components.

---

## ⚙️ Limitations & Error Sources
- **Webcam sensor limitations** restricted sensitivity at low intensities.
- **CD grating imperfections** caused small wavelength distortions.
- **Light diffuser** reduced brightness and signal-to-noise ratio.
- **Lamp glass absorption** and **self-emission** of tungsten introduced small deviations.

---

## 🧰 Tools & Software

- [Theremino Spectrometer](https://www.theremino.com/en/downloads/automation)  
- [Tracker Video Analysis](https://physlets.org/tracker/)  
- [Python](https://www.python.org/) — with `NumPy`, `Matplotlib`, and `SciPy`  
- [LaTeX](https://www.latex-project.org/) — for report preparation  

---

## 📚 References

1. R. Harris, *Modern Physics*, Pearson Education (2014).  
2. R.H. Petrucci, *General Chemistry*, Pearson (2017), pp. 312–314.  
3. W.G. Schrenk, *Analytical Atomic Spectroscopy*, Springer (1975).  
4. C. Kittel & H. Kroemer, *Thermal Physics*, W.H. Freeman (1980).  
5. E. Hecht, *Optics*, 5th ed., Pearson (2017).  
6. P.W. Atkins, *Physical Chemistry*, W.H. Freeman (1998).  
7. T. Pancheva et al., *Optical Measurements upon Compact Discs in Education of Optoelectronics* (2010).  
8. H.-S. Yeo et al., *Specam: Sensing Surface Color and Material with the Front-facing Camera of a Mobile Device*, *MobileHCI ’17* (2017).  

---

## 👤 Author

**Yusuf Kayra Gül**  
B.S. in Physics, Bilkent University  
📍 Ankara, Turkey  
📧 [kayra.gul@ug.bilkent.edu.tr](mailto:kayra.gul@ug.bilkent.edu.tr)  
🔗 [LinkedIn](https://www.linkedin.com/in/kayra-gul-71641b308) | [YouTube](https://www.youtube.com/@yusufkayragul320)

---
