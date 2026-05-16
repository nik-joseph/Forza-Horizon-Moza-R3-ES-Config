# Forza Horizon - Moza R3 ES SRP Lite Config

Custom input mapping profile for **Forza Horizon 5** using the **Moza R3** wheel with the **ES (Endurance Strip) SRP Lite** button box.

---

## Hardware

- **Wheel base:** Moza R3 (VID/PID: `0x346e0005`)
- **Button box:** ES SRP Lite
- **Pedals:** Gas, Brake, Clutch

---

## Button Mappings

### Axes

| Axis | Input | Index |
|------|-------|-------|
| Steering | Axis 0 | 0 |
| Gas | Axis 2 (inverted) | 2 |
| Brake | Axis 5 (inverted) | 5 |
| Clutch | Axis 6 (inverted) | 6 |

### Buttons

> Button indices are 0-based. A = 0, B = 1, X = 2, Y = 3.

| Label | Index | Mapped Action |
|-------|-------|---------------|
| A | 0 | Horn / UI Confirm |
| B | 1 | Handbrake / UI Cancel |
| X | 2 | UI X |
| Y | 3 | UI Y |
| DPad Up | 4 | Look Forward / UI Up |
| DPad Right | 5 | Look Right / UI Right |
| DPad Down | 6 | Look Back / UI Down |
| DPad Left | 7 | Look Left / UI Left / Activate |
| Left Paddle | 12 | Shift Down / UI LBumper |
| Right Paddle | 13 | Shift Up / UI RBumper |
| WIP | 19 | Convertible Trigger |
| FL | 20 | ANNA Activate / UI Back |
| CAM | 21 | Switch Camera |
| HOME | 24 | Radio Next |
| BOX | 33 | Quick Chat / UI Start |
| PL | 34 | Rewind / Mulligan |
| START | 36 | Open Map |
| S2 | 37 | Pause Game |

### D-Pad (Switch 0)

| Direction | Mapped Action |
|-----------|---------------|
| Up | UI D-Pad Up |
| Down | UI D-Pad Down |
| Left | UI D-Pad Left |
| Right | UI D-Pad Right |

---

## Input Contexts

| Context | Description |
|---------|-------------|
| `INPUTCONTEXT_RACING` | In-race controls (steering, pedals, buttons) |
| `INPUTCONTEXT_UI` | Menu navigation |
| `INPUTCONTEXT_RACING_UI` | HUD overlays during a race (ANNA, radio, quick chat) |
| `INPUTCONTEXT_RACING_CAMERA_ONLY` | Camera-only mode during a race |
| `INPUTCONTEXT_COPTER` | Drone/photo mode |
| `INPUTCONTEXT_ANNA` | ANNA voice assistant menu |
