# Fixed-Rotor-Wankel-Engine
A University Technical Communications course project (individiual) from Spring 2021 attempting to invert the Wankel engine geometry by fixing the triangular rotor in place and having the housing be the moving part.

A Wankel engine exploits the idea that a triangular rotor rotating on an eccentric shaft (the center of the rotor must orbit at a rate three times that of the rotor's rotation rate) traces a peanut shaped path that can be made into a housing and used to generate power like a traditional internal combustion engine. In this project I explore inverting this concept, inspired by LiquidPiston's work, which involves a very similar approach.


![A visual comparison of the basic geometry of a Wankel engine (left) and the new geometry (right) where the central red shape is stationary, the blue component is a single moving part, and the black component bounds the space required for the rotor to move freely.](/Pictures/Wankel%20vs%20Fixed%20Rotor.PNG)

In the above image, The basic geometry of the Wankel engine is on the left, where the red central shaft and black housing are fixed parts and the red triangular rotor orbits freely within the interior space of the housing. The new geometry on the right represents the basic geometry of both my design and the LiquidPiston design. The red component in the center is fixed while the blue peanut rotor orbits within the black housing. The difference between the LiquidPiston geometry and mine is that in the LiquidPiston design, combustion only occurs in the space between the rotor and the housing, with the red component absent,  while in my design, combustion occurs between the red component and the blue rotor, and the outer housing is absent from my design.


![The front view of my stator design, the core of the engine.](/Pictures/v2_0_2_Stator%20Assembly%20front%20side.PNG)

The front view of my stator design, the core of the engine. The 6-tooth gear is probably not the best of choices (30 teeth would likely be more sensible), but it was an artistic decision. The eccentric shaft slots in from the back of the stator and is held in place by the back plate that is fixed to the stator.


![The back view of my stator design.](/Pictures/v2_0_2_Stator%20Assembly%20back%20side.PNG)

The back view of my stator design. The screw holes for the back plate are visible. The apparent gear at the back of the back plate is not actually a gear but is my conception of a part that permits the engine to be mounted to a test rig. However, it occurs to me now that unless it is welded to the rig, it is not a satisfactory mounting point. Oh well.


![The front view of my housing design with the intake port visible.](/Pictures/Housing%20Assembly%20intake%20side_ver3.PNG)

The front view of my housing design. As you can see, the housing closes over the stator with an intake port on the front plate and an exhaust port on the back plate.


![The back view of my housing design with the exhaust port and 4-tooth gear visible.](/Pictures/Housing%20Assembly%20exhaust%20side_ver3.PNG)

The back view of my housing design. Visible here is the 4-tooth gear fixed to the front plate (20 teeth would likely have been preferable to go along with a 30-tooth gear replacing the 6-tooth gear on the stator) that attaches to the eccentric shaft and interfaces with the 6-tooth gear on the stator.


![The front view of my intake and exhaust assembly design with the intake arm, exhaust plate, and exhaust manifolds visible.](/Pictures/Intake%20and%20exhaust%20assembly%20front_ver3.PNG)

The front view of my intake and exhaust assembly design. At the front is the intake arm that connects to the intake port. The rear has the exhaust plate (with the first attempt at slots for face seals) and the three exhaust manifolds.


![The back view of my housing design with the exhaust port visible.](/Pictures/Intake%20and%20exhaust%20assembly%20front_ver3.PNG)

The back view of my intake and exhaust assembly design. This shows how the exhaust plate interfaces with the stator assmebly, making the exhaust palte a fixed component. The exhaust manifolds attach to the exhaust plate via the screw holes.

![The front view of the full assembly.](/Pictures/Engine%20intake%20side_ver3.PNG)

The front view of the full assembly. Still missing in the design are some slots for seals, the seals themselves, any lubrication of the seals, spark plugs, and fuel injection. If the design were to include these things, the oil, fuel, and electricity could flow into the stator through the back of the engine.


![The back view of the full assembly.](/Pictures/Engine%20exhaust%20side_ver3.PNG)

The back view of the full assembly.

Originally, I wanted to have the intake and exhaust ports both be present on the front side of the engine so the rear could be open for all of the connections for fuel, oil, and electricity. But I couldn't figure out how to have both the intake and exhaust arms at the front of the engine without them intersecting eachother. Eventually, I solved this problem.

The stator design remained virtually the same, but the rest of the design changed.

![The front view of housing design v2.0.2 with the intake and exhaust ports visible.](/Pictures/v2_0_2_Housing%20Assembly%20front%20side.PNG)

The front view of housing design v2.0.2 with the main difference being the movement of the exhaust port from the back plate to the front plate. Don't ask what versions 2.0.0 and 2.0.1 were, I don't remember and I don't seem to have the files anymore. Oops. But they must have been only slightly different.


![The back view of housing design v2.0.2.](/Pictures/v2_0_2_Housing%20Assembly%20back%20side.PNG)

The back view of housing design v2.0.2, looking largely the same as the old housing design.


![The front view of the concentric shaft design.](/Pictures/Concentric_Shaft_Front.PNG)

This part (front view shown) is the key to design v2. I call it the concentric shaft. The intake air flows in through the central channel while the exhaust flows out through the outer channel. The intermediary channel is there to insulate the intake air from the exhaust and cold air can be pushed through the intermediary channel easilym, as it is open at both ends, shown in the following picture.


![The back view of the concentric shaft design.](/Pictures/Concentric_Shaft_Back.PNG)

The back view shows the second opening of the intermediary channel clearly. The holey sections of the shaft allow continuous flow between the concentric shaft and the intake and exhaust arms visible in the next picture. Note: The three holes at the back end of the shaft are screw holes to attach to the eccentic shaft protruding from the front plate of the housing. They should not permit flow of air.


![The front view of intake and exhaust assmebly v2.0.2.](/Pictures/v2_0_2_Intake%20and%20exhaust%20assembly%20front.PNG)

The front view of intake and exhaust assembly v2.0.2. The exhaust intake arms are both shown, and it is apparent how they both interface with the concentric shaft.


![The back view of intake and exhaust assmebly v2.0.2.](/Pictures/v2_0_2_Intake%20and%20exhaust%20assembly%20back.PNG)

The back view of intake and exhaust assembly v2.0.2. The geometry of the exhaust and intake arms is more clear from this angle.


![The front view of full assembly v2.0.2.](/Pictures/Engine%20intake%20side_ver3.PNG)

The front view of the full assembly. Still missing the same sealing, lubrication, ignition, and injection design components as before, but the need for the exhaust plate has been completely eliminated, opening ample space for oil, fuel, and electricity to be piped into the stator through the back of the engine (the hole in the back plate of the housing would need to be widened a bit, but there's ample space for that too).


![The back view of full assembly v2.0.2.](/Pictures/Engine%20exhaust%20side_ver3.PNG)

The back view of the full assembly. This clearly shows the space I mentioned that could be opened up here if the hole in the back plate of the housing were to be widened, Giving direct access to the back of the stator.
