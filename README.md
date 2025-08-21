# Cipher bot

A browser-based chat interface that encrypts messages using three different cipher methods.

## Features

- **Three cipher types**: Caesar, Symbol, and Reverse ciphers
- **Chat-like interface**: WhatsApp-style message bubbles with timestamps
- **Command history**: Navigate previous messages with arrow keys (terminal-style)
- **Interactive UI**: Dynamic send button states and smooth animations

## Usage

Open `index.html` in a web browser and interact with the bot using these commands:

### Encryption Commands

```
caesar: your message here
symbol: your message here
reverse: your message here
```

### Information Commands

```
whatis(caesar)
whatis(symbol)
whatis(reverse)
```

## Cipher Methods

- **Caesar Cipher**: Shifts characters alphabetically by 13 positions (ROT13)
- **Symbol Cipher**: Replaces specific letters with visually similar symbols (i→!, l→1, s→$, etc.)
- **Reverse Cipher**: Reverses each word individually while maintaining word order

## Limitations

- Case-insensitive input only
- No message persistence between sessions
- Fixed cipher parameters (e.g., Caesar shift of 13)
- Single-user interface (no real chat functionality)

## Technical Details

- **Frontend**: Vanilla HTML, CSS, JavaScript with jQuery
- **Styling**: Custom CSS with chat bubble layout and background imagery
- **Features**: Responsive textarea, smooth animations, message persistence

## File Structure

```
├── index.html          # Main interface
├── src/
│   ├── style.css       # Styling and layout
│   ├── logic.js        # Cipher algorithms and UI logic
│   ├── active.png      # Send button icon (active)
│   ├── disabled.png    # Send button icon (disabled)
│   ├── hover.png       # Send button icon (hover)
│   ├── game.jpg        # Background image
│   └── royal.ttf       # Custom font file
└── README.md
```
