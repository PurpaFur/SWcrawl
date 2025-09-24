# Star Wars–Style Crawl Generator

A browser-based Star Wars opening crawl generator written in plain HTML, CSS, and JavaScript. It recreates the iconic opening sequence from the Star Wars films, with the classic title card, episode text, subtitle, and body crawl.

## Features

- **Default content**: Comes preloaded with the classic Star Wars opening text.
- **Custom text**: Replace the title card, episode, subtitle, and body with your own.
- **Starfield**: Adjustable star count with toggle.
- **Typography**: Crawl width, base font size, and letter spacing controls.
- **Animation timing**: Sliders for crawl duration, title hold/fade, and logo hold/fly-out.
- **Perspective**: Adjustable tilt and perspective depth.
- **Logo**: Default Star Wars logo with adjustable display timing.
- **Music**:
  - Load a local audio file (royalty-free or licensed).
  - Delay start, sync offset, and fade-out controls.
  - Fade-out can be set to align with the crawl ending.
- **Responsive**: Works in modern browsers, adapts to full screen.

## Font Requirement

This project uses the **Star Jedi Outline** font for the logo. Download it here:

[Star Jedi Outline Font](https://www.fontspace.com/star-jedi-outline-font-f9643)

### Installation

1. Download the font `.ttf` file from the link above.
2. Install it on your system:
   - **Windows**: Right-click the `.ttf` file and select *Install*.
   - **macOS**: Double-click the `.ttf` file and click *Install Font*.
   - **Linux**: Copy the `.ttf` file to `~/.fonts` or use your distro’s font manager.
3. Restart your browser to ensure the font is recognized.

If the font is not installed, the logo will fall back to a system font.

## Usage

1. Open `crawl.html` in a modern browser (Chrome, Edge, Firefox).
2. Use the default Star Wars text, or customize via the left panel.
3. (Optional) Load an audio file from your system.
4. Click **Full Screen + Start**.
5. Record the playback with screen capture if you want an `.mp4`.

## Development

- Pure HTML/CSS/JS, no frameworks.
- Uses CSS custom properties for animation timing and layout.
- Canvas used for starfield rendering.
- Includes a small self-test suite for text splitting.

## Notes

- The original Star Wars score is copyrighted and not included. Use your own licensed or royalty-free music.
- Tested on Chrome/Edge/Firefox at 1080p and 4K.

## License

MIT License. Free to use, modify, and distribute. See [LICENSE](LICENSE) for details.

---

© 2025. This project was AI-assisted. You may share and modify without attribution.
