# Michelson-Interferometer–Based Optical Spectrum Analyzer (OSA) Simulation

This project simulates a Optical Spectrum Analyzer (OSA) using a Michelson interferometer model. It generates interferograms for single- and multi-line optical sources, adds noise, applies apodization and zero-filling, and recovers the optical spectrum using FFT.

---

##  Features
- Michelson-interferometer interferogram simulation  
- Single-line and multi-line optical source support  
- Gaussian shot noise + electronic noise model  
- Apodization (Hanning) in OPD domain  
- Zero-filling (ZFF) for denser spectral sampling  
- FFT-based spectrum recovery  
- Multi-scan averaging for improved SNR  
- True vs. recovered spectrum comparison  
- Automatic plotting and figure saving  

## How It Works
A Michelson interferometer creates interference fringes as the mirror changes the Optical Path Difference (OPD).  
- Each wavelength produces a unique fringe frequency.  
- Multiple wavelengths combine to form a complex interferogram.  
- Applying an FFT converts these frequencies back into wavelengths.  

This is the basic principle behind Fourier-transform OSAs.

##  Requirements
This project requires:

- **Python 3.8+**
- **NumPy**
- **Matplotlib**
- (Optional) **Jupyter Notebook** for running the `.ipynb` file


## Contents
- Simulation of MI-OSA -- Main Notebook


