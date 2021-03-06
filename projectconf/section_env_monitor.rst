..  Copyright (c) 2014-present PlatformIO <contact@platformio.org>
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
       http://www.apache.org/licenses/LICENSE-2.0
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

.. _projectconf_section_env_monitor:

Monitor options
~~~~~~~~~~~~~~~

.. contents::
    :local:

Custom options for :ref:`cmd_device_monitor` command.

.. _projectconf_monitor_port:

``monitor_port``
^^^^^^^^^^^^^^^^

Port, a number or a device name. See :option:`platformio device monitor --port`.

Example:

.. code-block:: ini

    [env:custom_monitor_port]
    ...
    ; Unix
    monitor_port = /dev/ttyUSB1

    ; Windows
    monitor_port = COM3

.. _projectconf_monitor_baud:

``monitor_baud``
^^^^^^^^^^^^^^^^

A monitor baud rate (speed). See :option:`platformio device monitor --baud`.

Example:

.. code-block:: ini

    [env:custom_monitor_baudrate]
    ...
    monitor_baud = 115200

.. _projectconf_monitor_rts:

``monitor_rts``
^^^^^^^^^^^^^^^

A monitor initial ``RTS`` line state. See :option:`platformio device monitor --rts`.

.. _projectconf_monitor_dtr:

``monitor_dtr``
^^^^^^^^^^^^^^^

A monitor initial ``DTR`` line state. See :option:`platformio device monitor --dtr`.
