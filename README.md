# plot_util
Generate PDF file report using ROS Odometry data.

Author: Silvio Maeta - smaeta@andrew.cmu.edu

Take a look in the plot_util/launch/generate_plots.launch to configure:
 - output_filename: output path and filename for the PDF report containing the plots
 - pose_topic: Odometry message topic name
 
OBS: this plot generator was developed expecting position in NED frame - North=X / East=Y / Down=Z
The python code can be easily modified to support other coordinate frames.

