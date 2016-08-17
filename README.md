Abstract
========

En route to ever larger processor performance, processor designers are
facing complex problems to the conventional way of performance improvement. To
cover the rising demand of computing power many manufactures take meanwhile
multi-core chip design into consideration.

IBM, Sony and Toshiba developed therefore a new processor architecture the Cell
Broadband Engine (CBE) which promise a variety of performance bene\-fits. To
achieve a high degree of parallelism the CBE unites a pipeline, multi core
architecture with simultaneous multi threading on a highly integrated chip.
The CBE combines a Power Processor Element (PPE) and eight Synergetic
Processing Elements (SPE). The SPU is a RISC processor with a 128-bit single
instruction multiple data (SIMD) unit for single and double precision
computation which handles the most computational workload. The PPE acts like
a control or monitoring system for the rest of the system.

To solve a specific task entirely new approaches have to be developed. This not
only results in adapting the task to the architecture, but it also results in a
variety of approaches which have to be taken into account to solve a given
problem. With respect to its performance and adaptability each approach has to
be tested to determine the best solution.

The problem that yields out of that situation will be examined for a ray tracer
which will be adapted to the CBE architecture. In the frame of this work,
different approaches are supposed to be introduced whereby the single approaches
with respect to its performance and its capability for ray tracing are examined.
Goal of the work is to develop an optimized architecture for ray tracing on the
CBE with focus on performance.

As a result, this optimized architecture will be able to render medium sized
scenes at acceptable rates.
