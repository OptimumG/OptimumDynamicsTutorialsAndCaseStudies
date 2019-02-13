[Return to Start](1_Tutorial_1.md)

-|-|-|-
[Create Project](2_Create_Project.md)|[Tire Stiffness](3_Tire_Stiffness.md)|[Tire Friction](4_Tire_Friction.md)|[Tire Assembly](5_TireAssy.md)
[Chassis](6_Chassis.md)|[Spring](7_Spring.md)|[Bump Stop](8_BumpStop.md)|[Coilover](9_Coilover.md)
[Anti-Roll Bar](10_ARB.md)|[Linear Suspension](11_LinearSus.md)|[Aerodynamics](12_Aero.md)|[Brakes](13_Brakes.md)
[Differential](14_Diff.md)|[Drivetrain](15_DT.md)|[Powertrain](16_Powertrain.md)|[Gearbox](17_Gearbox.md)
[Introduction to Setup](18_Setupintro.md)|[Creating a Setup](19_Setup.md)|[Validating a Setup](20_ValidateSetup.md)|[Conclusion](21_Conclusion.md)

#Tire Assembly

A tire assembly is comprised of a tire friction model and a tire stiffness model.  If one of the two components is missing from the model, the setup used will not validate.  

To create a tire assembly:

![New Tire](../img/tire_assy.png)

1) Click the __Add Tire__ button and select the __New Tire__ option

![Tire Name](../img/tire_assy_name.png)

2) Provide the assembly a name and verify the location saved

3) Click the (...) next to *Select Component*

![Tire Stiff File](../img/tire_stiff_file.png)

4) Select the created tire stiffness file.  The tire will now appear in the 3D Editor

![Tire Force File](../img/tire_force_file.png)

5) Select the tire force model being used.  The tire pressure can be set after that.  

6) The tire assembly also specifies a tire pressure.  Our model does not include tire pressure effects, but should still be filled out.  This will be a good opportunity to go over the options changes.  The default units for pressures are Pascals, and we are going to switch them to bar.  To change the units:

Go to __options__ in the __Project Backstage__ or press the hot key __F9__.

![Options](../img/Options.png)

Under __Units__, go to __Pressure__, and select Bar

7) With the units changed, set the pressure to 1.6 Bar.

8) Once the first tire is done, complete the same method for the second tire model, using the second tire model and a pressure of 1.65.