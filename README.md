# Batch Level Distillation
This is the official repository for Batch Level Distillation (BLD), presented in the paper:<br/>
Online Continual Learning under Extreme Memory Constraints

**Abstract.** Continual Learning (CL) aims to develop agents emulating the human ability to sequentially learn new tasks while being able to retain knowledge obtained from past experiences. In this paper, we introduce the novel problem of Memory-Constrained Online Continual Learning (MC-OCL) which imposes strict constraints on the memory overhead that a possible algorithm can use to avoid catastrophic forgetting. As most, if not all, previous CL methods violate these constraints, we propose an algorithmic solution to MC-OCL: Batch-level Distillation (BLD), a regularization-based CL approach, which effectively balances stability and plasticity in order to learn from data streams, while preserving the ability to solve old tasks through distillation. Our extensive experimental evaluation, conducted on three publicly available benchmarks, empirically demonstrates that our approach successfully addresses the MC-OCL problem and achieves comparable accuracy to prior distillation methods requiring higher memory overhead.

**UPDATE:** we are in the process of filing a patent based this work. For this reason, there might be delays on the upload of the code.
