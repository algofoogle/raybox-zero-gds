# raybox-zero-gds

These are the results of hardening [raybox-zero, `ew` branch](https://github.com/algofoogle/raybox-zero/tree/ew).

For the spec of my design (and in particular my top module and the intended way for it to be wired up to the clock, LA, and IO pads), see: [EWSPEC](https://github.com/algofoogle/raybox-zero/blob/ew/doc/EWSPEC.md).

Note also that [`top_ew_algofoogle`](https://github.com/algofoogle/raybox-zero/blob/ew/src/rtl/top_ew_algofoogle.v) is my top module, which instantiates the main design (`rbzero`) and throws in a bunch of other debug mux stuff.

I suspect its ports will need another wrapper, yet, to match `user_project_wrapper` net names...?

