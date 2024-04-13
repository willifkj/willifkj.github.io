---
title: "Phone Bike Mount"
excerpt: "Top-down modeled mount made with PLA"
header:
  image: /assets/img/Bike Phone Mount v45.png
  teaser: /assets/img/Vertical Phone.jpg
gallery:
  - image_path: /assets/img/Side Phone.jpg
  - image_path: /assets/img/Horizontal Phone.jpg
  - image_path: /assets/img/Vertical Phone.jpg
---

## Introduction to Multi-Material Prints

Print-in-place parts represent an innovative approach to manufacturing, wherein multiple components are seamlessly integrated and printed together, resulting in immediate functionality upon completion of the print. This technique offers significant advantages in terms of efficiency and convenience, eliminating the need for assembly of individual parts post-printing. However, achieving optimal functionality in print-in-place designs necessitates careful consideration of material selection, particularly in relation to factors such as surface energies, chemical composition, shrinkage, cooling rates, and mechanical compatibility. 

Commonly paired materials, such as PLA and TPU, PLA and PVA, and ABS and HIPS, demonstrate the importance of selecting compatible materials to ensure proper bonding and structural integrity. This nuanced understanding of material properties forms the foundation for successful print-in-place projects.

In the realm of additive manufacturing, the design and production of multi-material pliers serve as a compelling example of this design process. These pliers feature a rigid handle and trigger mechanism seamlessly integrated with elastic jaws, constructed to grip and pick up through-hole resistors effortlessly upon the completion of printing. Such intricate assemblies underscore the significance of material compatibility and precise engineering in achieving functional and reliable print-in-place components.

Beyond the realm of pliers, print-in-place technology finds diverse applications across various industries. In the medical sector, for instance, prosthetics benefit from the seamless integration of components, enhancing comfort and usability for patients. Additionally, in the field of soft robotics, the ability to print both soft and hard materials within a single design enables the creation of versatile and adaptable robotic systems.


### Application: Pliers Design

In the context of designing pliers, a strategic blend of materials is employed to optimize functionality and durability. The inherent flexibility of TPU material is harnessed to imbue the jaws with elasticity, while PLA serves as the foundation for rigid components such as the handle and trigger. This configuration ensures that forces applied to the handle are efficiently transmitted to the jaws, facilitating effective gripping action. The jaws themselves function as spring elements, reverting to their original position when the trigger is released.

To enhance the connection between the flexible jaws and the rigid components, a form-fit dove-tail mechanism is utilized. This design feature not only promotes flexibility at the junction points on the handle but also balances the overall assembly's flexibility with durability. To validate the design's structural integrity, a finite element analysis (FEA) is conducted using ANSYS software. The analysis confirms a comfortable safety factor for fatigue loading, as depicted in the accompanying gif. The simulation reveals that the pliers can endure repeated use for up to 1e9 cycles without failure, ensuring long-term durability.


<div style="text-align:center">
    <img src="/assets/img/Safety_Factor_loop.gif" alt="FEA Analysis" loop="infinite" />
</div>  



Considering ergonomic factors, a minimum applied force during operation is around 0.15 pounds, well below the average grip strength of an adult (approximately 50 pounds). This design consideration ensures ease of use for the trigger finger, enhancing user experience and usability.

Prior to arriving at the final design iteration, an earlier version faced usability challenges. Although it functioned similarly, its smaller size caused discomfort and cramping for average users. Subsequent adjustments in the final design address these ergonomic concerns, resulting in a more user-friendly and comfortable handling experience.

### Specifications  

The mechanical component under consideration is characterized by several key specifications, each essential for understanding its functionality and potential applications. First and foremost, the inner jaw angle of the device is precisely set at 30 degrees. This angle delineates the relationship between the inner surfaces of the jaws, dictating how objects will be gripped or secured.

Further defining the device's capabilities is its jaw capacity, which stands at 16.881 millimeters. This measurement signifies the maximum width or diameter of objects that can be effectively accommodated by the device's jaws. It provides a clear boundary for the size range of objects the device is designed to handle securely.

Complementing the jaw capacity is the jaw length, which extends to 32.611 millimeters. This dimension denotes the distance along the inner surface of the jaw from its tip to its base or pivot point. It illustrates the reach or depth to which the jaws can securely grasp objects, offering insights into the device's operational range.

Armed with this information, users can better comprehend how to employ the device in various tasks and environments, maximizing its utility and performance.

### Print Settings

In preparing the print settings for 3D printed pliers, meticulous attention is paid to ensure optimal performance and structural integrity. The G-code, the essential set of instructions for the 3D printer, is meticulously formatted for the MakerGear M3 Dual Extrusion system, taking into account the utilization of two distinct filaments: TPU and PLA. This dual-extrusion setup enables the creation of complex, multi-material designs with precision and accuracy.

To provide robust support throughout the printing process, support structures are enabled universally, ensuring the stability and fidelity of intricate features. Meanwhile, the infill is set to 20%, striking a balance between material conservation and structural strength.

For the pliers' construction, specific parameters are defined to achieve the desired durability and functionality. Three top and bottom shells, each with a thickness of 0.6 millimeters, contribute to the overall resilience of the tool. Additionally, four vertical shells with a thickness of 1.077 millimeters each reinforce the sides, enhancing their rigidity and longevity.

Furthermore, the filament settings for each material are meticulously calibrated to optimize printing outcomes. For PLA, the recommended bed temperature is set to 60 degrees Celsius to facilitate adhesion and prevent warping. The starting layer is extruded at a temperature of 215 degrees Celsius, ensuring proper bonding and layer adhesion, while subsequent layers are printed at 210 degrees Celsius for consistency and stability.

On the other hand, TPU filament demands slightly different parameters to achieve optimal results. Similarly, a bed temperature of 60 degrees Celsius is maintained to promote adhesion and minimize distortion. However, due to the unique properties of TPU, the starting layer is extruded at a higher temperature of 235 degrees Celsius, ensuring proper flow and adhesion. Subsequent layers are then printed at 225 degrees Celsius to maintain flexibility while maintaining structural integrity.

In essence, the comprehensive print settings for 3D printed pliers encompass a meticulous balance of parameters tailored to each filament type, ensuring exceptional performance, durability, and reliability in the final product.

---

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ead3830d86d8c2851?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Phone Bike Mount Gallery" %}
