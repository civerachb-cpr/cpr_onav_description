^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cpr_onav_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.3 (2023-07-25)
------------------
* fix: move lms1xx link back into correct location. this bug was resolve in the intall script. update hokuyo prefix
* Contributors: José Mastrangelo

0.1.4 (2023-08-10)
------------------
* fix urdf issue related to including multiple realsense cameras. moved all includes into custom block. each of the standard/starter sub-urdfs have their own include lines for the required sensors.
* 0.1.3
* Changes.
* fix: move lms1xx link back into correct location. this bug was resolve in the intall script. update hokuyo prefix
* Contributors: José Mastrangelo, Tony Baltovski

0.1.2 (2023-06-05)
------------------
* modified sensor topic names. and move laser out of block as a temp fix
* Contributors: José Mastrangelo

0.1.1 (2023-05-08)
------------------
* Added license file.
* remove circular dependency by adding local copies of accesory urdf files
* added charge receiver link
* Contributors: José Mastrangelo, Tony Baltovski

0.1.0 (2023-03-16)
------------------
* Added STL files for Starter Kit, Velodynes and Realsense D435s
* Added urdf files for starter and standard kits
* Contributors: José Mastrangelo
