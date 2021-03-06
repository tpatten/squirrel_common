^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package robotino_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.33 (2018-03-08)
-------------------

0.0.32 (2018-02-27)
-------------------

0.0.31 (2018-02-26)
-------------------
* add argument for simulation vs real robot
* add front shell collision
* Contributors: ipa-nhg

0.0.30 (2018-01-25)
-------------------
* revert motor directions
* joint directions review
* Merge branch 'indigo_dev' into ArmReview
* updated velocities and effrots
* review motor directions for the arm
* udpated joint limits for folding the arm
* added a calibration parameter for the neck to the shell
* added gazebo controllers for the shell
* test shell model on real robot
* update urdf to support calibration
* add door model
* updated the collision model of the shell
* update base model
* review collisions
* Contributors: Nadia Hammoudeh García, Philipp Zech, Richard Bormann, Thomas Fäulhammer, ipa-nhg

0.0.29 (2017-09-05)
-------------------

0.0.28 (2017-09-04)
-------------------
* some misalignment
* aligned with squirrel-project
* aligned with remote
* add position interfaces
* updates
* updates
* updated the collision model of the base
* change frame_id for the odometry on simulation
* update shell model to be compatible with the calibration software
* added shell with kinematic
* Contributors: Federico Boniardi, ipa-nhg

0.0.27 (2017-06-28)
-------------------

0.0.24 (2017-02-20)
-------------------

0.0.23 (2017-02-13)
-------------------
* Temporal fix: ignore the visual model of the shell
* colored the shell
* update arm colltion model to include the airskin
* compare tf tree with real robot -- odom frame fixed
* added shell model to tuw-robotino-2
* Integrate hclhand description on robotino_description
* set 8 dof
* update
* simple base
* removed collision and visual parts of virtual joints
* test model
* added gazebo_plugins
* THE (hopefully) working model
* use a simple base for non-arm robots
* typo error
* use gazebo plugin to move the baser
* addapted base to 8 dof modus
* made navigation and planning to work in parallel
* removed base plan xacro
* rolled back base
* Contributors: Edith Langer, Philipp Zech, ipa-nhg, shangl

0.0.22 (2016-09-28)
-------------------

0.0.21 (2016-09-15)
-------------------

0.0.20 (2016-09-07)
-------------------
* simplify collision model
* created a new base urdf to plan
* Merge branch 'Arm' of github.com:ipa-nhg/squirrel_common into Arm
  Conflicts:
  robotino_description/urdf/arm.urdf.xacro
* base 8 dof
* 8 dof description
* 8 dof description
* clean and review arm link names
* add missed depend
* default inertia values for hand links
* updated urdf
* updated urdf
* new arm description
* package restructuration
* Contributors: ipa-nhg
