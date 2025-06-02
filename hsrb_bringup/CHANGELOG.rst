^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package hsrb_bringup
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.2.0 (2025-04-22)
-------------------
* change cgos to HSRC only
* modify stereo launch to stereo.launch.py
* remove file:// from calibration_file_directory
* add depth_rectifier, pgr_camera, auto_diagnostics
* Fix input odom of omnibase controller
* add gpio settings
* Add laser odometry and odometry switcher
* Add configuration for the diagnostic aggregator of the battery and IMU
* Enable velocity control for the base_roll_joint
* Change the startup timing of the imu diagnostics updater
* Fix README
* Separate the startup of the application node
* Fix lint errors
* remove redundunt codes, modify params, remove unused mainteiner. trap align_angle_sensors_response is None
* add hsrb_align for init pose on startup, add cotrollers, add hsrb_status_led
* Contributors: Hiroaki Yaguchi, Keisuke Takeshita, katsushi fukuoka

2.1.0 (2024-10-16)
-------------------
* Migration to Humble
* Contributors: Hiroaki Yaguchi, Keisuke Takeshita, Masayuki Masuda, Tomohiro Ono

