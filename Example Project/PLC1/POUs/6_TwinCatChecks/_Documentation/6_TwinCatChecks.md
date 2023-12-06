___
[[_TOC_]]
___
# Introduction
At runtime these functions check the bounds of arrays or subrange types, the validity of pointer addresses, or division by 0. This to prevent a BSoD or page fault caused by a programming fault.

When a fault is detected, a counter is increased. For each check are one or two counters available. The counters can be found at _GVL_TwinCatChecks_.

Note: These implicit checks can NOT be called from a library.

See at the [Beckhoff- implicit checks](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_plc_intro/2527298443.html&id=) website for more details.