```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/mul-cps/orbbec-ros-deb-builder/resolute-lyrical-amd64/ ./" | sudo tee /etc/apt/sources.list.d/mul-cps_orbbec-ros-deb-builder-resolute-lyrical-amd64.list
echo "yaml https://github.com/mul-cps/orbbec-ros-deb-builder/raw/resolute-lyrical-amd64/local.yaml lyrical" | sudo tee /etc/ros/rosdep/sources.list.d/1-mul-cps_orbbec-ros-deb-builder-resolute-lyrical-amd64.list
```
