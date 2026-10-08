# RAW Planner V1.6

Adds a one-tap **FULL BODY** RAW alongside 🎲 AUTO.

Full Body builds a balanced six-exercise session with upper push, upper pull, lower-body and core coverage. Within those slots, exercise selection uses the existing recency, usage, difficulty, progression and variety scoring, and the final flexible slot favors muscle groups not used in the most recent RAW.

Run on Windows with: `python -m http.server 8080`


## V1.6
- Fixed FULL BODY button contrast on iPhone.
- Library search now updates only the result list, preserving keyboard focus for continuous typing on iOS.
- Added Cancel RAW; canceled sessions are discarded and never enter History, Progress, usage, or progression.
