# Open City

A single-file, zero-dependency HTML5 Canvas top-down open-world driving and railway game (`game.html`). Made via Codex (GPT 6.2 Sol). 
Contains original music (human-made)! 

## Features

- **Procedural Endless World:** Seeded streaming chunks featuring city districts, expressways, four old-town styles, regional/international airports, parks, hospitals, and multi-tile nature reserves with rivers and lakes.
- **Six Game Modes:**
  - **Free Roam:** Explore at your own pace and set custom map waypoints.
  - **Police Chase:** Outrun up to five coordinated pursuit units; destroy pursuers with nitro for `+100 KM` each.
  - **Uber / Bus / Truck:** No-time-limit passenger, multi-stop transit, and freight routes with clean-driving, distance, and takedown bonuses.
  - **Train:** Drive a three-car train along an elevated railway network in either direction with manual junction switching (`A`/`D`) between jobs.
- **Vehicle Garage & Economy:** Every kilometre driven and job completed earns spendable KM (saved in `localStorage`). Car, Bus, Truck, and Train each have independent performance upgrades (engine, turbo, cooling, brakes) and cosmetics (paints, liveries, wheels, underglow/markers, body parts).
- **Trophy Room:** Spend earned KM on 12 permanent collectibles.
- **Dynamic World Systems:** Day/night cycle with headlights, streetlamps, and late-night expressway motorbike gangs; road pickups (Speed Boost, Ghost Drive, Infinite Nitro); responsive touch controls; and an interactive pan/zoom city map with nearby landmark search.

## Running

Open `game.html` directly in any modern desktop or mobile web browser. No build step, server, or external assets required.

## Controls

| Action | Keys |
| :--- | :--- |
| Accelerate / Brake & Reverse | `W` `S` / `↑` `↓` |
| Steer / Queue Train Junction | `A` `D` / `←` `→` |
| Handbrake / Drift (Emergency Brake on Train) | `Space` |
| Turbo Boost (once unlocked) | `Shift` + Accelerate |
| Accept Job / Next Job | `E` / `N` |
| Cycle Mode / Mode Menu | `C` / `V` |
| Garage / Map / Trophy Room | `G` / `M` / `B` |
| Recover Vehicle / Pause | `R` / `Esc` (`P`) |
