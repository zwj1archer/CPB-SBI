# CPB-superpixel
This apprach is proposed by Dr.ZHOU Wen-jun, it is for background initialization based on CPB+superpixel.

The files includ two parts: 1) CPB; 2) Background Initialization.
For CPB, please check the link: https://github.com/zwj1archer/CPB.git

For Backgroud Initialization by CPB+superpixel:

The code was realized by Dr.ZHOU Wen-jun(zhouwenjun@swpu.edu.cn) in Image Processing and Parallel Computing Laboratory, School of Computer Science, Southwest Petroleum University, China.

This code includes three parts: 1) Superpixel segmentation; 2) Motion mask; 3) Background initialization;

Superpixel segmentation: 'superpixel.m' is for superpixel segmentation by SLIC algorithm;
Motion mask: 'mask.m' is for motion detection from the result of foregound detecion by CPB and combined with  superpixel segmentation;
Background initialization: 'Backgroundinitialization.m' for final background generation by initial model of CPB.


If you need to use it for testing you own algorithm, please feel free to download it.

If you plan to use it in your paper, please tell us in advance.

Thank you.

Jan.1,2020
