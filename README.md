# Unified Robot Environment (URE) - Robot Repository

## Overview

Welcome to the Unified Robot Environment (URE) - Robot Repository! This repository houses a collection of various robots integrated into the URE. Each robot comes equipped with URDF files and STL models, providing a diverse set of robotic entities for your projects.

## Usage

Loading the URDF file will load all of the stl files for the robot. To add a new robot, please put it in it's own folder.

## Credits

These robots are build by different individuals. We would like to thank the following people for their contributions:

### OpenQuadruped

- Maurice Rahme
- Ian Abraham
- Matthew Elwin
- Todd Murphey

### SpotMicro

- Deok-yeon Kim

## Licensing Information

The licensing details for each robot can be found in the `docs/` folder within the corresponding subdirectory. Take the time to understand and comply with the licensing terms before incorporating any robot into your work.

## Contribution

If you have additional robots or improvements to existing ones that you'd like to contribute, please make an issue to discuss the change.

Necessary files to include for a new robot would be:

- `docs/README.md`: Credit the original authors of the STL/URDF files and link to their original repos, if available. If there are READMEs with relevant information in their repos, add it to this README as well.

- `docs/LICENSE.txt`: Add the original authors license information, following the license agreement.

- `stl/*.stl`: The STL files for the robot

- `*.urdf`: The URDF file, linked correctly to the STLs in the `stl` folder.

If available, please add the MuJoCo XML file as well. In the future, the URE may support MuJoCo simulation. Please put this file at the same level as the URDF.

## Disclaimer

While this repository strives to provide a variety of robots for your convenience, it is your responsibility to ensure compliance with the individual licenses associated with each robot. Be sure to thoroughly review the documentation and licensing information before using any robot from this repository.

We hope you find the Unified Robot Environment (URE) - Robot Repository a valuable resource for your robotics endeavors.

