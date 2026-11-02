# Ukraine Volunteer FPS

**PC-first Call of Duty-style modern military FPS** set during the Russo-Ukrainian war from **24 February 2022** to the present (November 2026).

## Core Pillars (Non-Negotiable)

- **Player Role**: You are always an **international volunteer** from your own country, fighting only with Ukrainian forces or the International Legion.  
  **You never play as Russian / aggressor forces.**

- **Historical Accuracy**: Real weapons, real vehicle designations, real Ukrainian units, and strict timeline of equipment availability.

- **Key Systems**:
  - Vehicle capture & appropriation (including civilian tractor towing of abandoned armor, especially strong in 2022)
  - Level-based weapon progression that is **timeline-locked**
  - Realistic unit appearance (period-correct uniforms, patches, gear)
  - Tactical evolution of the war reflected in gameplay

- **Platform**: PC (Windows) first. Console versions later if viable.

## Engine Recommendation

**Primary recommendation: Unreal Engine 5**

Reasons:
- Excellent for high-fidelity FPS and large environments
- Strong vehicle physics and networking
- Nanite + Lumen for realistic visuals
- Good multiplayer framework (including dedicated servers)
- Strong support for complex systems (drones, destruction, inventory)

**Alternative**: Unity 6 (HDRP) if the team prefers C# and faster iteration on systems.

## High-Level Project Structure (Unreal Engine 5)

```
ukraine-volunteer-fps/
├── README.md
├── DESIGN.md                  # Full master design document
├── Docs/
│   ├── Equipment-Timeline.md   # Real weapons & vehicles by year
│   ├── Units.md                # Real Ukrainian units & appearance notes
│   ├── Systems/
│   │   ├── VehicleCapture.md
│   │   ├── Progression.md
│   │   └── Drones-EW.md
│   └── Multiplayer.md
├── Content/                   # (UE5 Content folder once project is created)
│   ├── Characters/
│   ├── Weapons/
│   ├── Vehicles/
│   ├── Maps/
│   ├── UI/
│   └── VFX/
├── Source/                    # C++ modules if needed
├── Config/
├── Plugins/
└── .gitignore
```

## Current Status

- Design fully locked
- Repository initialized
- Engine decision: Unreal Engine 5 recommended
- Next steps: Create UE5 project, flesh out DESIGN.md and equipment lists, prototype player controller + vehicle capture

## Contributing / Building

This is currently a design + pre-production repository.  
Actual Unreal project files will be added once the base project is created locally and pushed.

---

**Play only as a volunteer. Historical accuracy first.**
