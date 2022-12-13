`move_line_up`

Moves all cursors 1 line up, removing any selections.
Repeating this will remember the vertical position of the cursors,
even when moving across shorter lines.

--- Examples ---

The cursor remembers its vertical position,
even after moving across the shorter line.
┌──────────────────────────────┐     ┌────────────────────────────┐     ┌────────────────────────────┐
│ This is a longer line.       │     │ This is a longer line.     │     │ This is a longer l[i]ne.   │
│ Shorter line.                │ --> │ Shorter line.[]            │ --> │ Shorter line.              │
│ This is another lo[n]g line. │     │ This is another long line. │     │ This is another long line. │
└──────────────────────────────┘     └────────────────────────────┘     └────────────────────────────┘