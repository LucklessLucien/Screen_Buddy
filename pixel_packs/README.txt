PIXEL PACKS

Each folder in this directory is one complete character. Pixel's Settings menu lets you switch packs.

To make a new pack:
1. Copy an existing pack folder and give the copy a new folder name.
2. Edit pack.json. Change "name" to the label shown in Settings. Set "faces" to the name of the folder containing the PNG expressions. Set "voice" to a Kokoro voice ID, and adjust "speed" and "pitch" if you like.
3. Edit personality.txt to describe the character's personality and speaking style. Keep the shared tool and safety rules in the app; this file is an extra character profile.
4. Add PNG images to the faces folder. The filename (without .png) is the expression name, such as idle.png, happy.png, or thinking.png. Pixel can only show emotions for which that pack provides an image; missing moods fall back to its idle or first available image.
5. Reopen Settings. The new pack appears in the selector. Switching packs also switches its saved conversation and notes.

Voice models are shared by all packs, so don't copy the Kokoro model files into each pack. The original Pixel conversation and notes remain in pixel_history.json and pixel_memory.json.
