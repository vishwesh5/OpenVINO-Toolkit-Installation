## Download OpenVINO Toolkit

**Ubuntu-18.04 is not supported.**

Go to [Downloads Page](https://software.intel.com/en-us/openvino-toolkit/choose-download/free-download-linux) and get **Intel Distribution of OpenVINO toolkit for Linux**.
Select **Offline Installer** (you can even go for **online installer**) and start the download.

```
mkdir openvino-toolkit
mv ~/Downloads/l_openvino_toolkit_p_<version>.tgz
tar -xvzf l_openvino_toolkit_p_<version>.tgz
cd l_openvino_toolkit_p_<version>
./install_cv_sdk_dependencies.sh
```

**There is a dependency conflict in `libpng12-dev` and `libgtk2.0-dev`**.

```
./install_GUI.sh
```
We will cover command line installation later in the post.
