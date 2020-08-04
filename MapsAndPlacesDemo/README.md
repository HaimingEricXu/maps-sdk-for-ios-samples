# MapsAndPlacesDemo
## Description
This demo application looks to bridge some of the features found in the GooglePlaces and GoogleMaps demo applications as well as utilize some of the ways the two API's can work together.
For more details, please view my [design document](https://docs.google.com/document/d/1hMAYWIzPWIDOCDoLwaJEIVfCDWZjPeMfe1MaQlS_f-o/edit?usp=sharing). Be sure to be logged into your @google account!
Click this [link](https://www.youtube.com/watch?v=u4Ih8EWqZio) to watch a video demonstration.

__This project was made by Haiming Xu as an internship project from 05/2020 to 08/2020__
## Requirements
- A [Google Cloud Platform API key](https://developers.google.com/maps/documentation/ios-sdk/start#get-key) with Maps SDK for iOS and Places SDK for iOS enabled
- A light and dark themed map, which can be created [here](https://console.cloud.google.com/google/maps-apis/client-styles?project=verdant-medium-278819&folder=&organizationId=) (make sure you sign in first)
- A data set that follows the correct formatting (and is also a JSON file) OR a text file of raw coordinates
## Installation
1. Make sure you are in the right folder (MapsAndPlacesDemo)
2. Run `pod install`
3. Open `MapsAndPlacesDemo.xcworkspace`
4. If you have a data set that follows the requirements, skip to step 7
5. Create a set of raw coordintes called raw_input.txt
6. Compile create_list.cpp and run
7. Drag your data set (dataset.json or your data set) into the Xcode file explorer (left pane)
