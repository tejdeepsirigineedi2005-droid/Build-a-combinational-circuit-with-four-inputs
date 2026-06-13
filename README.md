# Build-a-combinational-circuit-with-four-inputs
module top_module( 
    input [3:0] in,
    output out_and,
    output out_or,
    output out_xor
);
    assign out_and=&in;
    assign out_or=|in;
    assign out_xor=^in;

endmodule
 circuit diagr
am
 <img width="720" height="1600" alt="WhatsApp Image 2026-06-13 at 11 06 51 AM" src="https://github.com/user-attachments/assets/7d03ed86-c59a-46dc-b7d1-c304362f639e" />
output:
<img width="1366" height="721" alt="Screenshot 2026-06-13 110444" src="https://github.com/user-attachments/assets/ee6410b8-1ea7-4275-8787-b5f439164fd3" />
