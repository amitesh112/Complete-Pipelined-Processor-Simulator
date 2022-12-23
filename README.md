# Complete-Pipelined-Processor-Simulator

Implemented a simulator for an out-of-order processor implementing and APEX-ISA with an Issue Queue, a load-store queue and a reorder buffer that uses
register renaming.


Specific Processor Details-:

8 Architectural Registers(R0-R7) with 15 Physical Registers(P0-P14).

The Processor has three Functional Units:

1. An Integer Function Unit with a latency of one clock cycle.

2.A Logical Function Unit with a latency of one clock cycle.

3.A Multiplier Function Unit with a latency of four clock cycles.

4. Two Forwarding Buses, with Early Broadcasting Implementation.

5. An Issue Queue with 8 enteries, a Reorder Buffer with 12 enteries and an Load-Store Queue with 4 enteries.

6. It also consists of a static branch prediction with a negative offset in branch instruction indication that the branch is taken and vice versa for the
   positive offset.
