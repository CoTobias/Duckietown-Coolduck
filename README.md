Autonomous Navigation & Real Time Mapping on iOS
```
'''
To run Analysis:
1 Keyboard Control:		
	dts duckiebot keyboard_ control
2 Camera Control:			
	dts start_gut_tools 'duckiebotname' 
	rqt_image_view duckiebotname'
3 Run Trajectory Calculation: 
	dts devel build -f 
	dts devel run -R duckiebotname' -L trajectory
4 See published Messages: 
	dts devel run -H duckiebotname' -L my-subscriber

To run Mobile iOS:
# Mobile ROS

Mobile ROS is a iOS application for dealing with word pluralization.

## Installation

Use the package manager [npm](https://www.npmjs.com) to install Mobile ROS, make sure you are under root path of the project.

bash
npm install


## Usage

bash
#to start the app
npx expo start

and then press i/a/w to launch iOS/Android/web version of the application

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)

To run Lane following:
change the name of the bot in default.sh in launcher
dts devel build -f
dts devel run -R [Vehicle_Name]
