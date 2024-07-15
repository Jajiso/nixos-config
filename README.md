# nixos-config

[ ] TODO: make this readme pretty
[ ] TODO: create a script to do all the setup
[ ] TODO: create a configuration for vm with windows to game



1. make a copy of your hard `hardware-configuration.nix` into sensitive/ folder
2. make a copy of `variables.example.nix`, rename it to `variables.nix` and copy it into sensitive folder
3. (optional) modify the flake as you want to be able to use stable or unastable, etc.
4. Use one of the hosts already created or create your own (the `configuration.nix` and the `home.nix` should be in the hosts/my-host/)
5. Modules are separated between `modules/nixos/` (here goes all the modules that are for the whole system) or `modules/home/` (here goes all the modules that are for user level home-manager)
6. `themes/` here you can declare all the possible themes you want to use for your nixos 

