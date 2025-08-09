---
title: "Aegis Coffee"
author: "Abdelrahman El Nabawy Mohamed El nabawy Essa"
description: "Four-chamber air purification unit using coffee grounds and real-time sensors to combat urban air pollution."
created_at: "26/06/2025"
---

## Total Time Spent on the Project: **56 hours**

---

##  26/6 – 8 hours  
I started the project by sketching the core concept: a four-chamber airflow system designed to filter air using coffee grounds alongside other neutralizing agents like NH₃ and ZnCl₂. My goal was to design a flow where each chamber played a unique role in purifying the air. I researched different filtration methods that could work well with coffee grounds, ensuring they could be paired effectively with chemical neutralizers. By the end of the day, I had outlined a functional flow diagram for the entire process and chosen the Raspberry Pi 5 with a compatible HAT to manage multiple sensors and I/O control, setting the foundation for the system’s brain.

---

##  27/6 – 8 hours  
With the concept in place, I moved into CAD modeling using Fusion 360. I began shaping the external enclosure, creating chamber cutouts and defining airflow paths. This included positioning spaces for fans, filters, and chemical scrubber holders. I made sure to add placeholders for sensors and internal wiring channels, keeping the design flexible for future adjustments. Running basic airflow simulations revealed a few bottlenecks, so I fine-tuned the internal channel diameters to ensure optimal flow.

![3D chamber layout view](https://github.com/user-attachments/assets/ef9eadab-762e-4900-b1c3-6e378450600c)

---

##  28/6 – 7 hours  
I spent the day refining the CAD model further. The focus was on integrating mount points for the Raspberry Pi and fans within a waterproof housing. I designed slots for the LCD display and access points for the external power switch, making the system user-friendly. By the end of the day, I generated the first rendered image of the complete 3D unit. To better visualize its proportions, I produced a simple, non-functional scale model using a basic print—mainly to check sizing rather than test function.

![Rendered 3D prototype](https://github.com/user-attachments/assets/eaa4ae09-3925-4c99-942b-1ccf35015177)

---

##  29/6 – 6 hours  
The focus shifted to planning the wiring layout based on the sensor positions inside the CAD model. I experimented virtually with servo placements to manage air diversion between chambers. I also explored how the Raspberry Pi GPIO pins could interface with the chosen servo valve, ensuring the design could realistically handle control signals without overloading the system.

---

##  30/6 – 8 hours  
I finalized the CAD model, preparing it for documentation and potential fabrication. I produced exploded views and section diagrams to clearly show internal components and their relationships. I also created custom sensor mounting clips in the model, ensuring they would stay secure during operation. With the structure completed, I exported the design files in STL and DXF formats, ready for future manufacturing.

---

##  1/7 – 8 hours  
This day was dedicated to studying the chemical interaction processes in the third chamber. I simulated different inner surface treatments to optimize reaction efficiency, focusing on how ammonia and coffee grounds interact under varying airflow conditions. During this process, I derived two equations to quantify and ensure the efficiency of the chosen activation method. I also integrated brackets for coffee grounds and ZnCl₂ filters directly into the chamber design, adding sealed zones to safely contain ammonia vapors. All of these details were recorded in my design notes for later use.

Drived equations:

<img width="202" height="77" alt="image" src="https://github.com/user-attachments/assets/fb5d9718-93ff-45f6-b741-8829c7d9e3af" />
<img width="169" height="58" alt="image" src="https://github.com/user-attachments/assets/1ca88970-fa49-4b7b-8591-298b06b47eb0" />

---

##  2/7 – 7 hours  
I created a high-resolution render of the complete model for inclusion in the project’s README file. The full assembly layout was finalized, with details such as fasteners and cable glands integrated into the design. I cross-checked every part in the Bill of Materials against the CAD design to confirm that nothing had been overlooked.

![3D model chamber breakdown](https://github.com/user-attachments/assets/0908067a-cf6b-4a80-9dc8-595c39d0903e)

---

##  3/7 – 4 hours  
The last day of work focused on gathering and finalizing all documentation. I compiled the Bill of Materials (BOM), README, and this journal into their final form, attaching all relevant images and diagrams. I uploaded rendered images, screenshots, and the wiring diagram to the GitHub repository. I then went through a thorough formatting and proofreading session, testing every link to ensure the project files met the submission requirements without missing details.

Estimated results of the project:

<img width="250" height="118" alt="image" src="https://github.com/user-attachments/assets/fca738cf-9325-492b-beca-efd66e5ac718" />

---
