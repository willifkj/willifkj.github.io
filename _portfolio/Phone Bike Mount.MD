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

## Introduction to Top-down modeling

Print-in-place parts represent an innovative approach to manufacturing, wherein multiple components are seamlessly integrated and printed together, resulting in immediate functionality upon completion of the print. This technique offers significant advantages in terms of efficiency and convenience, eliminating the need for assembly of individual parts post-printing. However, achieving optimal functionality in print-in-place designs necessitates careful consideration of material selection, particularly in relation to factors such as surface energies, chemical composition, shrinkage, cooling rates, and mechanical compatibility. 

Commonly paired materials, such as PLA and TPU, PLA and PVA, and ABS and HIPS, demonstrate the importance of selecting compatible materials to ensure proper bonding and structural integrity. This nuanced understanding of material properties forms the foundation for successful print-in-place projects.

In the realm of additive manufacturing, the design and production of multi-material pliers serve as a compelling example of this design process. These pliers feature a rigid handle and trigger mechanism seamlessly integrated with elastic jaws, constructed to grip and pick up through-hole resistors effortlessly upon the completion of printing. Such intricate assemblies underscore the significance of material compatibility and precise engineering in achieving functional and reliable print-in-place components.

Beyond the realm of pliers, print-in-place technology finds diverse applications across various industries. In the medical sector, for instance, prosthetics benefit from the seamless integration of components, enhancing comfort and usability for patients. Additionally, in the field of soft robotics, the ability to print both soft and hard materials within a single design enables the creation of versatile and adaptable robotic systems.


### Application: Design Constraints

In the context of designing pliers, a strategic blend of materials is employed to optimize functionality and durability. The inherent flexibility of TPU material is harnessed to imbue the jaws with elasticity, while PLA serves as the foundation for rigid components such as the handle and trigger. This configuration ensures that forces applied to the handle are efficiently transmitted to the jaws, facilitating effective gripping action. The jaws themselves function as spring elements, reverting to their original position when the trigger is released.

To enhance the connection between the flexible jaws and the rigid components, a form-fit dove-tail mechanism is utilized. This design feature not only promotes flexibility at the junction points on the handle but also balances the overall assembly's flexibility with durability. To validate the design's structural integrity, a finite element analysis (FEA) is conducted using ANSYS software. The analysis confirms a comfortable safety factor for fatigue loading, as depicted in the accompanying gif. The simulation reveals that the pliers can endure repeated use for up to 1e9 cycles without failure, ensuring long-term durability.

### Assembly instructions


---

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ead3830d86d8c2851?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Phone Bike Mount Gallery" %}
