# CSP Libraries

[Communicating Sequential Processes](https://en.wikipedia.org/wiki/Communicating_sequential_processes) is a useful tool for thinking about and modeling the behaviour of event-based systems. It is particularly useful for modeling systems that consist of two or more concurrent processes. CSP is quite expressive, but building up every model from scratch can still be a complex and time-consuming procedure. The libraries contained in this simplify that procedure by capturing some useful CSP fragments in a reusable form. The current libraries are:

 * lib_tinyos_2.csp -  A collection of process definitions for building models of [TinyOS](http://www.tinyos.net/) programs, as described in [Modeling and Analysis of TinyOS Sensor Node Firmware: A CSP Approach](http://hdl.handle.net/10092/5372).
 * lib_mobile_channel.csp - A collection of process definitions for modeling occam-&pi; style mobile channels in CSP.
