KTF Injection Molding Calculator - Version 7

CYCLE-TIME REFERENCE WORKFLOW
- No bulk data entry is required.
- Add a comparable existing part only when one is useful during normal quoting.
- Actual cycle is the only required comparison value.
- Optional ERP/process fields:
  * Reference resin
  * Part thickness (in)
  * Part mass (g)
  * Part shut height (in)
  * Shot weight (g)
  * Cavitation
  * Cooling time
  * Recovery dwell / screw recovery time
  * Fill time
  * Pack + hold time
  * Part ejection / removal time
- Save the comparison only when you want it available to future quotes.
- Incomplete reference jobs are allowed.
- Richer reference records receive more trust in future calibration.
- Current quote now also accepts optional part mass (g).

CYCLE LOGIC
The physics/geometry model remains the baseline.
Saved actual BRI cycle times are blended based on similarity.
Detailed actual cycle-stage times can also nudge the model's component estimates.
Recovery is retained as reference data but is not blindly added to cooling because those times can overlap.

DATA STORAGE
Saved references remain local to the browser/device.

UPDATING GITHUB
Replace:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

Service-worker cache: v7
