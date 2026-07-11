# -FIFO-Memory-using-Verilog
designing synchronous FIFO Memory


here memory of 16x4 is there with parameters 
data width : 4, 
address_width  : 4, 
ram_depth : 16.

Output signals are full,empty and data_out;

Input signals are data_in,clk,reset,write_en,read_enable and 
Write ,read pointers and status count are declared(reg type),data ram is declared(wire type) 
to indicate signals so that proper implantation of fifo can be shown while simulation


