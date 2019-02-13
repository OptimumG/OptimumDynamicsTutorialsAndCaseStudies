[Return to Start](1_Tutorial_1.md)

-|-|-|-
[Create Project](2_Create_Project.md)|[Tire Stiffness](3_Tire_Stiffness.md)|[Tire Friction](4_Tire_Friction.md)|[Tire Assembly](5_TireAssy.md)
[Chassis](6_Chassis.md)|[Spring](7_Spring.md)|[Bump Stop](8_BumpStop.md)|[Coilover](9_Coilover.md)
[Anti-Roll Bar](10_ARB.md)|[Linear Suspension](11_LinearSus.md)|[Aerodynamics](12_Aero.md)|[Brakes](13_Brakes.md)
[Differential](14_Diff.md)|[Drivetrain](15_DT.md)|[Powertrain](16_Powertrain.md)|[Gearbox](17_Gearbox.md)
[Introduction to Setup](18_Setupintro.md)|[Creating a Setup](19_Setup.md)|[Validating a Setup](20_ValidateSetup.md)|[Conclusion](21_Conclusion.md)

#Bump Stop

Bump stops are a secondary spring usually intended to prevent the shock piston from bottoming out, causing damage to the vehicle.  They can also be used to control the ride height of a vehicle to much advantage.  To demonstrate how to create import data for a component, we are going to create a non-linear bump stop.

1) To start, open __Microsoft Excel (R)__ to a new worksheet

![Bump Stop Data](../img/bump_stop_data.PNG)

2) Input the following dimensions for displacement and force and save the file as __Tutorial Bump Stop.csv__.

![Bump Stop Import](../img/bump_stop_import.png)

3) Go to the __Bump Stop__ button and select the __Excel or CSV File__ option under __Import__.

![Bump Stop File](../img/import_file.png)

4) Select the file name for the bump stop being used.

![Displacement Button](../img/displacement_bs.png)

5) Click on the (...) to open up the series select tool.

![Displacement Data](../img/displacement_data.png)

6) Click on the column that corresponds to the displacement data. The data being used will be highlighted red.  Once selected, click on the button on the right hand side of the series select tool.

7) Repeat steps 5 and 6 for the force values.  The force data should be highlighted blue.

8) Input the compressed length.  Our bump stop will have a compressed length of 8mm

9) Input the extended length.  Our bump stop will have an extended length of 15mm

10) Click __OK__ to save the data import

![Bump Stop Output](../img/bs_output.png)

10) The __Document Manager__ will display the data in the left hand editor column and a plot of the data

