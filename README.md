# hello_world
trying
module abc;
bit clk;

always #5 clk = ~clk;

#1000 $finish();
endmodule
