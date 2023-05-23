```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/esteve/autoware_packages/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/esteve_autoware_packages.list
echo "yaml https://raw.githubusercontent.com/esteve/autoware_packages/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-esteve_autoware_packages.list
```
