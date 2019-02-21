####[Return To Case Studies](../Case_Studies.md)
![Header Image](../img/Case_Study_Header.png)
#Validating a Vehicle Model

A vehicle model is only as good as the inputs that are put in, and can be considered null and void if the model outputs are not validated to the raw data of the vehicle. OptimumDynamics has several features that can be used to make the vehicle validation process a breeze.

The vehicle being validated in this case is a later model GT racing car using data from the Nurburgring. We are assuming that the vehicle kinematics are correct in this simulation, and that the main sources of variance are the spring rate, the anti-roll bar rate, the aerodynamic balance, and tire force scaling. The processes on how to adjust parameters can be found in the tutorial __[here](../Tutorial_3_Modifying_Vehicle_Setup/1_Tutorial_4.md)__

Upon Creating the vehicle setup and importing the data, we can run the base parameters for the vehicle. This assumes no scaling for real world situations. We have data available for the damper position which will be used as out validation for compression of the vehicle and roll of the vehicle.

The baseline setup can be used to benchmark the difference between the input parameters and the actual outputs of the simulation. To begin, we have channels for lateral, longitudinal and vertical acceleration for the four corners of the vehicle. In addition to the included channels, we also are going to use the linear potentiometer channels to determine if the vehicle reactions being read in the data are the same as the outputs in simulation. Note that we are not accounting for the reaction in the simulation, so there are some of the instances that will not perfectly match up.

Using the linear potentiometers, we create four math channels for the input parameters: Front Roll Angle, Rear Roll Angle, Left Pitch Angle, Right Pitch Angle. These can be used to match up the actual roll gradient of the suspension, and the stiffness of the springs. This only gives us the roll gradient of the vehicle without tire stiffness, ride height sensors would be required to determine the full roll of the vehicle with tires.

In the early stages of the simulation, there may not be a perfect correlation of the tire forces, which can cause the simulation to not converge. When this occurs, the data points for those instances will not show up. We can deselect the option __Only Show Converged Steps__. After completing the baseline simulation, we can start to make decisions on where to improve the vehicle model. In the case of this simulation, there was a serious underestimation of the vehicle tire friction. Before any moves can be made to improve the representation of the vehicle balance, this needs to be addressed. The progression below shows how the simulation output improved with the tire forces scaled.

![](../img/tire_plot_scaling.png)

Once the data reached a point in which the acceleration plots were nearly equivalent, we could move on to establishing the correct vehicle balance. We have created plots for the vehicle pitch angle, pitch gradient, roll angle, roll gradient, and vehicle compression relative to speed.

![]()

Based on our results, our simulated car had an overly ambitious aerodynamics package that caused the vehicle show an aggressive pitch angle in simulations that did not exist in the actual vehicle lap. To fix the solution, we will start by dropping the downforce coefficients

![]()

The results for the high speed pitch angle are now much more in line with the actual vehicle results, with the areodynamic effect no longer causing the aggressive parabolic shape initially seen.

###[Next Case Study: Determining Vehicle Balance](../Case_Study_4_Vehicle_Balance/1_Case_4.md)