Yocto Layer for librealsense
============================
This layer adds the packages necessary for adding support for Intel® RealSense™ cameras via [librealsense](https://github.com/IntelRealSense/librealsense) to your Yocto distribution.

Usage
=====
1. Checkout the branch which corresponds to your version of Wind River IDP (e.g. `idp_3.x`)
2. Include the following in your project configure command
```bitbake
    --with-layer=/path/to/meta-intel-realsense
    --with-package=librealsense,librealsense-examples
```

License
=======
This project is Copyright (C) 2015 Intel Corporation. Please see the LICENSE file for more information.
