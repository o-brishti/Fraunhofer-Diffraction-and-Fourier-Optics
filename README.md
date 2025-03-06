# Fraunhofer Diffraction with Fourier Transforms
  
This project deals with the Applications of Fourier Transforms in different diffraction patterns. By simulating different aperture shapes (single slit, double slit, multi-slit, circular and other arbitrary shapes), we visualize how light interacts with obstacles, producing characteristic diffraction patterns.  

## Files to Open  
- **`fourier-optics.ipynb`** – The main Jupyter Notebook containing the mathematical derivation for single slit diffraction from FT and visualizations of various other patterns such as:
  
![N slit grating](https://raw.githubusercontent.com/o-brishti/Fraunhofer-Diffraction-and-Fourier-Optics/main/images/pattern1.png)

![single slit](https://raw.githubusercontent.com/o-brishti/Fraunhofer-Diffraction-and-Fourier-Optics/main/images/pattern2.png)

![double slit](https://raw.githubusercontent.com/o-brishti/Fraunhofer-Diffraction-and-Fourier-Optics/main/images/pattern3.png)

![circular aperture](https://raw.githubusercontent.com/o-brishti/Fraunhofer-Diffraction-and-Fourier-Optics/main/images/pattern4.png)


## Some Notes on the Implementations: 

In this diffraction simulation, wavelength is not explicitly specified because the code demonstrates diffraction patterns in a normalized, dimensionless space. The simulation uses the mathematical relationship between an aperture and its far-field diffraction pattern through the Fourier transform, which preserves the essential features of diffraction patterns without requiring physical units. The diffraction pattern in the far field is essentially the Fourier transform of the aperture function. The Fourier transform preserves the essential pattern regardless of absolute scale. The simulation shows the correct shape of the diffraction pattern without needing absolute measurements.

After the FFT, we're in a normalized spatial frequency domain where the pattern depends only on the relative dimensions of the aperture, not absolute physical measurements.

In a real-world scenario where you needed to predict the exact angular position of diffraction features, you would need to incorporate:

- The physical wavelength of light (λ)
- The actual dimensions of the aperture
- The distance to the observation screen


