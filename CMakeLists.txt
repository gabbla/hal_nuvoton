# SPDX-License-Identifier: Apache-2.0
#
# Copyright (c) 2020 Linumiz
# Author: Saravanan Sekar <saravanan@linumiz.com>

add_subdirectory_ifdef(CONFIG_SOC_SERIES_M0A2X m0a2x)
add_subdirectory_ifdef(CONFIG_SOC_SERIES_M48X m48x)
add_subdirectory_ifdef(CONFIG_SOC_SERIES_M46X m46x)
