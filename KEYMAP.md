# Cradio / Ferris Sweep — Simplified Programmer Layout

34-key split. **Plain QWERTY** on the base layer (no home-row mods).

Thumbs:
`L-inner: TAB / hold → Layer 2 (symbols)`   `L-outer: ENTER / hold → Layer 1 (nav · nums · mods)`
`R-inner: SPACE`                              `R-outer: BACKSPACE` (always plain — no layer hold)

Combos:
`Q+W → ESC` · `Z+X → ⌘Z` · `X+C → ⌘⇧Z` · `K+L → ;` · `L+' → :` · `,+ . → _`
`D+F → {` · `J+K → }`

Tri-layer: hold **both** thumb layer keys (TAB + ENTER) → Layer 3 (F-keys · Bluetooth · reset)

---

## Layer 0 — Base (plain QWERTY)

```
╭─────┬─────┬─────┬─────┬─────╮   ╭─────┬─────┬─────┬─────┬─────╮
│  Q  │  W  │  E  │  R  │  T  │   │  Y  │  U  │  I  │  O  │  P  │
├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
│  A  │  S  │  D  │  F  │  G  │   │  H  │  J  │  K  │  L  │ ' " │
├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
│  Z  │  X  │  C  │  V  │  B  │   │  N  │  M  │ , < │ . > │ / ? │
╰─────┴─────┴─────┼─────┼─────┤   ├─────┼─────┼─────┴─────┴─────╯
                  │ TAB │ ENT │   │ SPC │ BSP │
                  │ L2  │ L1  │   │     │     │
                  ╰─────┴─────╯   ╰─────┴─────╯
```

Type normally — letters behave like a regular keyboard.

---

## Layer 1 — Nav · Numbers · Modifiers — hold ENTER

```
╭─────┬─────┬─────┬─────┬─────╮   ╭─────┬─────┬─────┬─────┬─────╮
│ INS │  1  │  2  │  3  │  4  │   │HOME │PGDN │PGUP │ END │  :  │
├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
│ DEL │  5  │  6  │  7  │  8  │   │  ←  │  ↓  │  ↑  │  →  │  ;  │
├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
│ ⇧   │ ⌃   │ ⌥   │ ⌘   │  9  │   │ ⌘   │ ⌥   │ ⌃   │ ⇧   │  0  │
╰─────┴─────┴─────┼─────┼─────┤   ├─────┼─────┼─────┴─────┴─────╯
                  │     │     │   │     │     │
                  ╰─────┴─────╯   ╰─────┴─────╯
```

Hold left thumb **ENTER** for arrows, numbers, and explicit modifier keys (no accidental ⌘/⌃ while typing).

---

## Layer 2 — Symbols — hold TAB

```
╭─────┬─────┬─────┬─────┬─────╮   ╭─────┬─────┬─────┬─────┬─────╮
│  `  │  [  │  {  │  }  │  \  │   │  ^  │  (  │  )  │  ]  │  ~  │
├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
│  !  │  @  │  #  │  $  │  %  │   │  *  │  -  │  =  │  +  │  |  │
├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
│  ;  │  :  │  "  │  '  │     │   │  &  │  _  │  /  │  ?  │     │
╰─────┴─────┴─────┼─────┼─────┤   ├─────┼─────┼─────┴─────┴─────╯
                  │     │     │   │     │     │
                  ╰─────┴─────╯   ╰─────┴─────╯
```

Dart / Python / Swift essentials: `{}[]()`, `#`, `;`, `:`, `_`, quotes, operators.

---

## Layer 3 — Tri (System · F-keys · Bluetooth) — hold TAB + ENTER

```
╭─────┬─────┬─────┬─────┬─────╮   ╭─────┬─────┬─────┬─────┬─────╮
│RESET│     │     │     │ BT0 │   │ F1  │ F2  │ F3  │ F4  │ F5  │
├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
│BOOT │     │     │     │ BT1 │   │ F6  │ F7  │ F8  │ F9  │ F10 │
├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
│ STD │     │     │BTCLR│ BT2 │   │ F11 │ F12 │⌘⇧4  │     │     │
╰─────┴─────┴─────┼─────┼─────┤   ├─────┼─────┼─────┴─────┴─────╯
                  │     │     │   │     │     │
                  ╰─────┴─────╯   ╰─────┴─────╯
```

---

## Quick reference for coding

| Need | How |
|------|-----|
| `{` `}` | Hold TAB, or combo D+F / J+K |
| `;` `:` | Hold TAB, or combo K+L / L+' |
| `_` | Hold TAB, or combo ,+. |
| Arrows | Hold ENTER |
| ⌘ ⌃ ⌥ ⇧ | Hold ENTER, bottom row |
| ESC | Combo Q+W |
| Undo / Redo | Combo Z+X / X+C |

---

## Key positions (for editing combos)

```
 0  1  2  3  4      5  6  7  8  9
10 11 12 13 14     15 16 17 18 19
20 21 22 23 24     25 26 27 28 29
         30 31     32 33
```