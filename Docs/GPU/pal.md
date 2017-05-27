Maps a color in the palette to another color.

---

**There is 2 palettes in LIKO-12**:

* **The Images palette**: Which affects images __ONLY__.
* **The Drawing palette**: Which affects all other GPU functions.

---

## Usage:

---

### 1. Reset the whole palette:

---

#### Syntax:
```Lua
pal(false,false,[P])
```

---

#### Parameters:

* **[P] (Number)**: (0) will reset the Drawing palette, (1) will reset the Images palette, (nil/false) will reset the both palettes.

---

### 2. Reset a specific color to it's default:

---

#### Syntax:
```Lua
pal([C],false,[P])
```

---

#### Parameters:

* **[C] (Number)**: The color to reset to it's default.
* **[P] (Number)**: (0) will reset the color in the Drawing palette only, (1) will reset the color in the Images palette only, (nil/false) will reset the color in both palettes.

---

### 3. Map a specific color:

---

#### Syntax:
```Lua
pal([A],[B],[P])
```

---

#### Parameters:
* **[A]**: The color to replace.
* **[B]**: The color which will replace A.
* **[P]**: (0) will affect the Drawing palette, (1) will affect the Images palette, (nil/false) will affect the both palettes.