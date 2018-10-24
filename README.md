The purpose of this repository is to provide measured test data for silicon photonic devices and circuits, specifically with the aim of understanding manufacturing variability and its impact on device and circuit performance.

Motivation: 
Silicon photonics is a technology that can integrate a large number of optical functions on a chip using the fabrication technology of the CMOS industry, thereby enabling low cost, large volume, manufacturing. A unique feature of silicon photonics is its high refractive index contrast, which allows for small components and densely packed optical circuits.  However, the high refractive index contrast imposes very stringent requirements on the dimensional control in the fabrication of silicon photonic circuits, as nanometer-scale variations in waveguide core width or thickness have a significant impact on the individual devices and on the overall performance of a circuit, thereby affecting the yield.

The paper by Bogaerts and Chrostowski, ["Silicon Photonics Circuit Design: Methods, Tools and Challenges"](publications/LPR2018-Wim-Design/2018_LPR_Bogaerts.pdf) discusses how variability affects circuits, how it can be included in the device and circuit models, and how it can be addressed during the design.

The paper ["Impact of Fabrication Non-Uniformity on Chip-Scale Silicon Photonic Integrated Circuits"](publications/OFC2014-LukasC-variability/2014_OFC_lukasc.pdf) presents measurement results of 371 identical resonators on a 16x9 mm chip fabricated by IME, Singapore. The analysis reveals a strong linear correlation between the physical distance between devices and the variability in the ring resonators' wavelength mismatch.

The paper by Zeqin Lu et al., ["Performance prediction for silicon photonics integrated circuits with layout-dependent correlated manufacturing variability"](publications/OE2017-Zeqin-MC/2017_OE_MonteCarlo.pdf), describes an implementation of a Monte Carlo (MC) simulation methodology to predict the impacts of layout-dependent correlated manufacturing variations on the performance of photonics integrated circuits. It is based on similar ring resonators as the above paper, and a method of extracting physical parameters (thickness, width) from the spectra is presented. Using the proposed methodology, we characterized the manufacturing variability of a 200-mm-wafer fabricated by a 248-nm DUV lithography process through IME’s silicon photonics foundry. A total number of 2074 identical racetrack resonators were fabricated on 34 lithography dies on the wafer.


