# CNN-Concrete-Crack-Detectionion--

Crack detection in concrete is an important issue because it is one of the main materials used in civil infrastructure. Cracks first appear on the surface of the concrete structure under load and are a sign of further destruction. In concrete structures, the presence of discontinuities affects their consistency to a large extent. Cracks and seams are among these discontinuities. Structural damage of economic concrete in structures is called damage failure, which has raised many concerns in engineering. When the concrete cracks appear, the steel quickly hardens, so this stage is considered as a symbol of the end of useful life and a golden time to repair the damaged tissue. The subject of the thesis is prediction and detection of cracks on structures using convolutional neural network. Crack detection becomes a very challenging task due to the inhomogeneous intensity of cracks and the complexity of the background, for example, low contrast with the surrounding pavement and possible highly similar shadows. 
![crack_detection_positive](https://github.com/RoshaSoft/CNN-Concrete-Crack-Detectionion--/assets/85801966/59966bb6-702e-4d99-aad0-99cd8c720670)

![crack_detection_negative](https://github.com/RoshaSoft/CNN-Concrete-Crack-Detectionion--/assets/85801966/d1946aa4-22dc-41f8-9bf6-ff5bd0c04138)

![pfga_vs_cpu](https://github.com/RoshaSoft/CNN-Concrete-Crack-Detectionion--/assets/85801966/b88f8b7c-7e76-4baf-ba23-3dbaa6429dcd)

![FPGA_Colab](https://github.com/RoshaSoft/CNN-Concrete-Crack-Detectionion--/assets/85801966/10fe6bbc-71be-486d-a1d5-8bff93280882)

A supervised convolutional neural network is trained to classify each image patch in the collected images. Using Python libraries1, multiple layers of convolutional neural network in Google environment2 and data sets with 20,000 images collected from Bank3 are used for crack detection. Finally, the important part is the implementation of the complex neural network model (convolutional) on the 4FPGA processor, using the installation of the measured drivers, and the result is checked with the 5CPU, GPU6 processors of the performance and limitations7. This research makes a convolution code that is able to generate code for GPU and FPGA. Another task of this research is to simplify the use of high-performance FPGA by 1TSIM for programming, the generator does not require hardware knowledge to provide a high-performance accelerator at the software level. Our tests show a 55x speedup for GPU runtime and a 25x speedup for FPGA.
[https://data.mendeley.com/datasets/5y9wdsg2zt/2

![crack_detection_fpga](https://github.com/RoshaSoft/CNN-Concrete-Crack-Detectionion--/assets/85801966/111af850-d1e5-402e-be8b-a74798ad05a8)

![concrete_crack_detection](https://github.com/RoshaSoft/CNN-Concrete-Crack-Detectionion--/assets/85801966/d166fbbd-7173-4098-b94f-a8e65f6ee6e6)

![crack_detection](https://github.com/RoshaSoft/CNN-Concrete-Crack-Detectionion--/assets/85801966/a36f5089-d7bd-4198-aa59-777fd0f07036)
Introduction
Effective and timely identification of cracks in structures is essential for proper repair and limiting any further damage. To date, most crack detection methods follow a manual inspection approach as opposed to image-based automatic detection, which makes the overall method expensive and time-consuming. In this study, an automatic structural crack detection analysis system based on CNN deep learning framework is proposed. This system is obtained using 20,000 images.
The results of the simulation

Like anything else, FPGA has its pros and cons. FPGA is a method of designing and implementing logic and digital circuits that is used for manufacturing chips, prototyping or for industrial and advanced applications. Using FPGA is more complex and expensive than microcontroller, but it is a much better option for simultaneous and parallel applications. One of the important issues in electronic board design is FPGA, if you intend to do tasks related to parallel processing or distributed systems, you can think in this way.

Speed performance
In this paper, we have compared the optimal implementation of complex image processing algorithm on GPU and FPGA. In both systems, the goal was to achieve a rapid and significant increase, which, of course, we achieved with great efforts. Overall, it can be concluded that both FPGA and GPU systems have important – but different – advantages. While the ultimate flexibility of an FPG-based system can result in faster performance than a GPU-based platform, the effort expended in developing an FPGA implementation of a particular algorithm is completely reduced. In terms of physical space and power consumption, FPGA is definitely the winner. However, the ease of integrating a GPU implementation into a server installation cannot be overlooked.
