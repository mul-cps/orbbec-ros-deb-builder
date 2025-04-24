```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/mul-cps/orbbec-ros-deb-builder/noble-jazzy-amd64/ ./" | sudo tee /etc/apt/sources.list.d/mul-cps_orbbec-ros-deb-builder.list
echo "yaml https://github.com/mul-cps/orbbec-ros-deb-builder/raw/noble-jazzy-amd64/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-mul-cps_orbbec-ros-deb-builder.list
```
