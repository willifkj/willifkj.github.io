---
title: "Multi-Material Pliers"
excerpt: "Multi-Material Pliers made leveraging a multi-material printer loaded with PLA and TPU"
header:
  image: /assets/img/Pilers v23.jpg
  teaser: /assets/img/Pliers Final.jpg
gallery:
  - image_path: /assets/img/Pliers Prototype.jpg
  - image_path: /assets/img/Pliers Iterations.jpg
  - image_path: /assets/img/Pliers Final.jpg
  - image_path: /assets/img/Final_Mixing_Device.jpg
---


## Introduction to Microfluidic Devices

Microfluidic devices, often referred to as uFluidic devices, are miniaturized platforms designed to manipulate small volumes of fluids at the microscale level. These devices offer numerous advantages over conventional macroscale systems, including reduced sample and reagent consumption, rapid analysis, precise control, and potential for integration with other technologies. 

### Application: Homogeneous Mixing

One essential application of microfluidic devices is achieving homogeneous mixing, where two or more fluids are thoroughly blended to create a uniform solution. Homogeneous mixing is crucial in various fields such as analytical chemistry, biomedical diagnostics, drug discovery, and chemical synthesis.

For instance, in biomedical diagnostics, accurate mixing of biological samples with reagents is necessary for conducting assays, detecting biomarkers, and analyzing biochemical reactions. Similarly, in chemical synthesis, homogeneous mixing ensures uniform distribution of reactants, leading to consistent product quality and yield.

### Challenges in uFluidic Mixing

Despite the advantages of microfluidic devices, achieving homogeneous mixing poses significant challenges. The primary obstacles include:

1. **Low Reynolds Number Regime**: Microfluidic systems typically operate in the low Reynolds number regime, where viscous forces dominate over inertial forces. In this regime, fluid flow is characterized by laminar behavior, hindering spontaneous mixing.

2. **Limited Diffusion**: Diffusion, the primary mechanism for molecular transport in microfluidic channels, is slow compared to turbulent mixing in macroscale systems. Consequently, achieving rapid and efficient mixing solely through diffusion is challenging.

3. **Surface Effects**: Interactions between fluids and channel surfaces, such as capillary action, can lead to non-uniform flow profiles and hinder mixing efficiency.

### Conclusion

In summary, while microfluidic devices offer unparalleled advantages in fluid manipulation, achieving homogeneous mixing remains a key challenge. Overcoming these challenges requires innovative design strategies, such as the incorporation of active mixing mechanisms, surface modifications to mitigate surface effects, and optimization of flow conditions. Despite the difficulties, addressing the issue of homogeneous mixing in microfluidics is crucial for unlocking the full potential of these devices in various applications.
# Mixing Sections

## Section A:

In my design, a serpentine microstructure featuring strategically placed ridges was crafted to harness a chaotic mixing phenomenon. This microstructure, with a substantial cross-sectional area measuring 705.101 mm<sup>2</sup>, serves as the bedrock for enhancing mixing efficiency within the chip. 

### Serpentine Channels and Elongated Pathways

The serpentine pattern, with its winding and channels, effectively elongates the travel path of fluids traversing through the chip. This elongation not only prolongs the interaction time between the fluids but also promotes intimate mixing by ensuring thorough contact between the two substances. 

### Harnessing Chaotic Advection

Moreover, the inclusion of ridges in the serpentine channels plays a pivotal role in intensifying the chaotic advection within the chip. These protrusions act as disruptors, perturbing the fluid flow and inducing turbulence at critical junctures. As a result, the fluids experience enhanced intermingling, leading to accelerated mixing rates.

### Synergistic Effects and Mixing Performance

The culmination of these design elements is showcased in the accompanying video, where the synergistic effect of prolonged travel path and heightened chaotic advection becomes evident. By the conclusion of the third serpentine section, the once-distinct fluids seamlessly blend into a homogeneous mixture, underscoring the remarkable mixing performance facilitated by the mic

