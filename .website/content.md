beatline is a terminal-based real-time music visualizer. it captures audio from a microphone or an audio file and turns it into live visuals directly in the terminal. no gui frameworks, no external visual tools — just audio processing and character graphics.

## what it does

beatline includes multiple visual modes:

• waveform — live audio waveform  
• spectrum — frequency bars  
• pulse — volume-reactive pulses  
• circlebands — circular band energy visual  
• zones — frequency-separated regions (sub, bass, mids, treble)  
• squares — intensity-based glowing blocks  

each mode reflects a different aspect of the signal.

## requirements

• python 3.8+  
• numpy  
• sounddevice  
• soundfile  
• blessed  
• curses (builtin on macos / linux)

macos users need microphone permission. a virtual audio driver like blackhole helps if you want to visualize system audio.

## why i built this

i was lowk bored and wanted to experiment with lightweight terminal visualization, hackable music visualizer that lives in the terminal. it became a way to explore audio processing and terminal graphics together.