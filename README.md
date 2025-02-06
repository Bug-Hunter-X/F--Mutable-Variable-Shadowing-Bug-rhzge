# F# Mutable Variable Shadowing Bug

This repository demonstrates a common error in F# related to mutable variables and shadowing. The `swap` function attempts to swap the values of two mutable variables, but due to shadowing, it fails to modify the original variables. The solution showcases how to correctly swap mutable variables in F#.