<p align="center">
  <img src="images/logo.png" height="200"/>
</p>

> A wholistic solution to the identification and removal of invasive species by 
> both the community and the council.

## Stack 
### Frontend
 
See the `invasiveFE` submodule:

`Flutter` - Google's Crossplatform UI toolkit for native development

`Tensorflow Lite` - Machine learning library

`geojson` - Represent geographical regions in `json`

`camera` - Camera & Image Stream support in flutter

### Backend

See the `invasiveBE` submodule:

`Python` - Interpreted, OOT, High level programming language

`FastAPI` - Web framework for RESTful APIs in Python

`Pydantic` - Creation of custom datatypes and models for use in RESTful APIs

`uvicorn` - ASGI Server implementation

`fuzzywuzzy` - Fuzzy search algorithm

`requests` - HTTP Request library

## Setup 

1. Clone this repo with `git clone --recurse-submodules https://github.com/MoreMilkPerMilk/uproot.git` to get all the code for the project
2. Install frontend requirements with `cd invasiveFE`, then `flutter pub get` in `invasiveFE`
3. Install backend requirements with `cd invasiveBE`, then `pip install -r requirements.txt` in `invasiveBE`
4. Run the backend with `./start.sh`
5. Install a release / debug build of the Flutter app on whatever device you please with 
   `flutter run`. Check Flutter docs for more info.

## Credits
### Programming
* Hamish Bultitude
* James Tobler
* Djamahl Etchegaray
* Joe Holownia

### Design
* Robert Hardgrove
* Carl Shield

## Images
### Camera
<p align="center">
  <img src="images/0_camera.png" width="200">
  <img src="images/1_detection.png" width="200">
  <br>
</p>

### Map
<p align="center">
  <img src="images/3_map.png" width="200">
  <img src="images/6_map_marker.png" width="200">
  <br>
</p>

### Report Page
<p align="center">
  <img src="images/0_camera.png" width="200">
  <img src="images/1_detection.png" width="200">
  <br>
</p>
