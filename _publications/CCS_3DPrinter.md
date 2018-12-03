---
title: '[Leave Your Phone at the Door: Side Channels that Reveal Factory Floor Secrets](http://seclab.illinois.edu/wp-content/uploads/2016/10/CCS_2016___3D_Printer.pdf)'
authors: 'Avesta Hojjati, Anku Adhikari, Katarina Struckmann, Edward J. Chou, Thi Ngoc Tho Nguyen, Kushagra Madan, Marianne S. Winslett, Carl A. Gunter, William P. King'
date: 2016-05-20
teaser: 'CCS_3DPrinter.png'
permalink: /publication/CCS_3DPrinter
collection: publications
---

Abstract
-------
From pencils to commercial aircraft, every man-made object must be designed and manufactured. When it is cheaper or easier to steal a design or a manufacturing process specification than to invent one’s own, the incentive for theft is present. As more and more manufacturing data comes online, incidents of such theft are increasing.
In this paper, we present a side-channel attack on manufacturing equipment that reveals both the form of a product and its manufacturing process, i.e., exactly how it is made. 
In the attack, a human deliberately or accidentally places an attack-enabled phone close to the equipment or makes or receives a phone call on any phone nearby. The phone executing the attack records audio and, optionally, magnetometer data. We present a method of reconstructing the product’s form and manufacturing process from the captured data, based on machine learning, signal processing, and human assistance.

We demonstrate the attack on a 3D printer and a CNC mill, each with its own acoustic signature, and discuss the commonalities in the sensor data captured for these two different machines. We compare the quality of the data captured with a variety of smartphone models. Capturing data from the 3D printer, we reproduce the form and process information of objects previously unknown to the reconstructors. On average, our accuracy is within 1 mm in reconstructing the length of a line segment in a fabricated object’s shape and within 1 degree in determining an angle in a fabricated object’s shape.
