#
# JSMN
#
# Copyright (c) 2022 Laird Connectivity
#
# SPDX-License-Identifier: Apache-2.0
#

if(CONFIG_JSMN)
    # Add include and source file
    zephyr_include_directories(include)
    zephyr_sources(src/jsmn_json.c)
endif()

