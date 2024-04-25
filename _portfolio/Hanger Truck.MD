---
title: "Hanger Truck"
excerpt: "Generative SLS Printed Hanger Truck for Electtric Longbroad"
header:
  image: /assets/img/TruckRenderV2.jpg
  teaser: /assets/img/Full_Skate_1.jpg
gallery:
  - image_path: /assets/img/Hanger_1.jpg
  - image_path: /assets/img/Hanger_2.jpg
  - image_path: /assets/img/Hanger_3.jpg
  - image_path: /assets/img/Pulley_1.jpg
  - image_path: /assets/img/Pulley_2.jpg
  - image_path: /assets/img/Full_Skate_1.jpg
  - image_path: /assets/img/Full_Skate_2.jpg 
---

## Introduction to Generative Design

The process of generative design begins with the input of design parameters and constraints, such as material properties, manufacturing methods, and performance requirements. These inputs are then used to generate a set of potential design solutions through iterative computational algorithms. By simulating and evaluating numerous design iterations, generative design can identify the most efficient and effective solutions based on the specified criteria.

While generative design offers significant potential for innovation and optimization, it is important to note that it is not a one-size-fits-all solution. One of the primary limitations of generative design is the substantial computing power required to perform the complex simulations and iterations necessary to explore a wide range of design options. As a result, access to high-performance computing resources, such as cloud-based services, is often necessary to fully leverage the capabilities of generative design.

In the context of the design process above, the computations were conducted in the cloud using the web services of Fusion, highlighting the reliance on external computing resources to support generative design activities. Additionally, it is worth noting that while generative design can be performed using specialized software tools such as ANSYS, manual iteration with a deep understanding of statics and dynamics is also a viable approach to achieving similar results. This underscores the importance of understanding when and how to leverage different design tools and resources effectively, in order to optimize the use of time and computational resources.

In conclusion, generative design represents a powerful approach to design optimization, leveraging computational algorithms to explore a vast design space and identify innovative solutions. However, its effectiveness is contingent on access to substantial computing resources and a nuanced understanding of when and how to apply generative design methods within the broader design process. As such, the successful application of generative design requires a strategic approach that balances computational capabilities, domain knowledge, and resource optimization.



### Application: Aerospace

Generative design has revolutionized aerospace engineering, offering innovative solutions for aircraft and spacecraft design. The aerospace industry has leveraged generative design to optimize components, particularly in thermoplastic composites and composite materials, resulting in lightweight and high-strength parts critical for aerospace applications. Additionally, generative design has facilitated the exploration of complex geometries, addressing challenges related to additive manufacturing, with a focus on creating intricate and organic designs suitable for aerospace applications. Selective Laser Sintering (SLS) and Electron Beam Melting (EBM) have been adopted for the production of components designed using generative design principles. Furthermore, generative design has played a pivotal role in multi-objective optimization within aerospace engineering, enabling the simultaneous consideration of diverse design criteria such as weight reduction, structural integrity, and aerodynamic performance. The aerospace industry has recognized the potential of generative design in achieving optimal structural designs, with a focus on minimum-weight aircraft structural components and the application of optimization methods for aerospace turbopump design. Moreover, generative design has been instrumental in addressing the complex thermodynamic inputs required for aerospace vehicle development. In conclusion, generative design has become an indispensable tool in the aerospace industry, enabling engineers and designers to push the boundaries of innovation and achieve unprecedented levels of performance, efficiency, and reliability in aircraft and spacecraft design.

### Hanger Truck Design

In the context of designing an electric longboard, it is essential to comprehensively understand and address the constraints inherent in its construction. This involves a detailed review of similar-sized longboards to establish relevant benchmarks, such as the maximum weight capacity, which was found to be 220 pounds. Utilizing this benchmark, the determination of the maximum forces acting on the longboard becomes feasible. These forces include a face plate force equivalent to a quarter of the maximum weight, a force along the rotation axis also amounting to a quarter of the maximum weight, and shear forces of 110 N on the wheel axle faces for left and right turns.

In the pursuit of generative design for the electric longboard, it is imperative to identify and define the appropriate design geometries that outline the constraints for the hanger. These physical constraints encompass an 8.2 mm through hole, a bearing interface not exceeding 18 mm, a 73.6 mm pulley gear distance, and an overall footprint of 160 mm x 160 mm x 290 mm. These constraints serve as the foundation for the preserved geometry of the design. Furthermore, considerations for clearance for the motor, pulley gear system, bushing plate, as well as ground and turning clearance for the longboard form the basis of the obstacle geometry. Establishing a starting geometry provides a foundational point for the design, effectively reducing iteration time and maintaining design coherence.

In the process of solving the design challenges, the criteria are set to minimize the mass using an unrestricted manufacturing method. Additionally, the selection of materials, specifically Nylon 12 and ALSi10Mg, is made to explore different final designs based on material strength. The utilization of the unrestricted manufacturing method results in the generation of more organic designs characterized by complex curves and angles, which may pose challenges for conventional manufacturing methods. Powder bed fusion SLS printing emerges as a suitable manufacturing technique for such designs due to its flexibility in accommodating complex geometries and contours. In comparison to filament and resin printing, selective laser sintering (SLS) offers distinct advantages in the fabrication of complex geometries. SLS provides high design flexibility, enabling the creation of intricate and organic designs with complex curves and angles. This capability is particularly valuable as support during the printing process is simply provided by unsintered powder surrounding and holding the structure, allowing for the realization of designs that may be challenging with other 3D printing modalities. Furthermore, SLS is widely used for printing materials in various fields, including aerospace, sports equipment, and biomedical engineering, owing to its ability to produce objects with desired mechanical properties and aesthetic features. The use of SLS for 3D printing also extends to the fabrication of composite materials, polymers, and metals.

However, it is important to note that the organic nature of the design often leads to iterative geometries that are intricate and time-consuming, akin to the complexities encountered in normal CAD design, such as top-down modeling. These changes can be unpredictable and time-consuming due to the underlying computational algorithms, resulting in long turnaround times. Therefore, a comprehensive understanding of the design constraints and the implications of generative design on manufacturing processes is crucial for achieving optimal design outcomes.


---

### Ride Test

<iframe width="560" height="315" src="https://drive.google.com/file/d/1eh_GeUNfMzudUYmtZ_w1nqNFLANqmRYJ/view?usp=sharing" frameborder="0" allowfullscreen></iframe>

# CAD Models

Nylon 12 Hanger Truck
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ebf364e5b8d991a9c?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

ALSi10Mg Hanger Truck
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e630635d3f4952234?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Hanger Truck Gallery" %}
