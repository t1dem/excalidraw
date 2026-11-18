---
name: Dismiss menus and return to drawing
paths: [packages/excalidraw/hooks/useOutsideClick.ts, packages/excalidraw/components/dropdownMenu/**]
url: /
---
Open the main menu in the upper left and assert that its menu items are visible. Click empty drawing canvas, away from the menu. Assert that the menu items are no longer visible and the main menu is closed. Stop after this assertion.
