# Greetings, I'm Razushi.

```nix
let
  student = {
    university = "University of Technology Sydney";
    year = 2024;
  };
in
builtins.trace "Student at ${student.university}. Class of ${toString student.year}." student
```

```nix
let
  player = {
    level = 19;
    debuff = "University";
    faithPenalty = -5;
    vitalityPenalty = -1;
  };
in
player
```

```nix
let
  contributions = [
    "nixpkgs"
    "Flathub"
  ];
in
builtins.trace "Currently contributing to: ${builtins.toString contributions}" contributions
```

```nix
let
  language = "Java";
  project = "procedural generated voxel frameworks";
in
builtins.trace "Developing ${project} in ${language}." project
```

## Socials

You can find me at:
- **[NixOS](https://wiki.nixos.org/wiki/User:Razushi)**
- **[Twitter](https://twitter.com/razushi283)**
- **[Reddit](https://www.reddit.com/user/Cultural_Yam/)**

## Monitering

I'm watching over these repos, some interesting stuff is being done.
- **[serpent-os/moss](https://github.com/serpent-os/moss)**
- **[NixOS/nixpkgs](https://github.com/NixOS/nixpkgs)**
- **[hyprwm/Hyprland](https://github.com/hyprwm/Hyprland)**
- **[YaLTeR/nirl](https://github.com/YaLTeR/niri)**
