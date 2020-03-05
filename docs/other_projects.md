## Other related projects

Here is a short overview of other projects related to Lua and types, prompted by [this question at Github](https://github.com/hishamhm/tl/issues/24):

* [Typed Lua](https://github.com/andremm/typedlua) was a research project started as @andremm's PhD thesis at PUC-Rio, co-advised by @mascarenhas which also got contributions from some students over time. It was a big exploration of optional typing for Lua and lots of lessons were learned there (see the various published papers!). The focus being on research results, the implementation itself for most of the time remained more of a proof-of-concept of this research, rather than a practical tool. The original developers moved on to other things, and the repo hasn't had updates in a year.
* [Titan](https://github.com/titan-lang/titan) started as a community project between myself (maintainer of [LuaRocks](https://luarocks.org) and a PUC-Rio alumnus), the Typed Lua devs mentioned above, plus grad students at PUC-Rio @hugomg and @gligneul who at the time were studying optional typing and compilation techniques. The idea was to join forces and build something that would make everyone happy: I wanted a Lua for programming-in-the-large, the Typed Lua people wanted a typed dialect of Lua, and grad students wanted a high-performance Lua. The "companion language" concept seemed to fit the bill, being a "Lua-ish language you'd use instead of falling back to C or doing contortions to please the JIT compiler gods".
* [Pallene](https://github.com/pallene-lang/pallene) started as a fork of Titan because, as you can guess, design-by-committee is challenging, especially when people in the committee have different goals. :) Since grad students work under a deadline to produce results, the ideal situation was to have the academic side of Titan fork into its own project, which is currently active, healthy and continues with the evolution of the "companion language" concept. Titan went dormant as the others moved on: and as far as I'm concerned, Titan is now dead but I hope it will prove to have been a worthwhile kickstarting effort once Pallene starts to bear fruit.

So **tl;dr:**: as of 2020, Typed Lua and Titan aren't active, Pallene is a project aiming to generate native-code modules for use with the Lua interpreter, and tl is a transpiler for a dialect of Lua plus types.