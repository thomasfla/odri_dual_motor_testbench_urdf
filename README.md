# odri_dual_motor_testbench_urdf
URDF of open dynamic robot initiative dual motor test bench 

To generate the URDF file from CAD sources you need:

* An onshape account (Free account is ok)
* Install onshape-to-robot
`pip install onshape-to-robot`
* Set your onshape API key in bashrc:
```
// Obtained at https://dev-portal.onshape.com/keys
export ONSHAPE_API=https://cad.onshape.com
export ONSHAPE_ACCESS_KEY=Your_Access_Key
export ONSHAPE_SECRET_KEY=Your_Secret_Key
```
* Run `onshape-to-robot .` at the root of this repo
* Test on bullet with `onshape-to-robot-bullet .`

