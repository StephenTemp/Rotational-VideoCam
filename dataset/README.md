# Data
Each recording is stored in a folder. Each folder should have the essential files: "[...]_imu_timestamps.csv", "[...]_sync_orientation.csv", "[...]gyro.csv". The sync_orientation file is computed using the python script in script.ipynb.

# Scripts
The script includes functionalities such as: compute orientation from gyro, sync orientation file to video, check orientation-to-frame offset accuracy, and visualize the orientation.

# Visualize
You can visualize the orientation in 3D using the visualize.py script.