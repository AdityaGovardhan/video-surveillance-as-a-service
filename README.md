![alt text](https://github.com/AdityaGovardhan/video-surveillance-as-a-service/blob/master/architecture.jpg)
Prerequisites:
==============
- Bash Shell
- Runs on Linux/Mac machines

Deployment through script:
==========================
The source code comes along with a bash script (infrastructure.sh) that can be used for bringing up the infrastructure, deploying the project and bringing down the infrastructure. The requirement for successful use of these scripts is that the project folders of WebTier, AppTier and AppTier_Terminator, deployment files WebTier.sh and AppTier.sh, project files darknet_test.py and yolov3-tiny.weights should be in the same folder as infrastructure.sh file.

To bring up the initial infrastructure, following bash commands are executed:

	$ bash  infrastructure.sh  create

To deploy the project, following bash commands are executed:

	$ bash  infrastructure.sh  deploy-project

To bring down the infrastructure, following bash commands are executed:

	$ bash  infrastructure.sh  destroy
