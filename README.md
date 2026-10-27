# Ball Rush Cursor

A stylized arrow pointer with layered cyan and violet edging, a subtle neon glow, and a small sparkle.

## Downloads

### Windows

- [Download the Windows ZIP](https://raw.githubusercontent.com/remeey/ball-rush-cursor/main/BallRushPointer.zip)
- [Download the Windows cursor file](https://raw.githubusercontent.com/remeey/ball-rush-cursor/main/BallRushPointer.cur)

### Mac artwork

- [Download the Mac PNG](https://raw.githubusercontent.com/remeey/ball-rush-cursor/main/BallRushPointer-Mac.png) — transparent, 64 × 64 pixels, designed for a 32-point pointer at 2× scale.
- [View the scalable SVG](https://github.com/remeey/ball-rush-cursor/blob/main/BallRushPointer-Mac.svg)

## Install on Windows

1. Download and extract `BallRushPointer.zip`.
2. Open **Settings → Bluetooth & devices → Mouse → Additional mouse settings**.
3. Select the **Pointers** tab.
4. Under **Customize**, select **Normal Select**, then click **Browse**.
5. Choose `BallRushPointer.cur`, click **Open**, then click **Apply**.
6. To restore the Windows default, return to the **Pointers** tab, choose the **Windows Default** scheme, and click **Apply**.

The Windows file changes the regular arrow pointer. Text and resize pointers remain unchanged.

## Use the custom cursor on Mac

macOS does not include a built-in way to replace the system arrow with arbitrary artwork. Apple’s built-in pointer options let you adjust its size and colors. To use the Ball Rush artwork as a system cursor, you need a third-party cursor utility such as [Mousecape](https://github.com/alexzielenski/Mousecape).

**Compatibility note:** Mousecape uses macOS internals rather than a supported Apple cursor-customization feature. It may not work on every macOS version, and macOS updates can affect it. Mousecape is separate software; download it only if you’re comfortable installing it.

### 1. Download the files

1. Download [BallRushPointer-Mac.png](https://raw.githubusercontent.com/remeey/ball-rush-cursor/main/BallRushPointer-Mac.png) to your Mac.
2. If you want to inspect or resize the artwork, use the [SVG source](https://github.com/remeey/ball-rush-cursor/blob/main/BallRushPointer-Mac.svg).
3. Open the [Mousecape releases page](https://github.com/alexzielenski/Mousecape/releases) and download its latest listed release.
4. Open the downloaded ZIP. Move **Mousecape.app** into your **Applications** folder, then open it.

### 2. Create a Ball Rush cursor cape

A “cape” is Mousecape’s name for a cursor theme.

1. In Mousecape, choose **File → New** or press **Command-N**.
2. Select the new cape and choose **File → Edit** or press **Command-E**.
3. In the editor, add a cursor with the **+** button.
4. Set its cursor type to the normal arrow (often called **Arrow**).
5. Drag `BallRushPointer-Mac.png` into the cursor image area.
6. Set the cursor size to **32 × 32 points**. The image is 64 × 64 pixels, which is 2× resolution.
7. Set the hotspot to **X: 3, Y: 2**. The hotspot is the exact point that clicks; this places it at the arrow tip.
8. Save the cape with a name such as **Ball Rush**.

### 3. Apply it

1. In Mousecape, select your **Ball Rush** cape.
2. Choose **Capes → Apply Cape**.
3. If you want Mousecape to reapply the cursor after signing in, open the **Mousecape** menu and choose **Install Helper Tool**. macOS may ask you to approve the helper or enter your Mac password. Only approve it if you chose to install Mousecape and trust the copy you downloaded.
4. To return to the standard Mac pointer, choose **Capes → Restore Defaults**.

If Mousecape cannot apply the cape, the app or helper may not be compatible with your macOS version. You can still make the built-in pointer easier to see: open **Apple menu → System Settings → Accessibility → Display → Pointer**, then adjust its size, outline color, or fill color.

## License and credits

The Windows cursor and Mac artwork are provided in this repository for personal use. Mousecape is a separate third-party project; its licensing and support are handled by its authors.
