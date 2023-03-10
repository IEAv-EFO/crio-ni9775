# NI 9775

Code to use the module 9775 with cRIO-9053 via FPGA.

- The `record mode` saves snapshots of data in the internal memory of the real-time OS. 
This is mode can reach up to 20 MS/s.

- The `continuous mode` saves the data with limited speed, as fast as you can read the FIFO the module keeps acquiring data.
