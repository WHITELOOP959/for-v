# 🎂 Birthday Experience — For V

## Folder structure
```
birthday-v/
├── index.html       ← the whole experience lives here
├── voiceover.mp3    ← DROP YOUR RECORDING HERE (rename it to exactly this)
└── README.md        ← you're reading this
```

---

## How to run it
1. Open this folder in VS Code
2. Drop your voice recording in here, renamed to `voiceover.mp3`
3. Right-click `index.html` → Open with Live Server  
   *(install the "Live Server" VS Code extension if you don't have it)*
4. Click anywhere on screen to start

---

## How to edit — quick reference

Everything you need to change is in the `CONFIG` block  
at the very top of the `<script>` section in `index.html`.  
You don't need to touch anything else.

### 🎤 Change the audio file name
```js
voiceoverFile: 'voiceover.mp3',   // rename your file to match this
```

### ⏱️ Sync animations to your voice
All times are in **milliseconds** (1000 = 1 second).  
Record your voiceover first, then note the timestamps  
of what you're saying and update the `timings` block.

### 🎨 Change colors
Edit the `colors` block. All colors use hex codes (#rrggbb).  
Google "hex color picker" to find any color you want.

### ⚡ Change animation speed / style
Edit the `animation` block:
- `shootingStarFrequency` — lower number = more shooting stars
- `constellationBuildFrames` — lower = constellation draws faster
- `zoomAmount` — 1.0 means no zoom, 1.15 means zoom in more
- `fireworkBurstInterval` — lower = fireworks launch faster

### ✏️ Change any text
Edit the `text` block. Change names, lines, anything.

---

## How to share with her
1. Go to **github.com** and create a free account
2. Create a new repository called `for-v`  
3. Upload all files in this folder (including voiceover.mp3)
4. Go to Settings → Pages → set source to `main` branch  
5. She gets a link like: `https://yourusername.github.io/for-v`

That's it. She clicks the link, it opens, fullscreen takes over.
