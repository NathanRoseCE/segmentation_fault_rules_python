# External Tools
This is the external tools folder, if you need to add code that cannot be added to the 
requirements.txt file then you can add it in this folder:

## Process

1. Identify a tool that you need and cannot be installed directly
2. Get a copy of its source code and paste it in this folder
3. Create a README that contains the following information
    - Description of package
    - Version number
    - at least two maintainers(see responsibilities of maintainers below)
4. Push your changes

## Maintainer Responsibilities
As a maintainer of the code you become responsible for ensuring the software is in a 
working condition. A non-comprehensive list of responsibilities are shown below:

1. Ensuring the version of the software is appropriate(updating it when appropriate)
2. Working to handle any security patches that are required

Note that if you are moving to a position where you are unable to handle these 
responsibilities then you should remove yourself as a maintainer(and add a new 
maintainer if required).

## Version numbers
The version number should follow [semantic versioning](https://semver.org). In short:
Version number should follow MAJOR.MINOR.PATCH

incrament Patch number when the change should not effect the agreed contact(ie bug fixes,
implimentation changes)

incrament the Minor number when new features are added to the external api that is visible
to external parties(think python3.9->python3.10)

incrament the major number when the change introduced causes incompatibilites with prior 
versions.(think python2->python3)