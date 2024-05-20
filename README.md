# DEMULTIPLEXER1TO4
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/b6d81e6c-81ec-4f91-ae42-832a68f8facc)
# Truth Table
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/bb0a83c7-b4f3-463b-b422-f2ff65b1a0ee)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/dcd56444-97dd-454b-bddf-c7472c4af1de)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/03fbbbdf-8ae3-4653-8047-7d4cbf555ccb)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/f48cc07d-c76f-4d1c-8907-11e99711b751)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/a3075cf9-55ba-4478-b20c-c7128badef04)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/e07386db-69b3-4a5f-945f-b38929b801ea)
# VERILOG CODE:
module demux(s,I,y );

input I;

input [1:0]s;

output [3:0]y;

assign y[0] = ~s[1]&~s[0]&I;

assign y[1] = ~s[1]&s[0]&I;

assign y[2] = s[1]&~s[0]&I;

assign y[3] = s[1]&s[0]&I;

endmodule

# OUTPUT:
![image](https://github.com/SivaShankar33/DEMULTIPLEXER1TO4/assets/125188331/091f2d6e-55b5-4243-95bb-225eb7213c24)
