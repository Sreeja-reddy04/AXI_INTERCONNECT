## AXI INTERCONNECT INTRODUCTION
The AXI Interconnect connects multiple masters and slaves, enabling efficient communication within a system-on-chip (SoC). It 
performs address decoding, routing, and arbitration while ensuring high performance, low latency, and protocol-compliant data transfer across the system.

## AXI INTERCONNECT FEATURES
- Supports simultaneous transactions for parallel data transfer 
- Performs address decoding and routing efficiently 
- Implements arbitration for multi-master access control 
- Supports multiple outstanding transactions
- Provides scalable connectivity between multiple masters and slaves
- Supports flexible interconnect topologies 
- Low latency and  high bandwidth 
- Ensures high-performance communication in complex systems
- Maintains transaction ordering and protocol compliance 

## AXI CHANNELS AND SIGNALS
- Write Address Channel (AW)
  : AWADDR, AWVALID, AWREADY, AWLEN, 
AWSIZE, AWBURST 
- Write Data Channel (W)
  : WDATA, WVALID, WREADY, WSTRB, WLAST 
- Write Response Channel (B)
  : BRESP, BVALID, BREADY 
- Read Address Channel (AR)
  : ARADDR, ARVALID, ARREADY, ARLEN, 
ARSIZE, ARBURST 
- Read Data Channel (R)
  : RDATA, RVALID, RREADY, RRESP, RLAST
## HANDSHAKING MECHANISM
- VALID–READY handshake used in 
all channels 
- Transfer only when both VALID 
and READY are high 
- VALID → sender, READY → 
receiver 
- Supports independent flow 
control
- Ensures reliable data transfer
## TEST CASES
- FIXEDBurst transaction 
- INCREMENT Burst transaction
- WRAP Burst transaction
- Arbitration(Multiple-Master Access)
 ## CONCLUSION 
- Developed and verified an AXI interconnect using a UVM-based environment 
with AXI VIP, ensuring protocol compliance 
- Validated burst transactions, arbitration, address alignment, and VALID/READY 
handshaking through constrained-random testing 
- Performed protocol checks and functional coverage analysis, achieving 
comprehensive verification with 100% coverage
