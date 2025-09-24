# ST Microelectronics IIS3DWB 3-axis accelerometer driver
#
# Copyright (c) 2020 STMicroelectronics
#
# SPDX-License-Identifier: Apache-2.0
#
#zephyr_library()
zephyr_library_sources_ifdef(CONFIG_IIS3DWB iis3dwb_trigger.cpp) 