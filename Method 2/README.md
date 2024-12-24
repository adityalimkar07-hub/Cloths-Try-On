1. We have used M3D-VTON to build our model. Link to the repo:- "https://github.com/fyviezhao/M3D-VTON"
2. Set the directories according to the given repository
3. This model involes use of image parsing and human pose estimation using open pose.
4. Downlaod the rar file from "https://drive.google.com/file/d/1JOLJD1IXbDxHpwPRo0hDuzb_77IPrdqI/view?usp=sharing" and extract the folder.
5. Folder consists of code for image parsing and open pose model for pose estimation. We have also added main code for reference.
6. To use image parsing code, change the directory according to use and run the code.
7. To use openpose, open the openpose folder, copy the path of image and hit the command in powershell/cmd "bin\OpenPoseDemo.exe --video {directory to image} --hand --face --model_pose BODY_25 --write_json output_json_folder/".
8. Copy these files and save it in the directory as per the requirement of the main code.
9. Run the main code after adjusting the directories, this will give ply file as final output.
10. To convert the ply point cloud data into 3d mesh you can use meshlab , instructions are given in the link of M3D-VTON github repository.
