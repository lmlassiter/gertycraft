# GertyCraft

GertyCraft is a private-server extension of All the Mods 10 focused on Create Aeronautics.

Current candidate:

- GertyCraft 0.1.1
- Minecraft 1.21.1
- NeoForge 21.1.241
- All the Mods 10 7.2
- Create 6.0.10
- Create Aeronautics 1.3.0
- Sable 2.0.3
- Distant Horizons 3.2.0 beta (client-side)

`I'm Fast` is intentionally omitted because its unbounded rideable-vehicle AABB behavior is a documented conflict with Sable that can cause log spam, watchdog stalls, and severe lag.

The requested Axiom editor is not bundled. Axiom is Fabric-only, and the required Sinytra compatibility layer currently crashes when Axiom and Aeronautics' Sable physics library are loaded together on NeoForge 1.21.1. Keeping it out is required for a launchable pack.

## Install

1. Download the latest `GertyCraft-*-CurseForge.zip` release asset.
2. Open the CurseForge app.
3. Choose Minecraft, then **Import** or **Create Custom Profile → Import**.
4. Select the downloaded ZIP and let CurseForge install the pinned files.
5. Allocate 12 GiB to Minecraft. The profile recommends this automatically.
6. Get the current server address from the private GertyCraft group.

Do not substitute newer mod versions unless a new GertyCraft release explicitly pins them.

This is an unofficial derivative configuration and is not affiliated with or endorsed by the ATMTeam, the Create team, or the Create Aeronautics team.
