# 3DVolumeVerification
A real-world project for measuring volume through displacement of water.

This project is aimed at middle and secondary school students.  When the curriculum reaches the chapter on volume, there is often a footnote along the lines of:

"The volume of an object can be measure by submersing it water and seeing how much water was displaced."

It turns out to be difficult to "see how much water was displaced."  Most techniques that are discussed or taught have uncomfortably large error margins.

This project creates a setup that is accessible (i.e. low-cost with publicly available materials) and accurate to less than 5%.  It does not require special skills for students to measure the volume.

The two major categories of measuring displaced water are:
 - direct sighting of gradation marking along a container
 - capturing spilled water and measuring it.

Naked-eye readings of graduated cylinders have problem that the vessel needs to have a tight fit aroud the object to get accurate reading of how many mm the water level rose.  If the object has a wide footprint, the vessel opening must be larger, making every mm of water level represent more volume.

The motivating object for this project is a 1/6 cube square-based pyramid.  With a side length of S mm, the smalles cylinder needed to submerge the pyramid is S/sqrt(2) radius, so every mm of water is S^2/2 * pi * ~= pi/2 S^2 mm^3.  The volume of such a pyramd (with height = 1/2 S) is S^2*(S/2)*(1/3) = S^3/6.  Each mm is pi/2 S^2 / (s^3/6) = 3pi / S as a fraction of the volume.  At S = 90, 1mm is 9.3/90 ~= 1/10. Put another way, even with an unusually large shape for classroom demonstrations (about 10cm on a side, the error is still 10%.  And that assues the reading error is within 1mm, which is optimistic for a graduated cylinder with radius 5cm (usually 1L volume).

So rather than reading markings on a vessel, I decided to go with measuring the water that spills out.

The biggest challenge to "water that spilled out" is setting the container to be "full".  With water tension, there is a wide range of what migh tbe read as "full".
The second challenge is catching the water and measuring it.  Thanks to Anthony, I'm going with a spout for catching in a vessel, and a scale for measuring.
