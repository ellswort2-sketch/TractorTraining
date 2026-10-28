# Tractor virtual lab — v1.5 (speed and travel simulation)

## Open locally
Extract the entire ZIP. Open Tractor_5105M_Virtual_Lab.html in a browser.
Keep the assets folder alongside the HTML. The webpage now uses separate
image files to stay below GitHub's browser upload limit for an individual file.
Internet is only needed for the optional YouTube video.

## GitHub Pages
Upload BOTH Tractor_5105M_Virtual_Lab.html AND the entire assets folder
into the same Pages source folder. Preserve the assets directory name.
Replace the previous HTML with this updated version. Do not rename assets.
Commit, wait for deployment, and refresh the page (Ctrl+Shift+R if necessary).
Existing homepage link:
<a href="Tractor_5105M_Virtual_Lab.html">Tractor Virtual Lab</a>
Do not overwrite an existing index.html homepage.

## Activity
Explore the supplied photographs and manual reference views. Try the
representative PowrReverser gear/range simulation and hydraulic-cylinder
bench, complete 15 formative questions, then write the two explanations.
Download the printable HTML report or print/save it to PDF for Canvas.
The report records first answers; explanations require instructor review.
No automatic Canvas grade transfer or identity verification is included.
Completed reports and explored components persist locally when storage is
available. An unfinished quiz does not resume after reloading. On a shared
computer, download your report and start a new attempt for the next user.

## Configuration and accuracy
Four newly supplied views are identified by the instructor as a 2012 5105M.
They show 1-4 speed gears with Neutral/Park, F/N/R lever, electronic hitch
controls, and separate PTO engagement and speed-selection controls.
The yellow control engages/disengages the PTO. The separate black lever
selects PTO speed position. The earlier yellow-paddle description is corrected.
Thirteen supplied original stills are included, plus separate manual examples.

OMSJ10032 covers multiple 5M models including 5105M/5105ML. References:
20-1 front console; 20-5 low-profile mechanical hitch; 20-7 cab electronic
hitch; 55-6 speed/range/reverser; 70-1 rear SCVs; 70-4 rear SCV operation.
OMSJ10033 section 25-2 identifies the transmission/hydraulic oil filler cap
and separate level dipstick. The 2012 cab and low-profile references remain
separately captioned. Photos alone do not confirm every installed option.
The transmission bench remains a representative manual-based 16F/16R
PowrReverser, not an asserted digital twin of the photographed tractor.

All assessment images are original photos/manual excerpts. The separately
created AI presentation enhancement is not used for component assessment.
Manual images and John Deere names copyright Deere & Company. Video
stills supplied by instructor. Retain credits and confirm institutional use.
Not affiliated with or endorsed by John Deere.

## Verification
JavaScript syntax and asset references checked. Original assessment flow,
photo controls, transmission selection, hydraulics and reports were browser
tested. New PTO question and 2012 image references added in this revision.
This is a photographic teaching simulation, not a 3D/physics driving model.

## v1.3 clarification
Questions 6 and 11 now include their reference illustrations. Transmission
wording is clearer and identifies the simulation explicitly. All question
illustrations can be opened at full size. Replace the HTML file; existing
assets do not change. Existing browser reports remain in the earlier version
namespace; the revised activity starts a new attempt.

## v1.4
Question 14 uses the requested wording and includes manual reference 55-6.
Only the HTML needs replacing; image assets are unchanged.

## v1.5 — speed and travel
The transmission bench now estimates speed from engine RPM, gear, range,
direction, rear tire size and assumed wheel slip. It uses the supplied
OMSJ10032 manual section 55-7 table at 2,200 RPM with 16.9-30 R1 tires;
section 55-11 supplies tire correction factors. Reverse has its own table
values. Speed = table speed × RPM/2200 × tire factor × (1-slip/100).

Start the travel clock, apply RPM changes, and watch signed position versus
time. Depress the simulated clutch before changing gear/range. Stop the
simulated drivetrain before changing direction. Release the clutch to resume.
Forward raises position; reverse lowers it; total distance counts both.
Pause freezes the simulation clock, and does not disengage the drivetrain.
Download the travel CSV to examine settings, speed, position and distance.
The 60-second example demonstrates forward travel, increased RPM, a stop,
reverse travel, and a final stop.

This is an approximate constant-speed teaching model: acceleration, braking,
inertia and terrain are not simulated. Clutch depression stops motion instantly.
Actual tire rolling radius, pressure, loading and slip affect field speed.
The linear RPM scaling and user-entered slip are estimates.

Upload the revised HTML AND assets folder (including new manual-94.png and
manual-98.png). Keep all existing images. Questions 6, 11 and 14 retain their
reference illustrations. The v1.5 activity starts a fresh browser attempt.
JavaScript syntax, speed calculations, forward/reverse integration and the
example graph were checked. This model does not replace operator training.

## Hydraulic flow animation correction
The orange pressure line animates from the valve into the cylinder; the blue
return line animates from the cylinder back toward the valve. Extension and
retraction swap the pressure and return sides, including animation direction.
Only the HTML changed; the existing assets remain unchanged.

## Mowing challenge — MOW-1.0
Upload Tractor_Mowing_Challenge.html beside Tractor_5105M_Virtual_Lab.html.
Replace the lab HTML to add the Mowing challenge navigation link. The new game
is self-contained and requires no additional images or services.

Practice is untimed and pausable. Challenges last five real minutes, cannot
be paused, and have fixed field, mower and scoring conditions. A completed
challenge is labeled eligible for class comparison; early finishes are not.
Students download an HTML report (or print to PDF) for Canvas; JSON includes
the sampled travel log. Reports include route/coverage map, category scores,
errors and student reflection. Browser-local best score is not a class leaderboard.
Reports are editable formative records, with no authentication or automatic
Canvas grade transfer. Instructor review is required.

Scoring: coverage 40 (full at 70% cut), pass accuracy 25, target operation 20,
control procedures 15. The latter three scale up until 25% coverage, preventing
a tiny cut area from earning most points. Target: 5–9 km/h, 1900–2200 RPM.
These are classroom game targets, not manufacturer instructions. Simplified
6 m rear mower, 91.44 × 48.77 m football playing area, 0.5 m scoring grid.
No end zones, soil physics, PTO ratio modeling, slopes, or collisions.

Keyboard: focus field, hold W/up to drive, A/D or left/right to steer, S/down
to brake; release drive to stop. Touch users hold the labeled buttons. Begin
with B3, engage PTO at 1000 RPM while stopped, then raise RPM to 2200. Clutch
before gear/range changes. Stop and disengage PTO before selecting reverse.
Raise mower for turns; turn in the 6 m headland. Recommended first class use:
practice together, then one five-minute attempt, download report and explain
strategy. Rank only completed challenges from the same build and conditions.

Verification: browser checks of driving, PTO, field rendering and report;
deterministic checks of cut area, distance, no-cut with raised mower/reverse,
shift interlocks, time expiry, early finish eligibility and score behavior.
