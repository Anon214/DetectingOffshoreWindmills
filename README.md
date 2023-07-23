<h1 align="center">
  DetectingOffshoreWindmills
</h1>

<h4 align="center">A script to detech offshore windmills.</h4>

## About the code
Primarily built with
* Python
* Tensorflow
* Various other libraries


## How To Use

To run this repository, you must need access to the Microsoft Planetary Computer. You can request access <a href="https://planetarycomputer.microsoft.com/">here</a>.

Download copy.pynb and import it into the planetary computer environment.

From there, every library should already be installed in there as long as you keep running the code blocks in a sequential manner.

## About the code

* Developed during the Microsoft NASA Space Education Hackathon program
* There was code given, and the written code begins at block 15
* Developed machine input parameters such as ratios and distances
* Took the nearest three distances as input parameters into the machine learning model, alongside various other variables such as area
* Trained and tested the model which lead to an accuracy rate around 97-99%

> **Note**
> It only detects the east coast of germany right now. More work has to be done on figuring out the bound values in order to go to different regions.
