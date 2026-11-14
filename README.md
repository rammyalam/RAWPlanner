# RAW Planner V1.6

Adds a one-tap **FULL BODY** RAW alongside 🎲 AUTO.

Full Body builds a balanced six-exercise session with upper push, upper pull, lower-body and core coverage. Within those slots, exercise selection uses the existing recency, usage, difficulty, progression and variety scoring, and the final flexible slot favors muscle groups not used in the most recent RAW.

Run on Windows with: `python -m http.server 8080`


## V1.6
- Fixed FULL BODY button contrast on iPhone.
- Library search now updates only the result list, preserving keyboard focus for continuous typing on iOS.
- Added Cancel RAW; canceled sessions are discarded and never enter History, Progress, usage, or progression.


## V1.7 updates
- Tap **+ Add Set** within any exercise to append another set (0 reps initially).
- Every exercise has a free-text **Exercise note** saved when you Finish RAW; notes display in RAW History and Library exercise details.
- Every new set starts at **0 reps**; previous weight recommendations remain available.
- Existing history and localStorage key remain unchanged. Deploy by uploading the contents of this folder to the existing GitHub Pages repository.

## V1.8 – Custom RAW
- Today → **+ Build Your Own RAW** opens a searchable/filterable exercise picker.
- Add/remove exercises and move them up/down before starting. Tap **Start Custom RAW**.
- While a RAW is active, **+ Add Exercise** lets you choose another exercise from the library.
- No custom templates are stored; only completed RAWs are saved to History as before.
- Previous performance, set entry, notes, swapping and cancellation work in custom RAWs.
