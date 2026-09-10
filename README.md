# RunMineEscape Resource Pack — 0.50.0

This repository provides the public Minecraft resource pack required by the RunMineEscape Paper server.

## Server download URL

`https://raw.githubusercontent.com/bobuildington/RME-resourcepack/main/RunMineEscape-26.2.zip`

Current SHA-1: `d759c3dbe91fb61dd998c47abe7b88f1e6958de6`

Minecraft 26.2, resource-pack format 88. Includes the Forge, eleven RME ore models (including new Dragon ore), five tree-trunk models, depleted ore, and matching resource item-model definitions. Existing block identities are preserved; Dragon appends state 16. No Fabric mod is required. Servers send this pack automatically when configured with its HTTPS download URL and SHA-1.

The pack is released alongside the matching private RunMineEscape project. Only client pack assets and this README are published here; server source, generation datapacks, configuration, worlds and profiles remain private. Server deployments should pin the raw URL to the tested commit (replace `main` in the URL with that commit ID) and use the matching hash to avoid stale-cache mismatches.

When the pack changes, rebuild it from the private RunMineEscape project, replace `RunMineEscape-26.2.zip` here, commit and push the update, then set the server's `resource-pack-sha1` to the new SHA-1.
