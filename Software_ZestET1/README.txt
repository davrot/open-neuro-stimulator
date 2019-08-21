This archive contains the design and source files for our paper. We hope to inspire other developers and give them a starting point for their development. 

However, we expect the users of this collection to know what they are doing. Furthermore, we can not guarantee that everything works as it should or at all. It is up to you to test the design files and source codes before using them yourself. We are not liable for any problems caused by using these files in any way.


If questions arise please send us an email under davrot@neuro.uni-bremen.de.


Files for the Orange Tree Tech ZestET1
======================================

The ZestET1 is a FPGA board made by the company Orange Tree Technologies (http://www.orangetreetech.com).

It contains a Xilinx FPGA and a Gigabit Ethernet TCP/IP offload engine. We used it as computational heart for our base station.
The FPGA requires a firmware as well as software for establishing network communication between an external PC and a ZestET1.

The part of our software tool collection, which was written for programming the FPGA via Ethernet, is an interpretation of the original software from Orange Tree Technologies.

We optimized the software for the use with Linux (Scientific Linux 7.2). However, we also tested it with Windows and it seems to work there too.

Furthermore, the part of the firmware concerning the communication with the Ethernet offload engine was taken from an Orange Tree Tech example file.

We thank Orange Tree Technologies for allowing us to use this information and files in our software and firmware package.


MIT License
===========

Copyright (c) 2014 University of Bremen ZKW<p>
Permission is hereby granted, free of charge, to any person obtaining a copy of this hardware, software, and associated documentation files (the "Product"), to deal in the Product without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Product, and to permit persons to whom the Product is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Product.
THE PRODUCT IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE PRODUCT OR THE USE OR  OTHER DEALINGS IN THE PRODUCT.


