```ocaml
(* ~/whoami.ml *)

type person = {
  role      : string;
  company   : string option;
  location  : string;
  languages : string list;
  editor    : string;
  site      : string;
  x         : string;
}

let joaodematte = {
  role      = "software engineer";
  company   = None;
  location  = "brazil";
  languages = ["typescript"; "ocaml"; "rust"; "lua"];
  editor    = "neovim";
  site      = "https://joaodematte.com";
  x         = "https://x.com/joaodematte";
}
```
