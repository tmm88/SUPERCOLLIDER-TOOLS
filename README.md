Core Utilities and Helper Libraries for SuperCollider



Quark Name
GitHub Repository
Description
Why Recommended
Institution/Org Affiliation



BatLib
supercollider-quarks/BatLib
Helper classes including StageLimiter for safe audio output and external methods for other Quarks.
Essential for live coding to prevent clipping; recommended in tutorials (e.g., co34pt’s live-coding guide).
None specific, but widely used in Dutch live-coding scenes (e.g., Algorave NL).


wslib
supercollider-quarks/wslib
GUI classes (e.g., RoundButton, SmoothSlider), MIDI file support (SimpleMIDIFile), SVG rendering, and auto-backup tools.
Highly starred (~16 stars, ~18 forks); a “must-have” for GUI and file handling, per Reddit threads.
Used in workshops at Royal Conservatoire The Hague for GUI design.


MathLib
supercollider-quarks/MathLib
Mathematical functions, distributions, and numerical tools for synthesis and patterns.
Ideal for algorithmic composition; listed in Awesome SuperCollider.
None specific, but popular in Utrecht University’s music tech courses.


json
supercollider-quarks/json
JSON parsing/generation for data interchange (e.g., web APIs).
Key for networked projects; used in STEIM workshops for sensor data integration.
STEIM (Netherlands): Used in their interactive music systems.


ddwCommon
supercollider-quarks/ddwCommon
Utilities for patterns, GUIs, and server management by Daniel W. Hill.
Enhances pattern workflows; often paired with ddwPatterns.
None specific, but taught in HKU University of the Arts Utrecht’s SuperCollider courses.

Pattern and Rhythm Extensions for SuperCollider



Quark Name
GitHub Repository
Description
Why Recommended
Institution/Org Affiliation



Bjorklund
redFrik/Bjorklund
Euclidean rhythm generator (e.g., Pbjorklund2 for duration arrays).
Popular for polyrhythms in live coding; featured in co34pt’s tutorials and Algorave NL events.
Game of Life Foundation (Netherlands): Used in their spatial music performances.


ddwPatterns
supercollider-quarks/ddwPatterns
Advanced pattern classes for complex sequencing and probability.
Recommended for algorithmic music; used in advanced workshops.
Royal Conservatoire The Hague: Taught in composition courses.


BBCut
snappizz/BBCut
Breakbeat cutting and sample slicing for rhythmic fragmentation.
Classic for breakcore/hip-hop; preserved from old SVN repo.
None specific, but used in STEIM’s live-coding workshops.


JITLibExtensions
supercollider-quarks/JITLibExtensions
Enhancements for Just-In-Time (JIT) Patterns and Proxies.
Improves live coding; frequently cited in scsynth.org.
IRCAM (France): Used in their real-time audio research.

GUI and Control Interfaces for SuperCollider



Quark Name
GitHub Repository
Description
Why Recommended
Institution/Org Affiliation



AllGui
supercollider-quarks/AllGui
GUI builders for synths, patterns, and scopes.
Simplifies interface creation; beginner-friendly, per tutorials.
HKU University of the Arts Utrecht: Used in student projects for interactive installations.


ixiViews
supercollider-quarks/ixiViews
Modular GUI views for oscillators, filters, and effects.
Intuitive design by Thor Magnusson; listed in Awesome SuperCollider.
STEIM (Netherlands): Featured in their artist residencies.


JITMIDIKtl
supercollider-quarks/JITMIDIKtl
MIDI keyboard tracking for JIT environments.
Seamless MIDI-to-Pattern mapping; popular in live coding.
IRCAM (France): Used in performance research.


APCmini
andresperezlopez/APCmini
Support for Akai APC Mini for clip launching and control.
Popular for Ableton-like workflows; used in performances.
ZKM (Germany): Adopted in their live electronics workshops.


Automation
neeels/Automation
Records/plays back GUI interactions for automated performances.
Useful for live sets; listed in Awesome SuperCollider.
None specific, but used in Utrecht University’s performance classes.

