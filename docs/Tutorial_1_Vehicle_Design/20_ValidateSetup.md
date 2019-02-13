####[Return to Start](1_Tutorial_1.md)

1) [Create Project](2_Create_Project.md)|2) [Tire Stiffness](3_Tire_Stiffness.md)|3) [Tire Friction](4_Tire_Friction.md)|4) [Tire Assembly](5_TireAssy.md)
-|-|-|-
__5) [Chassis](6_Chassis.md)__|__6) [Spring](7_Spring.md)__|__7) [Bump Stop](8_BumpStop.md)__|__8) [Coilover](9_Coilover.md)__
__9) [Anti-Roll Bar](10_ARB.md)__|__10) [Linear Suspension](11_LinearSus.md)__|__11) [Aerodynamics](12_Aero.md)__|__12) [Brakes](13_Brakes.md)__
__13) [Differential](14_Diff.md)__|__14) [Drivetrain](15_DT.md)__|__15) [Powertrain](16_Powertrain.md)__|__16) [Gearbox](17_Gearbox.md)__
__17) [Introduction to Setup](18_Setupintro.md)__|__18) [Creating a Setup](19_Setup.md)__|__19) [Validating a Setup](20_ValidateSetup.md)__|__20) [Conclusion](21_Conclusion.md)__

#Validating a Vehicle Setup

The setup is now ready to be validated.  This takes the assembly created and tests the feasibility of the assembly in full compression, full extension, full steering lock, and the resting point of the vehicle under the influence of gravity only.

![Validate](../img/validate.png)

There is only one step to validate the setup, which is to click the embedded __Validate Setup__ button shown above

![Validate Status](../img/validate_status.png)

When the setup is validating, the above window will show, if everything solved, the setup can be used for simulation.

If there was an error in validation, the error will be listed in the validation window.

An error in front suspension means that the suspension cannot fully travel in extension or compression (not applicable for a linear suspension)

An error in static state means that there is a likely a spring rate that does not yield a feasible state

If there are no more issues, then you are ready to move on to the next tutorial!

###[Next: Tire Stiffness](3_Tire_Stiffness.md)

###[Previous: Table of Contents](1_Tutorial_1.md)