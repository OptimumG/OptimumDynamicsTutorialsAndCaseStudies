####[Return to Start](1_Tutorial_1.md)

1) [Create Project](2_Create_Project.md)|2) [Tire Stiffness](3_Tire_Stiffness.md)|3) [Tire Friction](4_Tire_Friction.md)|4) [Tire Assembly](5_TireAssy.md)
-|-|-|-
__5) [Chassis](6_Chassis.md)__|__6) [Spring](7_Spring.md)__|__7) [Bump Stop](8_BumpStop.md)__|__8) [Coilover](9_Coilover.md)__
__9) [Anti-Roll Bar](10_ARB.md)__|__10) [Linear Suspension](11_LinearSus.md)__|__11) [Aerodynamics](12_Aero.md)__|__12) [Brakes](13_Brakes.md)__
__13) [Differential](14_Diff.md)__|__14) [Drivetrain](15_DT.md)__|__15) [Powertrain](16_Powertrain.md)__|__16) [Gearbox](17_Gearbox.md)__
__17) [Introduction to Setup](18_Setupintro.md)__|__18) [Creating a Setup](19_Setup.md)__|__19) [Validating a Setup](20_ValidateSetup.md)__|__20) [Conclusion](21_Conclusion.md)__

#Spring

The vehicle springing is necessary to allow the suspension to operate.  Some knowledge of this mechanism is required to determined how much, and in what way the suspension will move when inputs are applied in the simulation. To create the spring for the model:

![Create Spring](../img/new_spring.PNG)

1) Click on the __Add Spring__ button and select the __New Linear Spring__ option.

![Spring Name](../img/spring_name.png)

2) We will create the front spring first, so the names should correspond in a way that allows the user to recall the component quickly

![Spring Param](../img/spring_param.png)

3) The stiffness, free length, and compressed length can now be input.

Note that once the inputs for free length and stiffness are set, OptimumDynamics will start to calculate the force at each displacement of the spring to its fully compressed length.  This can be used as a secondary reference to verify that the spring stiffness input is correct.

![Rear Spring Param](../img/rear_spring_param.png)

4) Repeat the sequence now for the rear spring, with a stiffness of 50 N/mm

###[Next: Bump Stop](8_BumpStop.md)
--------------------------------------------------------
###[Previous: Chassis](6_Chassis.md)