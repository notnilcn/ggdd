# Doxxing anti-cheat lmao
Make it so that if a player is detected as a cheater then it triggers an ai agent to literally fucking doxx them lmao. As in, the ai agent gets their ip address and then scrapes the internet for everything that related to them and then doxxes them.

# bullets and abilities optimization

  • P1: player movement/inventory/abilities/stats submodule carve-out; single chunk source of truth; static-vs-runtime inventory slot split; item/seeds.rs dead-tunable triage.
  • P2: bullet pooling + typed interop wrappers; oversized-component extraction (TerrainComponent, LocalPlayer, ItemSidebar); binder row-args signals starting with the bullet path; singletons out of hot paths; dirty-only overlay redraw.

