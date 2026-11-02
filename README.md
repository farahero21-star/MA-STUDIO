# MA STUDIO — Ultimate AI Video & Voice Production Studio
Designed & Developed by Mohamed Ahmed

Android app (Kotlin + Jetpack Compose) with a pure-Kotlin engine module (`:core`).

## Build the APK (no Android Studio needed)
1. Create a GitHub repository and upload the contents of this project (or `git push`).
2. Open the **Actions** tab → **Build MA STUDIO APK** → wait for it to finish.
3. Download the artifact **MA-STUDIO-debug-apk** and install `app-debug.apk` on your phone.
The same workflow first runs the engine unit tests (`gradle :core:test`).

## Status (v0.2.0)
| Module | State |
|---|---|
| Dashboard, projects (create / rename / delete / backup zip / restore zip / auto-save), AR-RTL + EN-LTR | Implemented — not yet run on a device |
| Script editor (word/char counts, duration estimate, TXT import, sentence-safe chunking, chunk preview/edit) | Implemented; text engine unit-tested |
| Cinematic Audio Lab (WAV/MP3/M4A import, 7-band EQ, character controls, gate, hum removal, de-esser, compressor, saturation, echo, early reflections, 5 reverb rooms, stereo width, LUFS normalisation, true-peak limiter, 11 presets incl. editable MY SIGNATURE, undo/redo, bypass A/B, waveform + live spectrum, before/after LUFS/TP/peak/RMS/clipping/silence, WAV 16/24/32f export) | DSP engine unit-tested (JVM); Android UI/playback not yet run on a device |
| Voice Studio (voice cloning) | NOT implemented yet (Phase 3) |
| Video editor, multitrack timeline, MP4 export | NOT implemented yet (Phase 4) |

## Not yet in the Audio Lab
Speed / pitch (needs pitch-preserving time-stretch), emotional intensity, spectral noise reduction, hiss removal, de-clipping, breath reduction, multiband compression.
