About this notes
================

.. figure:: ./img/cc_non_commercial_4.0.png
   :alt: Creative Commons Attribution-NonCommercial 4.0 International

   Creative Commons Attribution-NonCommercial 4.0 International

Please consider a small donation to tip me a coffee: `https://paypal.me/hb9fxq <https://paypal.me/hb9fxq>`__


Post to the USKA academy workshop
(`https://www.uska.ch/2018/02/06/uska-academy-2018/ <https://www.uska.ch/2018/02/06/uska-academy-2018/>`__ ) around GNU Radio, a few peers reached out to me with questions about how to get started, without the LiveUSB system used in the workshop in Lucerne.

This tutorial might help - might give some directions how to setup a SDR-Linux environment. Please feel free to edit or pullrequest my Markdown notes on my [GitHub repository](https://github.com/krippendorf/sdr-setup-notes).

**All steps are tested with best effort only for Linux mint 18.3 - no Support!**

Goals
-----

-  Option 1) Create a VM to explore some SDR stuff under Linux (start here: :doc:`Setup VM <setup_VM>` )
-  Option 2) Install SDR stuff on a bare metal PC (start here: :doc:`Setup requirements <setup_REQUIREMENTS>`)
-  Get some tools around RTL-SDR Dongles
-  Get a up-to-date GNU Radio installation - from Source, not Distro packages
-  Target Hardware UHD, RTL based sticks, PlutoSDR, HackRF One

Drawbacks
---------

-  GNU Radio setup can be a pain. It’ll cost a bit time to install manually. Installation from source has some good advantages. This tutorial is about installation from source and not using a distribution’s package manager.
-  Performance in a VM is not as good as a native Linux install on bare metal. Cool graphic stuff might not work and do not expect super-high data rates when routing USB devices from the HOST to the GUEST.
-  The setup takes some time, but gives you some good practice with linux setup procedures
-  *I can not give any support if anything goes wrong*

What else to explore?
---------------------

A curated list of some cool, SDR related tools to discover

-  `https://www.rtl-sdr.com/big-list-rtl-sdr-supported-software/ <https://www.rtl-sdr.com/big-list-rtl-sdr-supported-software/>`__

Devices used in this Tutorial
-----------------------------

-  `https://greatscottgadgets.com/hackrf/ <https://greatscottgadgets.com/hackrf/>`__
-  `https://www.rtl-sdr.com/product/rtl-sdr-blog-v3-r820t2-rtl2832u-1ppm-tcxo-sma-software-defined-radio-dongle-only/ <https://www.rtl-sdr.com/product/rtl-sdr-blog-v3-r820t2-rtl2832u-1ppm-tcxo-sma-software-defined-radio-dongle-only/>`__
-  `http://www.analog.com/en/design-center/evaluation-hardware-and-software/evaluation-boards-kits/adalm-pluto.html <http://www.analog.com/en/design-center/evaluation-hardware-and-software/evaluation-boards-kits/adalm-pluto.html>`__
-  `https://www.ettus.com/product/details/USRP-B200mini-i <https://www.ettus.com/product/details/USRP-B200mini-i>`__

