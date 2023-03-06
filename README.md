# Bubble pump

## Introduction
The bubble pump is a variant on the air-lift principle. When air is blown in a pipe or hose (under water) rising bubbles will force water upwards. Typically an air-lift pump will operate more efficiently when the inlet is placed deeper under water. The air will have to be more pressurised when the inlet is located further under the water surface. Therefore, when the bubbles rise up they will expand more and accelerate the rising water. This increases the pump capacity and efficiency. A variant of the air-lift pump operating at higher pressure is the geyser pump; here larger bubbles are created using a siphon principle. A chamber is filled with pressurized air, effectively displacing water until the deepest part of a siphon is exposed and the air chamber content is released suddenly in large bubble. Because of the high pressure, the bubble may carry a larger volume of water, again because it expands on its way up in the pump pipe or hose.

Our bubble pump is a poor man's version of the geyser pump. It is designed to be used with relatively small and cheap electrical air pumps that can be operated by simple and cheap solar panels. Typically the maximum air pressure difference these pumps can produce is 0.3\[bar\]. And therefore we cannot place our bubble pump much deeper than approximately 2 meters below the water surface. However, by design we make it easy to tune the size of the air bubble chamber such that you can optimize the pump for the depth of the water source (well or otherwise). The geyser effect will be negligible and the output not too high, but the main idea of this pump is that it may provide a small but steady stream of water. The supply can be either applied directly (e.g. irrigation, feeding life stock, etc) or stored for later use (e.g. a pond or storage tank).

## Materials
For the pump housing we use a PVC tube with a diameter of approx. 32\[mm\]. This should be small enough to fit in a fairly narrow borehole. *Note: these are outer diameters.* Length of this tube shall be at least 40\[cm\]. Wall thickness shall be less than 3\[mm\], otherwise the pump dimensions will not fit.

Both the pump and siphon shall be 3D-printed in PETG. Measure the inner diameter of the PVC tube, and use it as basis in the parameterised model of the pump in **pump-par.FCStd**.

Pump and siphon are connected using PE tubing with outer diameter of 8\[mm\] and preferably a wall thickness of approx. 1\[mm\]. Measure the diameter and use it in the parameterised models of both the pump **pump-par.FCStd** and siphon **siphon-par.FCStd**. 

## Printing
Export the FreeCAD model in STL or AFM format and use your favourate rendering engine to create GCODE for your printer. Do not print supports, but when using a recent version of Cura it is a good idea to use the ``Make Overhang Printable`` option. This should result in a much nicer 'roof' of the cavity inside both the pump and the siphon.

## Construction
As mentioned above, the outer shell of the pump shall be made from a PVC tube of approx. 40\[cm\] long and minimal 32\[mm\] wide. Internally, for the siphon we will need a few pieces of 8\[mm\] PE tubing. Cut pieces of approx. 10, 20 and 30\[cm\]. The shorter ones for the siphon and the longest for the lifting tube. (See the accompanying photos.)

## Tips and tricks
Use a 12V rated air pump in combination with a 6V PV-panel. The pump will not run the fastest, but increase its life time (i.e. the rubber seals inside the pump will last a lot longer).

## Installation
The ideal depth for the pump is somewhere between 1 and 2\[m\] below the water surface. This type of small airpumps have a maximum rating of 0.3\[bar\], so placing the pump deeper is no use. And closer to the surface makes it more difficult for the oscillating process of the siphon to start up.

## Credits
The WOT in general, and Menno-Jan in particular.
