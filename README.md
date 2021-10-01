# SurgicalCubePose
This is the main repository for tracking surgical attachment for accurate monocular pose estimation with aruco boards for the purpose of providing navigation support.


## Usage example
With this example, from tracing the tip of the surgical instrument on top of a porcelain sphere with a radius of 45 mm, the following sphere fit is obtained, shown in the following gif.

<p align="center">
    <img src="figures/tracing.gif" alt="tracing the sphere" width="400px"/>
</p>

To run this example:

* Clone this repository: `git clone https://github.com/camicontr/SurgicalCubePose.git`


A visualization of the point cloud in addition to the sphere model obtained 

<p align="center">
    <img src="figures/Sphere" alt="Result of fit sphere" width="400px"/>
</p>
With a radius rms error of 0.1701 mm 

## Dependencies

* Python 3
* NumPy
* Pandas
* Scipy
* OpenCV
* Sklearn
* circle_fit
* Scikit-surgery-sphere-fitting
