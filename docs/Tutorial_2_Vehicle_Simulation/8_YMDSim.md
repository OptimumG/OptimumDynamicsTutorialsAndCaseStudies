####__[Return to Home](1_Tutorial_2.md)__

[1) Importing and Exporting Setups](2_ImportExport.md)|[2) Single Step Simulation](3_SingleStepSim.md)|[3) Multiple Step Smooth Simulation](4_MultiStepSim.md)
-|-|-
[__4) Multiple Step Freehand Simulation__](5_MultiStepRough.md)|[__5) Track Replay Simulation__](6_TrackReplay.md)|[__6) Exporting Results Files__](7_ExportResults.md)
[__7) Yaw Moment Diagram Simulation__](8_YMDSim.md)|[__8) Conclusions__](9_Conclusions.md)

#Creating a Yaw Moment Diagram Simulation

*This step is optional. If you are not using and/or not planning to use a full tire model in your simulations, you can skip ahead*

The __Yaw Moment Diagram__ is a tool that can be used to understand the limit nature of the vehicle. We can create the full Yaw Moment Diagram using the __Constant Step__ tool and set the parameters to determine the size. The Yaw Moment Diagram does require a full tire model to use. A generic tire that can be used with the model can be downloaded __[here](../Tire Model Baseline.ODVeh)__.

__Full Disclosure__: The tire model within this setup does not reflect any actual tire. It was purely created to show the features of the software. Please determine your actual tire model if you are using a full vehicle model

Here are the steps to use the Yaw Moment Diagram:

1) __Import__ the tire model vehicle setup from the above link.

![New YMD](../img/new_YMD.png)

2) Select the __Constant Step YMD__ option under the __YMD__ button

![YMD Name](../img/YMD_name.png)

2) Provide a name for the Yaw Moment Diagram being created

![YMD Param](../img/YMD_param.png)

3) OptimumDynamics comes pre-loaded with parameters to create the Yaw Moment Diagram. The only parameter we are going to change is the __Free Rolling__ setting to the __Fixed Acceleration__ setting.  We will set this to -7.48 m/s^2

4) Run the simulation using the __Quick Run__ tool.

###[Next: Conclusion](9_Conclusions.md)
--------------------------------------------------------
###[Previous: Exporting Results Files](7_ExportResults.md)