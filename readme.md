Speed, Acceleration and Deceleration
I find a lot of people out there chasing crazy acceleration numbers with their 3d printers (particularly the core XY crew) and find this a little bonkers.
Whilst acceleration will genuinely reduce your print time, it seems to have become a focus and we are not all looking at the big picture.

So this little article is my meager attempt to encourage people to think about the whole thing!!

The speed that you can print at is dependent on how much filament you can flow, the acceleration you can achieve, the decceleration you can achieve, the weight of your tool head and how it affects your input shaping results, and cooling!
Unless all of these are balanced, you're leaving performance on the table.

You can have the ability to accelerate at crazy levels, but unless you can control decceleration, cooling, and vibration in the toolhead, it will have limited effect.
Most CoreXY printers will deccel at 50% of acceleration, this means the control is not up to muster and will cause a longer print time. By fine tuning deceleration, you will reduce your print times.

The caveat to this is that if you can apply very high accelerations and are beyond what your input shaper results recommend as optimal to infill, and your exruder / hotend can keep up, you can gain substantial time here.

Unless you can cool the printed plastic appropriately, you will need to slow down.
If your tool head is heavy, your input shaper results will be lower accelerations

And there is no point to be able to accelerate like crazy unless you can push the plastic because ultimately a lesser flow will result in diminishing returns on the higher accelerations.

Much beyond 5000 mm/s/s is pointless unless you can push 30mm2 a second. If you look at the graphs, you will see that there is a big difference in accel times and ultimately deccel times as well when you jump from 1000mm/s/s to 5000mm/s/s however once you jump up to 20000mm/s/s that return is less than 10% gain at 30mm2

Jump to 50000mm/s/s and its even less again. 
Unless you start pushing 40-45mm2, those accels don't really help, they may only save you a couple of seconds on your print job.

To optimise this, you need to look at the kinematic design of your printer. This is where printers like the Annex K3 excel.  The kinematic and structural design allow for very very agressive accel's and decel's, and the Sherpa Mini/Micro is a great little extruder that is under estimated more often than not. Combine a Sherpa extruder with the Bondtec RIDGA V2 gear and an LDO 17mm pancake motor and you will have a solid extruder that will push well for almost all hotends, very few exceptions in this case.  

Incidently, the Sherpa series of extruders would be the only extruder that I would recommend the LDO 17mm pancake and thats because of the efficency of those extruders and lack of bind.  Everything else needs the LDO 20mm pancake or better.
