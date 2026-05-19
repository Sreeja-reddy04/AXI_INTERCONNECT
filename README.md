# AXI INTERCONNECT INTRODUCTION
The AXI Interconnect connects multiple masters and slaves, enabling efficient communication within a system-on-chip (SoC). It 
performs address decoding, routing, and arbitration while ensuring high performance, low latency, and protocol-compliant data transfer across the system.

# AXI INTERCONNECT FEATURES
• Supports simultaneous transactions for parallel data transfer 
• Performs address decoding and routing efficiently 
• Implements arbitration for multi-master access control 
• Supports multiple outstanding transactions
• Provides scalable connectivity between multiple masters and slaves
• Supports flexible interconnect topologies 
• Low latency and  high bandwidth 
• Ensures high-performance communication in complex systems
• Maintains transaction ordering and protocol compliance 

# AXI CHANNELS AND SIGNALS
1.Write Address Channel (AW)
• Signals: AWADDR, AWVALID, AWREADY, AWLEN, 
AWSIZE, AWBURST 
2. Write Data Channel (W)
• Signals: WDATA, WVALID, WREADY, WSTRB, WLAST 
3. Write Response Channel (B)
• Signals: BRESP, BVALID, BREADY 
4. Read Address Channel (AR)
• Signals: ARADDR, ARVALID, ARREADY, ARLEN, 
ARSIZE, ARBURST 
5. Read Data Channel (R)
• Signals: RDATA, RVALID, RREADY, RRESP, RLAST