Synthesis and Audio Processing Quarks for SuperCollider



Quark Name
GitHub Repository
Description
Why Recommended
Institution/Org Affiliation



sc3-plugins
supercollider/sc3-plugins (via Quark: Generate_Quark.scd)
Community UGens for FFT, granular, and modal synthesis.
Expands core UGens; official recommendation for synthesis.
IRCAM (France): Contributed UGens for spectral processing; used in their research.


BandSplitter
scztt/BandSplitter.quark
Multi-band filtering and dynamic EQ.
Great for spectral work; listed in Awesome SuperCollider.
None specific, but used in ZKM’s sound design projects.


BinauralDecoders
madskjeldgaard/binauraldecoders
Binaural and ambisonic decoding for spatial audio.
Top for immersive sound; popular in VR/3D audio.
ZKM (Germany): Mads Kjeldgaard’s work aligns with their spatial audio focus.


DWGReverb
mysteryislandsmusic/DWGReverb
Physical modeling reverb with room-based reflections.
High-quality spatial effects; praised in synthesis threads.
Game of Life Foundation (Netherlands): Used in their multi-speaker installations.


AllBuf
madskjeldgaard/allbuf
Buffer management for multi-channel sample playback.
Streamlines granular synthesis; widely used.
Utrecht University: Student projects in granular synthesis.

Spatial and Multi-Channel Audio Quarks for SuperCollider



Quark Name
GitHub Repository
Description
Why Recommended
Institution/Org Affiliation



AmbIEM
supercollider-quarks/AmbIEM
Ambisonic encoding and decoding tools.
Core for spatialization; highly starred in Quarks org.
ZKM (Germany): Used in their ambisonic research and performances.


SpeakersCorner
supercollider-quarks/SpeakersCorner
Multi-speaker tools: latency compensation, EQ, FX.
Essential for installations; recommended in scsynth.org.
Game of Life Foundation (Netherlands): Core to their 192-speaker Wave Field Synthesis system.


Influx
supercollider-quarks/Influx
Multi-speaker latency and effects chaining.
Complements SpeakersCorner; precise spatial control.
Game of Life Foundation (Netherlands): Supports their spatial audio projects.


3Dj
supercollider-quarks/3Dj
3D audio positioning with joystick control.
Fun for interactive 3D sound; used in VR/games.
STEIM (Netherlands): Featured in interactive installations.

Specialized and Experimental Quarks for SuperCollider



Quark Name
GitHub Repository
Description
Why Recommended
Institution/Org Affiliation



arduino
supercollider-quarks/arduino
Interface for Arduino boards for sensor input/control.
Great for interactive art; extends SC to physical computing.
STEIM (Netherlands): Used in their sensor-based music projects.


AlgaLib
vitreo12/AlgaLib
Live coding framework with node-based synthesis graphs.
Modern alternative to core SC; popular in live coding scenes.
Royal Conservatoire The Hague: Student projects in live coding.


SuperDirt
justinfrankel/SuperDirt
TidalCycles integration for text-based live coding.
Essential for Tidal users; ~1k+ stars in Tidal community.
Game of Life Foundation (Netherlands): Used in their live-coding performances.


Conductor
supercollider-quarks/Conductor
Environment-based GUI and control system.
For complex control flows; by Ron Kuivila.
IRCAM (France): Used in their performance systems research.


Boids
woolgathering/boids
Flocking algorithm for particle synthesis/sonification.
Experimental; generates emergent soundscapes.
Utrecht University: Student projects in sonification.


Modality-toolkit
modality-team/Modality-toolkit
Framework for mapping controllers to SC parameters.
Advanced controller integration; used in performances.
STEIM (Netherlands): Developed during their workshops for gestural control.


Wacom
supercollider-quarks/Wacom
Support for Wacom tablets as input devices.
Niche for gestural control; used in interactive art.
STEIM (Netherlands): Featured in their artist residencies for tablet-based music.

