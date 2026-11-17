# whoami.nix
```nix
{ ... }:
{
name = "Oliver Hagenauer";
handle = "Mowerick";

does = [
"software engineering"
"cybersecurity"
"full-stack web"
"NixOS & self-hosting"
];

projects = {
"wake-on-lan/wol-backend" = "Wake-on-LAN service for the local network, built around hybrid encryption";
"wake-on-lan/wol-app" = "React Native client for wol-backend";
"Mowerick/Dory" = "Cheatsheet for memorizing shortcuts of new tools";
"Mowerick/Reagent-In-Bags" = "Small Addon for World of Warcraft Forever to move the seperate Reagent Bag into the combined Backpack view"
};

contributions = {
"anechunaev/notion-electron" = "Notion desktop client for Linux";
"NixOS/nixpkgs" = "Maintaining the nixpkgs for anechunaev/notion-electron";
};

website = "https://oliverhagenauer.info";
}
```
