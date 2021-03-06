^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package qb_device_driver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.1.0 (2019-05-28)
------------------
* Improve inheritance for other devices
* Update documentation
* Fix minor style issues

2.0.3 (2018-08-09)
------------------
* Update license agreement copyright

2.0.2 (2018-08-07)
------------------
* Exclude dummy boards from the connected device list

2.0.1 (2018-06-01)
------------------

2.0.0 (2018-05-30)
------------------
* Move sleep at low level (next to API)
* Add method to temporarily change PID parameters
* Fix doxygen documentation
* Fix communication errors with asynchronous reads
* Refactor node registration
* Add method to get currents and positions together
* Fix minors
* Fix repetitions reliablity check
* Add a blocking setCommands method
* Fix destructor calls on ROS shutdown
* Fix minors
* Fix unexpected fault with std::unordered_set
* Add parallelization with several USB connected
* Let the user decide whether to read/write or not
* Add an alert if maximum repetitions is set to zero
* Refactor node registration
* Add a real isConnected method
* Refactor device scan method with repetitions
* Retrieve control and input mode device settings
* Implement repetitions also for getMeasurements
* Add repetitions while reading from serial
* Move error checks in ROS service callbacks

1.2.2 (2017-11-30)
------------------
* Reduce communication errors

1.1.0 (2017-11-24)
------------------

1.0.8 (2017-06-27)
------------------
* Fix C++11 support for cmake version less than 3.1

1.0.7 (2017-06-26)
------------------
* Fix minor build problems

1.0.6 (2017-06-23)
------------------
* Update cmake version to match Kinetic standards

1.0.5 (2017-06-22)
------------------

1.0.4 (2017-06-21)
------------------

1.0.3 (2017-06-21)
------------------
* fix cmake settings to solve isolated builds

1.0.2 (2017-06-20)
------------------
* remove API git submodule and add API files manually (API commit: c61204b) because ROS buildfarm does not manage git submodules

1.0.1 (2017-06-19)
------------------
* first public release for Kinetic
