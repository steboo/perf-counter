PerfCounter
===========

A few lines of sample code to read performance counters in Windows, then pump them out to a local [Carbon](https://github.com/graphite-project/carbon) server in plaintext over UDP. Not intended to be an end solution.

Building
--------

Builds in Visual Studio 2010, but can probably easily build in older or newer versions.

Links against pdh.lib and ws2_32.lib.