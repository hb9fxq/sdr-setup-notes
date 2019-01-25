# WIP: Native SDRplay source blocks
-----------------------------------

I’m working hard to make SDRPlay a part of this List - In my eyes with great performance for ham radio enthusiasts - `https://twitter.com/HB9FXQ/status/1010926288641626112 <https://twitter.com/HB9FXQ/status/1010926288641626112>`__

Now my code is feature complete and I’ve provided it to some friends for code review and testing. The manual will be updated soon.

BETA gr-sdrplay
---------------

Make sure to download and install API/HW Driver – v2.13 (20th June 2018) from sdrplay.com

.. code:: bash

   cd ~/wrk
   source ~/wrk/grc_wrk/default/setup_env.sh
   git clone https://gitlab.com/HB9FXQ/gr-sdrplay.git
   cd gr-sdrplay && mkdir build && cd build && cmake .. && make && make install
   sudo ldconfig
   
A sample file to open with GNU Radio is available under ~/wrk/gr-sdrplay/examples/development_gui.grc
   

