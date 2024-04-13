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

Top-down 3D modeling is a technique that utilizes the known 3D structure of objects in a scene to estimate depth and structure for new and related 3D components streamlining the design process without the need for constantly measuring physical objects. In addition, the entire assembly lives in one document allowing for easy joint structuring for a complete assembly. When designing the mount, one used the handlebars and a phone model as structures to build from, eliminating measurements for all relative constraints without looking at external data.


### Application: Design Constraints

In the context of designing pliers, a strategic blend of materials is employed to optimize functionality and durability. The inherent flexibility of TPU material is harnessed to imbue the jaws with elasticity, while PLA serves as the foundation for rigid components such as the handle and trigger. This configuration ensures that forces applied to the handle are efficiently transmitted to the jaws, facilitating effective gripping action. The jaws themselves function as spring elements, reverting to their original position when the trigger is released.

To enhance the connection between the flexible jaws and the rigid components, a form-fit dove-tail mechanism is utilized. This design feature not only promotes flexibility at the junction points on the handle but also balances the overall assembly's flexibility with durability. To validate the design's structural integrity, a finite element analysis (FEA) is conducted using ANSYS software. The analysis confirms a comfortable safety factor for fatigue loading, as depicted in the accompanying gif. The simulation reveals that the pliers can endure repeated use for up to 1e9 cycles without failure, ensuring long-term durability.

### Assembly instructions


---

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ead3830d86d8c2851?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Phone Bike Mount Gallery" %}
