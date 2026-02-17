# NIH-plug

Build the puberty_simulator plugin as CLAP, VST3 & Standalone:
```shell
sudo apt-get update
sudo apt-get install -y libasound2-dev libgl-dev libjack-dev libx11-xcb-dev libxcb1-dev libxcb-dri2-0-dev libxcb-icccm4-dev libxcursor-dev libxkbcommon-dev libxcb-shape0-dev libxcb-xfixes0-dev
cargo xtask bundle puberty_simulator
```