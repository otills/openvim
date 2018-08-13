### Parts list

OpenVIM is modular and can be used with a large variety of different parts. This page details the parts that have been used succesfully with OpenVIM. The biggest limitation/consideration with parts is that the necessary MicroManager drivers are available [Micro-Manager supported hardware](https://micro-manager.org/wiki/Device_Support).


#### Lenses
* [Keyence VHZ20R](https://www.keyence.co.uk/products/microscope/digital-microscope/vhx-1000/models/vh-z20r/index.jsp) - Extremely high depth of field lens, excellent for low magnification imaging of aquatic embryos, 20-200 X digital magnification.
* [Keyence VHZ100R](https://www.keyence.com/products/microscope/digital-microscope/vh_lens/models/vh-z100r/index.jsp) - High depth of field 100 - 1000 X digital magnification lens)
* [Keyence VHZ500R](https://www.keyence.co.uk/products/microscope/digital-microscope/vhx-6000/models/vh-z500r/index.jsp) - 500 - 5000 X digital magnification, good for imaging Protozoa.
* [Optem zooming lens](http://www.qioptiq.com/optem-micro-12-5.html) - Highly modular lens system with a wide range of magnification using combinations of auxillary lenses and TV tubes.

#### Lighting
* [CCS LDR2-42-SW2](https://www.ccs-grp.com/products/series/1) - An angled 42 mm OD LED ring light for focussed dark field lighting
* [Keyence CA-DRW4F](https://www.keyence.com/products/vision/vision-sys/ca-d/models/ca-drw4f/index.jsp) - A non-focussed 43 mm OD LED ring light.
* [Schott EasyLED gooseneck lights](https://www.schott.com/lightingimaging/english/microscopy/products/easyled/spotlights.html) - A useful lighting apparatus for imaging different types of speciment, although less suited to repeatable lighting.

#### Motorised stages
* [Marzhauser SCAN IM 130 x 85](https://www.marzhauser.com/en/products/microscope-stages/motorized-microscope-stages/scan-series/scan-im.html) - The Marzhauser Scan Tango XY stage is a very reliable and robust stage with very good technical and MicroManager support
* Prior Optiscan stage - a cost effective stage with platform independant MicroManager support
* Inverted Prior Optiscan stage - good for samples requiring high magnification to reduce the distance from sample to lens - used with VHZ500R lens.

#### Cameras
* Allied Vision Technologies Pike 421B - an excellent camera for darkfield imaging, used with dc1394b FW800 connection. Great MicroManager support owing to new developments with the IIDC driver. Allows custom ROI, recording of full 14 bits and precise manipulation of frame rates via control over packet size. Image capture time is recorded with high precision.
* Allied Vision Technologies Pike 421C. As above, but colour model.
* Allied Vision Technologies Pike 210C. A lower resolution model of the above.
* The Imaging Source - various models used.
* QImaging Retiga - a good USB 3.0 camera with excellent image quality.

#### Incubation chambers
* Oko-lab Cryo Boldline - allows heating and cooling of samples in multiwell plates, with humidification (to reduce evaporation) and excellent data logging facilities. Can also be used with gas mixing modules, including combined mixing of nitrogen, oxygen and carbon dioxide.
* Oko-lab electrically heated chamber - allows heating of sample within multiwell plates together with data logging and humidification.

[Return to main OpenVIM page](README.md)
