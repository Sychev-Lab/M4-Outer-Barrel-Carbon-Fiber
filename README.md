# Fabrication of a Custom Outer Barrel for Airsoft M4 in Carbon Fiber

![Presentation image side view](/content/IMG_9243.HEIC.jpg)
![Presentation image overlap tubes](/content/IMG_9242.HEIC.jpg)

# Table of Contents
1. [Introduction and Design Considerations](#1-introduction-and-design-considerations)
2. [Modeling and Mold Creation](#2-modeling-and-mold-creation)
3. [Material Calculation and Resin Application](#3-material-calculation-and-resin-application)
4. [PLA+ Parts Printing](#4-pla-parts-printing)
5. [Parts Preparation](#5-parts-preparation)
6. [Waxing](#6-waxing)
7. [Resin and Carbon Layers](#7-resin-and-carbon-layers)
8. [Assembly and Curing](#8-assembly-and-curing)
9. [Carbon Tube Selection and Tools](#9-carbon-tube-selection-and-tools)
10. [Tube Cutting and Fitting](#10-tube-cutting-and-fitting)
11. [Final Assembly](#11-final-assembly)
12. [Testing and Adjustments](#12-testing-and-adjustments)
13. [Conclusions](#13-conclusions)

---

## 1. Introduction and Design Considerations

This manual details the process of fabricating a custom outer barrel for an Airsoft M4 using carbon fiber. It will address the challenges and solutions for specific components such as the threaded tip, the internal component, and the tube length.

![General image](/content/image_1736195279192_0.png)

First, we will focus on the tip where the suppressor will be placed, a critical element with a counter-clockwise thread. The difficulty lies in the impossibility of milling the part to create the thread, as it must withstand some pressure and wear from inserting and removing the suppressor. We will experiment with creating the thread directly with the press, carefully evaluating the result and durability.

Additional reinforcement is considered, possibly with the incorporation of miniature taper screws.

Secondly, we will address a complex internal component that fits into the upper body of the replica. This piece secures the tube to the RIS and allows the insertion of the hop-up. Its manufacturing is complex due to the protrusions and variable dimensions.

Finally, the tube will have a variable length requiring precise cutting according to needs.

## 2. Modeling & Mold Creation

3D modeling and subsequent printing allow us to create prototypes and molds precisely.

The process of creating the mold for the suppressor tip consists of building a model with a base, cap, pin, centering pins, and a locking washer. The final shape will be cubic to ensure precise molding.

![Point](/content/image_1736195635219_0.png)

## 3. Material Calculation & Resin Application

By analyzing the volume of the modeled part, we calculate the necessary amount of carbon fiber and epoxy resin. A mixture of ***60%*** carbon and ***40%*** resin is recommended, rounding the quantities for optimal results.

In the modeling program, by assigning properties to the piece, the volume is obtained in cubic millimeters `(mm^3)`.

![image.png](/content/image_1736195659340_0.png)

**The conversion formula is:**

```
grams = cubic millimeters × 0.001 therefore: X mm^3 / 1000
The tip has 3034.008mm^3 / 1000 = 3.034008g (grams)
```

This is the final weight of the piece. To calculate the amount of carbon and resin, we will use the following formulas:


```
percentage * quantity / 100
60% * 3.034g = 1.8204g (carbon)
40% * 3.034g = 1.21g (resin)
```

Usually, a little more is used, rounding the quantities and considering that the excess resin will come out of the mold.

## 4. Printing PLA+ Parts

We will use PLA+ to print the models due to its ease of printing and handling.

My printer is an Ender 3 Pro with Klipper, which will become a Voron Switch in the future.

We set the layers to `0.15mm` with Linear Advance to achieve a print quality similar to normal but in less time. The process takes approximately 4 hours for the tip and 8 hours for the internal part.

I recommend leaving the printing overnight to have the parts ready the next day. I prefer to print the parts separately to perform measurement checks and detect possible errors.

In the model design, we consider a margin of ***0.20mm*** between the joining pieces and also consider how the excess resin will be evacuated.

## 5. Part Preparation

Before starting the process, we make sure to meticulously prepare the parts. To do this, we carefully sand the interior surfaces, removing any artifacts or defects. This stage is crucial, as any imperfection will be reflected in the final finish.

We also conduct thorough testing to ensure that the parts fit smoothly and without problems, avoiding any jamming during assembly.

## 6. Waxing

To facilitate removal and achieve a smooth surface, we apply wax both inside and outside the mold. Inside, we will use manual wax application, as it will leave the surface smoother and the 3D printing layers will not show through, while a spray is used outside to remove excess resin remnants.

## 7. Resin & Carbon Layering

We apply a first layer of resin with a special brush, making sure to cover every corner of the parts. Then, carefully and precisely, we place pieces of carbon cloth over the resin. This process is meticulously repeated until all parts are fully impregnated.

In the case of the lid, we apply a generous amount of resin and then add an even layer of carbon.

## 8. Assembly & Curing

Once all the parts are prepared, we assemble them and carefully wrap them with plastic wrap. To ensure a perfect bond, we use a clamp to apply pressure evenly in all areas. During this step, it is normal for a little resin to protrude.

After completing the entire process, we let the parts sit for approximately 12 hours for the resin and carbon to harden (not completely), ensuring the structural integrity of the parts and allowing them to be removed from the mold without problems. The pieces must cure for another 12 hours to reach their final hardness.

<video src="/content/rendition.m3u8_1736195937051_0.mp4-hevc-q28.mp4" controls preload></video>

## 9. Carbon Tube Selection & Tools

Choosing the right tube for the project is crucial. We generally opt for prefabricated tubes of `50cm` in length. In this case, we bought a tube with dimensions of `18x16x500mm` and one of `32mm` in diameter for a reasonable price of approximately `10€`, including shipping, from the following website: [Purchase Link](https://es.aliexpress.com/item/1005004139982617.html?spm=a2g0o.order_detail.order_detail_item.5.488a39d3IQXEao&gatewayAdapt=glo2esp)

Before starting the cutting, make sure you have the right tools. You can opt for a traditional saw, although carbon does not cut easily with this method. The most recommended option is to use a rotary tool like a Dremel. Personally, I use a **Teccpo** model that comes with an extension cord.

![image.png](/content/image_1736195989372_0.png)

![image.png](/content/image_1736195995987_0.png)

![image.png](/content/image_1736196006220_0.png)

## 10. Cutting the Tube with a Dremel

To make precise, clean cuts in the carbon tube, I designed a holder that securely holds the tube and allows it to rotate for straight cuts. The Dremel's extension cord connects to the main handle, and the tube is held in place by clips. At the base of the holder, there are four wheels that facilitate the rotation of the tube for precise and clean cuts.

![image.png](/content/image_1736196016462_0.png)

![image.png](/content/image_1736196021933_0.png)

![image.png](/content/image_1736196026756_0.png)

## 11. Cutting Results & Video

Once you have cut the tube to your specifications, be sure to check the edges to ensure they are smooth and chip-free.

In the following video, I have documented the cutting process using the Dremel and the designed holder, which will give you a clear picture of how to perform this crucial step in creating your own M4 stock.

Video of how it is cut:

<video src="/content/rendition.m3u8-cutting.mp4" preload controls></video>

## 12. Sanding and Joining Parts

We begin the sanding process using grid-type sandpaper with 80 and 240 grit to ensure a smooth and uniform finish on the parts. We chose not to increase the grit of the sandpaper, as this texture is ideal for facilitating adhesion between parts during assembly.

To protect the visible areas and avoid accidental scratches, we carefully cover the parts with special attention to detail.

To join the parts, we use a highly effective two-component epoxy glue. We prepare the correct mixture and apply it precisely to the joints. The advantage of this glue lies in its rapid hardening process, which takes less than a minute, ensuring a solid and durable bond between the parts.

This meticulous approach to the sanding and assembly process allows us to achieve high-quality results and ensure the structural integrity of each part. Each step is performed with care and precision to ensure a flawless and durable final product.

<video src="/content/3rendition.m3u8_1736196251750_0.mp4" controls preload></video>

## 13. Tube Support & Hop-Up Bracket Mold (Optional)

The tube support and hop-up bracket are critical and complex components in its manufacture. This is the third version of the mold, and I will soon share a more updated version in future posts. This mold is composed of four main parts and two internal parts, one of which is discarded and the other is retained for processing.

The manufacturing method follows the same basic process we apply to other parts: first, we carefully sand the surfaces to ensure a smooth finish; then, we apply a layer of wax to facilitate mold release. Next, we join the mold pieces together. In this particular case, we fasten them together using screws. To prevent the formation of bubbles or other defects during casting, we apply plasteline to the joints. This plasteline not only prevents imperfections but also protects the screws during the process.

This meticulous approach to manufacturing ensures that each component is of the highest quality, with no visual or structural defects. Every step, from sanding to imperfection protection, is carefully performed to achieve an exceptional final product.

---


# Tools

* Dremel
* Gloves
* Particle mask
* Protective goggles

# Costs

Assuming we have basic tools such as a Dremel, drill, sandpaper, 3D printer, etc...

| Material | Unit | Cost |
|--|--|--|
|[Carbon Tube](https://es.aliexpress.com/item/1005004139982617.html?spm=a2g0o.order_detail.order_detail_item.5.488a39d3IQXEao&gatewayAdapt=glo2esp)|1|9.05€ with (-20%)|
|[Aluminum Adapter 12mm CW to 14mm CCW]()| 1 | 0.92€ |
|[Right Hand Thread Tap HSS](https://es.aliexpress.com/item/4000712624358.html?spm=a2g0o.order_list.order_list_main.88.7d85194d3GhdmP&gatewayAdapt=glo2esp)|1|3.37€|
| ***TOTAL*** | 3 | ***13.34€*** |

## Models and Files

The models are paid and you can find them here: [Cults3D](https://cults3d.com/es/modelo-3d/juegos/diy-outer-barrel-airsoft-m4-aeg)

### FAQ

- ***Why are they paid for?***
    - _I have taken time to write this article, I have spent time printing and testing parts to give you everything ready..._

---

## Conclusion

This manual has guided you through the process of creating a custom carbon fiber outer barrel for an Airsoft M4, from design and modeling to cutting, assembly, and finishing. By following these steps and paying attention to detail, you can create a high-quality, personalized component for your replica. Remember that safety and precision are paramount throughout the process. We encourage you to try this project and experience the satisfaction of creating your own custom parts.