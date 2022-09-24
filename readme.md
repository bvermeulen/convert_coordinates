# Convert coordinates (PSD93 Oman)

A little app in pyqt to make conversions between geodetic (WGS84) and PSD93 and UTM 40N projections. 

![main page](convert_main.png)

![conversion from lon lat to easting northing (in degrees)](convert_ll_en.png)

![converion from easting northing to lon lat (in DMS)](convert_en_ll.png)

App written in Python 3.10 with dependencies in `requirements.txt`


Instructions to install (Linux)
```
$git clone https://github.com/bvermeulen/convert_coordinates.git
$cd convert_coordinates
$python -m venv ./venv
$source ./venv/bin/activate
$pip install -r requirements.txt
$python convert_coords_pyqt.py
```
