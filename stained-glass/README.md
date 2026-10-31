# Window Glass Planner

A single-file tool for planning a fake stained-glass look on two windows using Grafico fluted / reeded glass film.

**Defaults** (all editable in Settings)
- Two windows, 69 × 170 cm glass each, shown side by side
- One Clear and one Tea sheet, 152 × 100 cm each
- 0.5 cm gap between cuts, 1 cm snap grid
- Flutes run parallel to the sheet's 100 cm edge (check this on the roll)

## Use it
Open `index.html` in any browser. It has no build step and no dependencies.

1. **New piece:** choose Clear or Tea, a width and height, and the flute direction, then press **Cut from sheet**. The piece is taken from what's left of that sheet. If it won't fit, it isn't added, and you're told how much is left and the largest free area.
2. **Drag** pieces onto either window (touch or mouse). They snap to the grid and to window and neighbouring edges. Drag a piece into the tray to take it off a window. Overlaps show as red dashed outlines.
3. **Resize:** press and hold a piece on a window for about half a second. Keep holding and drag to resize from the nearest corner, or let go and drag any of the handles. A piece stops growing when its sheet has no more film for it. Tap empty glass (or press Esc) when you're done. The **Resize** button in the selected-piece panel does the same.
4. **Selected piece:** edit its size or position, nudge it, rotate it 90° (which also turns its flutes), duplicate it or delete it.
5. **Cutting sheets** shows where each piece is cut from on each sheet. The cuts are re-packed automatically. A piece whose flutes have to run across the sheet's flutes is cut turned.
6. **Save version** downloads a `.json`. **Load** restores one.
7. **Print spec** gives the window overlay (each piece's ID, size and x, y from the top-left of the glass), both cutting sheets with sheet positions, and a full cut list. You can print it or download it as a standalone HTML file.

Your work is also autosaved in the browser.
