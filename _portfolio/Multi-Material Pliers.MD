---
title: "Multi-Material Pliers"
excerpt: "Multi-Material Pliers made leveraging a multi-material printer loaded with PLA and TPU"
header:
  image: /assets/img/Pilers v23.png
  teaser: /assets/img/Pliers Final.jpg
gallery:
  - image_path: /assets/img/Pliers Prototype.jpg
  - image_path: /assets/img/Pliers Iterations.jpg
  - image_path: /assets/img/Pliers Final.jpg
---


## Introduction to Multi-Material Prints

Microfluidic devices, often referred to as uFluidic devices, are miniaturized platforms designed to manipulate small volumes of fluids at the microscale level. These devices offer numerous advantages over conventional macroscale systems, including reduced sample and reagent consumption, rapid analysis, precise control, and potential for integration with other technologies. 

### Application: Pliers Design

One essential application of microfluidic devices is achieving homogeneous mixing, where two or more fluids are thoroughly blended to create a uniform solution. Homogeneous mixing is crucial in various fields such as analytical chemistry, biomedical diagnostics, drug discovery, and chemical synthesis.

For instance, in biomedical diagnostics, accurate mixing of biological samples with reagents is necessary for conducting assays, detecting biomarkers, and analyzing biochemical reactions. Similarly, in chemical synthesis, homogeneous mixing ensures uniform distribution of reactants, leading to consistent product quality and yield.



<div style="text-align:center">
    <img src="/assets/img/Safety_Factor.gif" alt="FEA Analysis" />
</div>

### Specifications  

The mechanical component under consideration is characterized by several key specifications, each essential for understanding its functionality and potential applications. First and foremost, the inner jaw angle of the device is precisely set at 30 degrees. This angle delineates the relationship between the inner surfaces of the jaws, dictating how objects will be gripped or secured.

Further defining the device's capabilities is its jaw capacity, which stands at 16.881 millimeters. This measurement signifies the maximum width or diameter of objects that can be effectively accommodated by the device's jaws. It provides a clear boundary for the size range of objects the device is designed to handle securely.

Complementing the jaw capacity is the jaw length, which extends to 32.611 millimeters. This dimension denotes the distance along the inner surface of the jaw from its tip to its base or pivot point. It illustrates the reach or depth to which the jaws can securely grasp objects, offering insights into the device's operational range.

Together, these specifications paint a comprehensive picture of the device's capabilities and limitations. The 30-degree inner jaw angle suggests optimized gripping at a specific orientation, while the specified jaw capacity and length provide boundaries for the size and depth of objects the device can effectively handle. Armed with this information, users can better comprehend how to employ the device in various tasks and environments, maximizing its utility and performance.

### Print Settings

In preparing the print settings for 3D printed pliers, meticulous attention is paid to ensure optimal performance and structural integrity. The G-code, the essential set of instructions for the 3D printer, is meticulously formatted for the MakerGear M3 Dual Extrusion system, taking into account the utilization of two distinct filaments: TPU and PLA. This dual-extrusion setup enables the creation of complex, multi-material designs with precision and accuracy.

To provide robust support throughout the printing process, support structures are enabled universally, ensuring the stability and fidelity of intricate features. Meanwhile, the infill is set to 20%, striking a balance between material conservation and structural strength.

For the pliers' construction, specific parameters are defined to achieve the desired durability and functionality. Three top and bottom shells, each with a thickness of 0.6 millimeters, contribute to the overall resilience of the tool. Additionally, four vertical shells with a thickness of 1.077 millimeters each reinforce the sides, enhancing their rigidity and longevity.

Furthermore, the filament settings for each material are meticulously calibrated to optimize printing outcomes. For PLA, the recommended bed temperature is set to 60 degrees Celsius to facilitate adhesion and prevent warping. The starting layer is extruded at a temperature of 215 degrees Celsius, ensuring proper bonding and layer adhesion, while subsequent layers are printed at 210 degrees Celsius for consistency and stability.

On the other hand, TPU filament demands slightly different parameters to achieve optimal results. Similarly, a bed temperature of 60 degrees Celsius is maintained to promote adhesion and minimize distortion. However, due to the unique properties of TPU, the starting layer is extruded at a higher temperature of 235 degrees Celsius, ensuring proper flow and adhesion. Subsequent layers are then printed at 225 degrees Celsius to maintain flexibility while maintaining structural integrity.

In summary, the comprehensive print settings for 3D printed pliers encompass a meticulous balance of parameters tailored to each filament type, ensuring exceptional performance, durability, and reliability in the final product.


### Conclusion

In summary, while microfluidic devices offer unparalleled advantages in fluid manipulation, achieving homogeneous mixing remains a key challenge. Overcoming these challenges requires innovative design strategies, such as the incorporation of active mixing mechanisms, surface modifications to mitigate surface effects, and optimization of flow conditions. Despite the difficulties, addressing the issue of homogeneous mixing in microfluidics is crucial for unlocking the full potential of these devices in various applications.


<div style="text-align:center">
    <img src="/assets/img/Pliers - Made with Clipchamp (1).gif" alt="Pliers in Action" />
</div>


# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e2f2a4595556ebb0d?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Multi-Material Pliers Gallery" %}

