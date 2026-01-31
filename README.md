🎧 What Is Nova Player?
Nova Player is a sleek, dark-themed music player that produces real audio directly in the browser using the Web Audio API. No external audio files or libraries are required. Each of the 8 tracks in the playlist is synthesised live, and every song sounds completely unique because the bass, lead melody, pad, hi-hat rhythm, and effects are tuned individually per track.

✅ Features
Core Features
FeatureDescription▶️ Play / ⏸ PauseStart and stop playback with a single button⏭ Next / ⏮ PreviousNavigate between tracks instantly📊 Progress BarClick or drag to seek to any position in the track⏱️ Time DisplayShows current elapsed time and total track duration🔊 Volume ControlSmooth slider with a dynamic speaker icon (🔇 🔉 🔊)💿 Vinyl AnimationAlbum disc spins during playback and stops on pause🎹 Visualiser BarsAnimated bars that react to the playing state
Bonus Features
FeatureDescription📋 Playlist8 tracks rendered dynamically with active track highlighting⏭️ AutoplayAutomatically plays the next track when the current one ends🔀 ShuffleRandomises the next track selection🔁 RepeatLoops the current track continuously

🎼 Audio Engine
The audio engine is built entirely on the Web Audio API. Each track is made up of 5 layers that are synthesised in real time:
LayerDescription🎸 BassLow-frequency sine wave with LFO tremolo for a pulsing feel🎵 Lead ArpeggioNotes cycling every 2 seconds using unique waveforms per track🎹 Pad ChordsTwo detuned sawtooth waves with a slow fade-in and low-pass filter🥁 Hi-Hat RhythmFiltered noise bursts at 110 BPM, accented on beat 1🔊 Delay EchoFeedback loop delay that adds depth and a reverb-like tail
Every track uses different frequencies, waveforms, LFO speeds, and effects, so all 8 songs sound musically distinct from each other.

📁 Project Structure
CodeAlpha_MusicPlayer/
│
├── index.html          # Main HTML file (contains everything)
│   ├── <head>          # Fonts, CSS styles
│   ├── <body>          # Player UI layout
│   └── <script>        # JavaScript logic + Web Audio API engine
│
└── README.md           # This file

The entire project is contained in a single HTML file — no build tools, bundlers, or dependencies needed.


🚀 How to Run
Step 1 — Clone the Repository
bashgit clone https://github.com/YOUR_USERNAME/CodeAlpha_MusicPlayer.git
Step 2 — Open the File
bashcd CodeAlpha_MusicPlayer
open index.html

Simply open index.html in any modern browser such as Chrome, Firefox, Edge, or Safari.

Step 3 — Press Play 🎵
Click the ▶ button to start playback. The browser may ask for audio permission — click Allow.

💻 Technologies Used
TechnologyPurposeHTML5Page structure and semantic layoutCSS3Styling, animations, glassmorphism, flexbox layoutJavaScriptDOM manipulation, state management, event handlingWeb Audio APIReal-time audio synthesis and playbackCSS VariablesConsistent theming across the entire playerCSS AnimationsVinyl spin, visualiser bars, pulse ring, background shift

🎨 Design Highlights

Dark Glassmorphism — Semi-transparent cards with backdrop blur and subtle borders
Animated Background — Slow-shifting radial gradients that create depth
Spinning Vinyl — Conic-gradient disc that spins during playback
Pulse Ring — Glowing ring animation around the vinyl
Visualiser Bars — 12 animated bars that pause when music stops
Progress Bar — Thumb dot appears on hover for precise seeking
Custom Volume Slider — Styled range input with a glowing accent thumb


📝 How I Approached This Project

Planning — Broke down requirements into UI design, audio engine, controls, and playlist logic
UI Design — Built the dark-themed glassmorphism interface with smooth animations first
Audio Engine — Researched and implemented the Web Audio API to synthesise real sound
Track Tuning — Individually tuned all 8 tracks with unique frequencies and waveforms
Controls — Connected every UI element (play, pause, seek, volume, next, prev) to the live audio engine
Testing — Tested all features including autoplay, shuffle, repeat, and seeking


🏢 About the Internship
This project was completed as part of the Frontend Development Internship at CodeAlpha.
DetailInfoCompanyCodeAlphaProgramFrontend Development InternshipTaskTask 4 — Music PlayerWebsitewww.codealpha.techEmailservices@codealpha.tech

📌 Requirements Checklist
RequirementStatusMusic player interface using HTML & CSS✅ DoneJavaScript audio control (play, pause, next, previous)✅ DoneSong title, artist, and duration display✅ DoneProgress bar✅ DoneVolume control✅ DoneBonus: Playlist✅ DoneBonus: Autoplay✅ DoneBonus: Shuffle✅ DoneBonus: Repeat✅ Done

📜 License
This project was built for the CodeAlpha Internship Program and is intended for educational purposes.

Built with ❤️ by [Syed AHmed Ali Shah] — CodeAlpha Frontend Intern