## Section B:

In my partner's approach, she replaced ridges with strategically positioned waves within the serpentine microstructure to exploit chaotic mixing phenomena. This intricate design serves as the cornerstone for optimizing mixing efficiency within the microfluidic chip.

### Serpentine Channels and Elongated Pathways

The serpentine pattern, characterized by its sinuous and undulating channels, effectively elongates the travel path of fluids navigating through the chip. This elongation not only extends the interaction time between the fluid streams but also fosters intimate mixing by facilitating comprehensive contact between the constituent substances.

### Harnessing Chaotic Advection

The incorporation of waves within the serpentine channels replaces conventional ridges to intensify chaotic advection within the microfluidic chip. These wave-like structures act as dynamic disruptors, introducing irregularities in fluid flow and inducing turbulence at strategic points along the microchannels. Consequently, the fluid streams experience heightened intermingling, leading to accelerated rates of mixing.

### Synergistic Effects and Mixing Performance

The culmination of these design elements is vividly demonstrated in the accompanying video, showcasing the synergistic interplay between prolonged travel paths and amplified chaotic advection. By the conclusion of the first serpentine section, the once-discrete fluid streams seamlessly blend into a homogeneous mixture, underscoring the exceptional mixing performance facilitated by the innovative microstructure.

In essence, the incorporation of waves within the serpentine microstructure represents a novel approach to enhancing mixing efficiency in microfluidic devices, offering promising avenues for applications in various fields such as analytical chemistry, biomedical diagnostics, and chemical synthesis.

# Mold to Final Device

1. **Design and 3D Printing**:
   - Utilize CAD software to design the desired microfluidic mold.
   - Convert the design into STL files suitable for 3D printing.
   - Employ a Form 3 SLA printer (Formlabs) to fabricate the mold using the appropriate resin (e.g., Grey, Clear, Black, or High Temp resin).

2. **Print and Cure Mold**:
   - Print the designed mold using the Form 3 SLA printer, ensuring accurate layer deposition.
   - After printing, cure the mold to ensure structural integrity and stability, utilizing the Formlabs UV cure.

3. **Parylene Deposition**:
   - Transfer the cured mold to a Labcoter PDS 2010 parylene deposition machine (Specialty Coating Systems).
   - Follow the manufacturer's instructions to coat the mold with parylene-C, utilizing 2 grams of parylene-C for each print.
   - Automate all other parameters using the Labcoter for consistent and uniform coating.

4. **Casting PDMS**:
   - Prepare a mixture of polydimethylsiloxane (PDMS) elastomer and curing agent at a weight ratio of 10 : 1.
   - Pour the PDMS mixture onto the parylene-coated mold, ensuring even distribution across all features of the mold.
   - Degas the PDMS mixture in a vacuum chamber for 30 minutes to remove trapped air bubbles.
   - Cure the PDMS in an oven at 80 °C for 3 hours to achieve proper crosslinking and solidification.

5. **Plasma Bond Glass Slide**:
   - Clean a glass coverslip thoroughly to remove any contaminants.
   - Utilize a PlasmaFlo PDC-FMG plasma cleaner to activate the surfaces of both the PDMS device and the glass coverslip.
   - Align the PDMS device with the glass coverslip, ensuring proper registration of features.
   - Use gentle pressure to facilitate bonding between the activated surfaces.
   - If the device is intended for cell culture, sterilize it using gamma irradiation with the specified dose.
   - Otherwise, sterilize the device in an autoclave prior to use.

By following these meticulous steps, you can successfully transform the 3D printed mold into the final microfluidic device, ready for various applications in research and diagnostics.

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e4215c017f367074f?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Multi-Material Pliers Gallery" %}

The video is available here: [link](https://drive.google.com/file/d/1XxTrSjvDsOyE1e8hy618UqlehHPXQZp9/view?usp=sharing).

