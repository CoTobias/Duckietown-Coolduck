Autonomous Navigation & Real Time Mapping on iOS


To run Analysis: 
1 Keyboard Control:
	dts duckiebot keyboard_ control
2 Camera Control:
	dts start_gut_tools coolduck 
	rqt_image_view coolduck
3 Run Trajectory Calculation: 
	dts devel build -f 
	dts devel run -R coolduck -L trajectory
4 See published Messages: 
	dts devel run -H coolduck -L my-subscriber
 
