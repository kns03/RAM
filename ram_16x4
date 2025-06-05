module ram_16x4(dout,din,en,clk,addr);
input clk,en;
input [3:0] din,addr;
output reg [3:0] dout;

reg [3:0] memory [15:0];
always @(posedge clk) begin 
	if (en) begin
		memory[addr] = din;
	end
	else begin
		dout = memory[addr];
		end
	end

endmodule
