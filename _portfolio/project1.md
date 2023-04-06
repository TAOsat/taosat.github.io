---
title: TAOsat update
subtitle: Drone flight of 2022-07-12.
image: assets/img/portfolio/01-full.jpg
alt: Drone Flight

caption:
  title: TAOsat update
  subtitle: Drone flight of 2022-07-12.
  thumbnail: assets/img/portfolio/01-thumbnail.jpg
---
ORION has a TAOsat project group composed of Makhan Virdi, Rob Scott, Dave Rauen, Carl Lyster, and David Fields.  The project is to build a CubeSat, TAOsat, that will detect and record radio astronomy data from above the ionosphere, process the data in orbit, and relay it back to researchers on the ground.

Here’s a summary of our progress:

## Last week’s progress was as follows:

1. Benchtop work got the software organized -- easier to use -- and the flight package ruggidized.  Digital ckt noise was not a problem.
2. Field testing showed the expected drop of 60Hz noise, followed by an unexpected rise of noise to high levels. Trouble was neighbor's electric fence.  Still, between the house and the fence we saw a nice improvement.
   Finding:  We've been relying on Hann windowing to diminish 60 Hz interference, but we should also be using filtering.  The Hann windowing does help since it reduces the 60 Hz sidelobes.  We might find this useful in the TAOsat 3 system if we can apply the windowing and filtering there. 
3. Our Drone flight was Tuesday 2022-07-122.  Thanks to John Bates for piloting.  The left photo shows the 2022-07-12 ascent.  The right photo was taken from the drone on an earlier flight and shows TAOsat 2 as viewed from above.
4. The plot below summarizes the 2022-07-12 flight path.  VLF data averages were stored each 6s of the flight, which ascended to just about 400' AGL.  The VLF flight package was suspended 5m below the drone for this flight.  The launch site was a half-mile from Bull Run power/switching systems, so the 60Hz is rather high.  Additionally, there is noise from a nearby microwave tower.
5. We didn't attain sufficient distance from the 60Hz interference to observe a significant drop, and drone motor noise at 33 kHz was also a problem.   60Hz noise was present in all records.  Drone motor noise was high when the drone was climbing or hovering, but much lower when the drone was descending.  Still, noise problems were much diminished from our previous flight, where switching power supply noise (from a computer monitor) was significant.
   Findings: VLF beacons were visible in most data captures.  With our TAOsat 1 and TAOsat 2 software, noise degraded the FFT amplitude information.  We don't need more drone flights unless improved software filtering suppresses the 60 Hz noise problem or we try at a remote site (TAO, or my house without the neighbor’s electric fence interference).  We can benefit from balloon flights with the type 2 and type3 CPUs.


{:.list-inline}
- Date: January 2017
- Client: Threads
- Category: Illustration

