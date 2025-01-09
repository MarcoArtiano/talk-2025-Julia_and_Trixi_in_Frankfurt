# Introduction to Julia

We use a [Pluto.jl](https://github.com/fonsp/Pluto.jl) notebook
to introduce Julia. This code was developed with Julia v1.10.7.
To run the code, you need to download and install Julia first,
e.g., from the official
[download website](https://julialang.org/downloads/).


## Working from a terminal (e.g., Linux or macOS)

Open a terminal and run

```bash
julia -e 'import Pkg; Pkg.activate(pwd()); Pkg.instantiate(); import Pluto; Pluto.run()'
```

in this directory.
Then, open the Pluto notebook `Introduction_to_Julia.jl`.


## Windows

You can double-click the `open_pluto.bat` file in this directory
to start Pluto.
Then, open the Pluto notebook `Introduction_to_Julia.jl`.

Alternatively, you can open the Julia REPL in this directory, e.g.,
by navigating to this directory in the Windows File Explorer and
typing "julia" the address bar.
A console window should open. There, execute

```julia
import Pkg; Pkg.activate(pwd()); Pkg.instantiate(); import Pluto; Pluto.run()
```

in the Julia REPL. Then, open the Pluto notebook mentioned above.
