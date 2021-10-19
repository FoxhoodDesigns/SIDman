# SIDman
6502 based SIDtune player

The SIDman (play on SID and Walkman) is a dedicated device for playback of SIDtunes. SIDtunes


FEATURES:
-Genuine 6502:        
-Stereo SID support:  
-Cycle Exact:         



The project works by having the Teensy emulate a small number of devices for the 6502 and SID to operate. Including:
-RAM Emulation:     which the 6502 reads/writes too.
-Address Decoding:  Handles chip-selection based on the addresses the 6502 is trying to read/write too.
-Clock Generator:   Generates the 985000Hz clock signal for the 6502.
-CIA Emulation:     Provides the 6502 with a set of timers for the proper timing needed to achieve SID Playback.
-S(I)D Loader:      Loads the SID files from an SD card into the emulated memory along with a small player code (for PSIDs).
