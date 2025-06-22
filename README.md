# Spice Opam Repo

An opam repo with ports of various packages to help build Opam/Dune packages
supporting the spice project. Even though spice does not use Opam packages,
various essential development tools (e.g. ocamllsp, ocamlformat) are distributed
as Opam packages. To use these tools with spice they must be compiled with a
relocatable OCaml compiler. Convincing Opam/Dune to use the correct OCaml
compiler while building tools requires porting various compiler meta-packages,
which is the purpose of this repository.
