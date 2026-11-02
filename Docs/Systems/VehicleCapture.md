# Vehicle Capture & Tractor Recovery System

## Overview

Players can locate, secure, and use abandoned or lightly defended enemy vehicles. This system is historically grounded and especially prominent in early 2022 content.

## Core Loop

1. Locate abandoned / disabled / lightly crewed vehicle.
2. Clear remaining crew if necessary.
3. Secure the vehicle (hotwire / systems check / change markings).
4. Choose action:
   - Drive immediately (with penalties)
   - Call for recovery
   - Mark for later retrieval

## Tractor Recovery (2022 Focus)

- Civilian tractors are usable tools.
- Can tow immobilized or abandoned armored vehicles.
- Matches documented real-world events from the opening months of the invasion.
- Towing is slower, louder, and more vulnerable but highly effective for moving heavy armor without dedicated recovery assets.

## Rules by Period

- **Early 2022**: High density of abandoned Russian vehicles. Tractor towing is common and encouraged.
- **2023–2024**: Captures still possible but less opportunistic. Western vehicles become high-value targets.
- **2025–2026**: Captures remain possible but riskier due to drone saturation and more contested battlefields. Many abandoned vehicles are already damaged.

## Gameplay Effects

- Different handling, optics, and ammunition.
- Higher breakdown chance until properly assessed or repaired.
- Temporary friendly-fire risk if markings are not changed.
- Strong player satisfaction from turning enemy equipment against them.

## Implementation Notes (UE5)

- Use Chaos Vehicle or custom vehicle framework.
- Interaction system for securing / towing.
- Simple damage and reliability model for captured vehicles.
- Visual marking system (paint / flags / tape) to reduce friendly fire.
