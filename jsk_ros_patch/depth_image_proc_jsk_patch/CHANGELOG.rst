^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package depth_image_proc_jsk_patch
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.27 (2014-06-10)
-------------------

1.0.26 (2014-05-30)
-------------------

1.0.25 (2014-05-26)
-------------------

1.0.24 (2014-05-24)
-------------------

1.0.23 (2014-05-23)
-------------------

1.0.22 (2014-05-22)
-------------------

1.0.21 (2014-05-20)
-------------------
* forget to add manifest.xml.patch
* Contributors: Kei Okada

1.0.20 (2014-05-09)
-------------------

1.0.19 (2014-05-06)
-------------------

1.0.18 (2014-05-04)
-------------------

1.0.17 (2014-04-20)
-------------------

1.0.16 (2014-04-19)
-------------------

1.0.15 (2014-04-19)
-------------------

1.0.14 (2014-04-19)
-------------------

1.0.13 (2014-04-19)
-------------------

1.0.12 (2014-04-18)
-------------------

1.0.11 (2014-04-18)
-------------------

1.0.10 (2014-04-17)
-------------------

1.0.9 (2014-04-12)
------------------

1.0.8 (2014-04-11)
------------------

1.0.4 (2014-03-27)
------------------
* depth_image_proc_jsk_patch: catkinize (dummy)

1.0.0 (2014-03-05)
------------------
* create new ticket for trac
* modify patch. we now don't need openni_launch_jsk_patch
* modify trac link
* move sample_zoom.launch from depth_image_proc_jsk_patch to openni_launch_jsk_patch and update sample calibration data
* update undistort.cpp for the change of kinect_near_mode_calibration/src/calibrate.cpp
* modify the repository of depth_image_proc. it is for fuerte. and remove openni_launch patch. this patch will be commited as an another package
* use http instead of https to avoid certificate verify failure
* modify undistort.cpp according to the change of kinect_near_mode_calibration. fitting with depth information
* miscommit wrong parameter file by mistake
* add depth_image_proc_jsk_patch. this package is a patch to undistort pointcloud acquired from kinect with zoom lens
* Contributors: k-okada, tsuda
