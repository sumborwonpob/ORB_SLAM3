# ORB-SLAM3

### Forked version of ORB-SLAM3 originally uploaded by
**Authors:** Carlos Campos, Richard Elvira, Juan J. Gómez Rodríguez, [José M. M. Montiel](http://webdiis.unizar.es/~josemari/), [Juan D. Tardos](http://webdiis.unizar.es/~jdtardos/).

Thank you for this amazing work!

## Changes
Mainly adjustments to facilitate and increase performance of Mono-Inertial mode.
* Change IMU initialization condition to allow a bit easier IMU initialization.
* Adjust timings for bundle adjustment to be faster.
* Always do scale refinement steps every certain interval, regardless of number of KF.
* Change visibility of some class arrtibutes to make it easier to interface in the ROS implementation.
