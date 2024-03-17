In this assignment let's build a Gallery App

Refer to images below:

--https://assets.ccbp.in/frontend/content/react-js/gallery-output.gif -- gallery-output

Design Files
Extra Small (Size < 576px) and Small (Size >= 576px)

Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)

Project Set Up Instructions
Download dependencies by running npm install
Start up the app using npm start
Project Completion Instructions
Add Functionality
The app must have the following functionalities

When the user clicks on a thumbnail then the corresponding image should be displayed.

The list of image and thumbnail URLs is passed to the Gallery component as a prop photosData in the form of an array object.

Each photo object will have the following properties.

Key	Data Type
id	Number
imageUrl	String
thumbnailUrl	String
imageAltText	String
thumbnailAltText	String
The value of the key id should be used as a key to the thumbnail image.

The value of the key imageAltText should be used as alt text to the selected image.

The value of the key thumbnailAltText should be used as alt text to the thumbnail images.

The default selected image should be the first image in the photosData array.

The ThumbnailsList component should render thumbnail images.

core code files

src/components/Gallery/index.js
src/components/Gallery/index.css
src/components/ThumbnailsList/index.js
src/components/ThumbnailsList/index.css
Quick Tip
Use the CSS opacity property to set the degree to which content behind an element is hidden. It has a value in the range of 0. Click this to know more.
Resources
Images
Image URLs

https://assets.ccbp.in/frontend/react-js/nature-mountain-with-pond-img.png
https://assets.ccbp.in/frontend/react-js/nature-sunset-img.png
https://assets.ccbp.in/frontend/react-js/nature-mountain-with-ocean-img.png
https://assets.ccbp.in/frontend/react-js/nature-mountain-with-forest-img.png
https://assets.ccbp.in/frontend/react-js/nature-leaves-img.png
https://assets.ccbp.in/frontend/react-js/nature-tree-img.png
https://assets.ccbp.in/frontend/react-js/nature-waterfall-img.png
https://assets.ccbp.in/frontend/react-js/nature-river-img.png
Thumbnail image URLs

https://assets.ccbp.in/frontend/react-js/nature-mountain-with-pond-thumbnail-img.png
https://assets.ccbp.in/frontend/react-js/nature-sunset-thumbnail-img.png
https://assets.ccbp.in/frontend/react-js/nature-mountain-with-ocean-thumbnail-img.png
https://assets.ccbp.in/frontend/react-js/nature-mountain-with-forest-thumbnail-img.png
https://assets.ccbp.in/frontend/react-js/nature-leaves-thumbnail-img.png
https://assets.ccbp.in/frontend/react-js/nature-tree-thumbnail-img.png
https://assets.ccbp.in/frontend/react-js/nature-waterfall-thumbnail-img.png
https://assets.ccbp.in/frontend/react-js/nature-river-thumbnail-img.png
Colors
Hex: #1e293b
Hex: #ffffff
Hex: #64748b
Font-families
Roboto
About
A gallery application with set of thumbnail images and a main image which is completely responsive in design created using react concepts.

Topics
javascript html5 css3 reactjs reactjs-components thumbnail-images reactjs-es6 responsive-web-design reactjs-demo
Resources
 Readme
 Activity
Stars
 1 star
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
JavaScript
55.9%
 
HTML
25.6%
 
CSS
18.5%
Footer
