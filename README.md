# FPGA-based-LSTM
A novel FPGA-based intent recognition system utilizing deep recurrent neural networks.

In order to reproduce the same results as the corresponding paper, the following steps must be performed:
1. For each .cpp file create a seperate file in Vivado HLS/Vitis and copy its contends in the Vivado HLS/Vitis files. The "rnn_model_tb.cpp" contains the testbench therefore must be included in the appropriate testbench of the project.
2. Download and save in a accessable place the "dataset" folder. Afterwards, in the testbench file edit the present address of the folder in all previous addresses. Therefore, the model can import the correct inputs and produce the propriate results.
3. The model is ready to be tested in Vivado HLS/Vitis.




