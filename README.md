# config_filterchain

This repository contains all the filterchain that proc_image_processing can use. This repository allow proc_image_processing to save the filterchain outside the container, so this repository must be a volume at this path: /home/sonia/ros_sonia_ws/src/proc_image_processing/config inside the container. All the files inside this repository must have be at least chmod 777.
