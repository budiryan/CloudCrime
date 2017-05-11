# CloudCrime
COMP4651 course project @ HKUST

## Installing Dependencies (Tested on Ubuntu 16.04):
- Update your system:

`sudo apt-get update`
- Install Linux dependencies: 

`sudo apt-get install build-essential libssl-dev libffi-dev python3-dev`
- Install Python virtual environment: 

`sudo apt-get install python-virtualenv`
- `cd CloudCrime`
- Create a new virtual environment: 

`virtualenv -p python3 env --no-site-packages`
- Switch to virtual environment: 

`source env/bin/activate`
- Install Python dependencies: 

`pip install -r requirements.txt`

### Install Basemap for visualization

`sudo apt-get update`

`sudo apt-get install python-gi-cairo`

`sudo pip install pyproj pyshp `

`git clone https://github.com/matplotlib/basemap.git`

- `cd basemap`
- Install Geos:

	```
	 > cd geos-3.3.3
	 > export GEOS_DIR=<where you want the libs and headers to go>
	   A reasonable choice on a Unix-like system is /usr/local, or
	   if you don't have permission to write there, your home directory.
	 > ./configure --prefix=$GEOS_DIR 
	 > make; make install
	```
- Install basemap:

	```
	 > cd ..
	 > sudo python setup.py install
   	```
- Install scipy


	```
	 > sudo apt-get install libblas-dev liblapack-dev libatlas-base-dev gfortran
	 > sudo pip install cython
	 > sudo pip install scipy
   	```

## CONTRIBUTORS:
- Budi RYAN (bryanaa) (https://github.com/budiryan)
- Dicky CHIU (mtchiu) (https://github.com/Dickyhaha)
- Mikaela UY (mauy) (https://github.com/mikacuy)

