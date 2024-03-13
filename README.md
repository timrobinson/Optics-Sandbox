This repository is an eclectic collection of optics, colorimetry, and image processing scripts written over the years.  Each targeted different projects, but I anticipate using/modifying these for future activities.

**Project 1**

This script models surface scattering properties assuming a collimated light source.  It assumes that a surface may be broken up in small segments, and that each segment is randomly assigned a slope.  The slopes are restricted by a gaussian distribution.  A surface roughness parameter may be adjusted by changing the distributions standard deviation.  The input parameters are (a) angle of incident, and (b) roughness parameter.  The graphic below shows the output of the script as the surface roughness is changed from smoothest (left) to rough (right).

![Scattering](https://github.com/timrobinson/Optics-Sandbox/assets/15863043/f9ba2309-8f5c-473b-b0d9-52961320f137)

**Project 2**

This script is based on a project conducted on Hawaii (big island).  A little over a decade ago, there was a push to change street lights from sodium lamps to LEDs.  This push concerned University of Hawaii astonomers who felt that LEDs would increase light pollution that interferes with the optical telescopes on top of Mauna Kea.  More to the point, the street lights of old used low pressure sodium (LPS) lamps.  The spectral output of LPS lamps is ideal for astronomy as the only significant emission is a sodium line at 589 nm.  This emission is naturally part of our upper atmosphere from meteorite events, hence filters are already in place to block light pollution at this wavelength.  In contrast, the common dominant technology used(uses) 5000K CCT white LEDs.  This technology emits significant blue emission from the InGaN LED semiconductor.  Blue light notoriously scatters in the upper atmosphere, frustrating astronomical observation within the blue band.  If these white LEDs replaced LPS lamps, Mauna Kea would suffer from excessive light pollution.

Human factors concerns are another aspect of this discussion.  The color emitted from the replacement lamps should be significantly different than traffic light signals.  The rationale - a driver should not confuse a cautionary traffic light signal with a street light.  In addition, emergency responders should be able to have enough color rendering to judge certain colors.  The script in this repository addresses this latter concern by modeling how we would perceive a MacBeth Color Checker when illuminated with various lamps.  The first graphic contrasts typical daylight with an High Pressure Sodium (HPS) lamp.  The second graphic expands this contrast with multiple lamps.  



![MacBeth Color Checker](https://github.com/timrobinson/Optics-Sandbox/assets/15863043/5a394d86-5416-49cd-8851-524b6a848592)


![chromatic_adaption](https://github.com/timrobinson/Optics-Sandbox/assets/15863043/31f4c7f9-8797-49d5-8165-3bee1e7b652c)


