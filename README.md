## Panorama creator ##

## Example of use
Takes 2 photos: 

	- Left image: 
		![alt text](https://github.com/AvielCo/Panorama-Stitch-Algorithm/blob/main/left.jpg?raw=true)
	- Right image:
		![alt text](https://github.com/AvielCo/Panorama-Stitch-Algorithm/blob/main/right.jpg?raw=true)
	- Result (panorama image):
		![alt text](https://github.com/AvielCo/Panorama-Stitch-Algorithm/blob/main/panorama.jpg?raw=true)
## Installation
	python version 3.7
	libraries needed:
		opencv
		numpy
		argparse
		matplotlib - optional, only to view photos in realtime

## How to use?
	1. open terminal/CMD
	2. write command to start the stitch process: python panorama.py <path_left_img> <path_right_img> <path_output>
	                                     example: python panorama.py left.jpg right.jpg panorama.jpg
	    2.1. takes left image and right image from selected path
		2.2. it will be output to path_output
	3. result will be panorama of both images using stitch algorithm
	
## Credits
	Aviel Cohen
	Vitaly Nechayuk 

AviVit Technologies Inc. ©
