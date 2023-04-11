# SPDX-License-Identifier: Apache-2.0
#
# Copyright (c) 2023 gabbla
# Author: Zampieri Gabriele <zampierigabriele.ist@gmail.com>

zephyr_include_directories(StdDriver/inc)
zephyr_include_directories(Device/M0A21/Include)

zephyr_sources_ifdef(CONFIG_SOC_SERIES_M0A2X Device/M0A21/Source/system_M0A21.c)

add_subdirectory(StdDriver)
