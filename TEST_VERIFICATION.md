# GOF Fleet Tank Sounding Calculator

## Test & Verification Record

Version:
v8.4.3

Verification date:
26 September 2026

Developer:
Mohamad Razri Abdul Razak

Operational verification:
Calculator functionality tested together with Chief Engineer (CE).

Platforms verified:

- Mobile browser
- PC / laptop browser
- GitHub Pages live deployment

Fleet verification:
Confirm all vessel datasets currently present in the calculator load successfully.

Dolphin Satu verification readings:

- No.1 Fuel Oil Tank (C): 470 mm
- No.1 Fuel Oil Tank (P): 2240 mm
- No.1 Fuel Oil Tank (S): 2300 mm
- No.2 Fuel Oil Tank (P): 2300 mm
- No.2 Fuel Oil Tank (S): 2350 mm
- B/T Fuel Oil Tank (S): 660 mm
- Fuel Oil Day Tank (P): 750 mm
- Fuel Oil Day Tank (S): 750 mm
- Observed trim: 0.000 m

Verified Dolphin Satu result from v8.4.3:

- Total volume: 46.517 m³
- Total volume: 46,517 L
- Total mass: 39.525 tonnes
- BDN mode: OFF
- Calibration source mode: approved sounding/calibration dataset

Unit testing:
The above readings were successfully verified using:

- mm
- cm
- m

Deployment verification:

- Vessel selector populated
- Tank table populated
- No unexpected OUT OF RANGE result for the supplied readings
- Required assets returned successfully
- No captured JavaScript console errors during final live verification

PWA packaging verification:

- Manifest, relative GitHub Pages paths, app-icon dimensions, and versioned service-worker cache behavior were verified locally.
- Manual device verification remains required for iPhone Safari Add to Home Screen, iPhone standalone launch, and Android Chrome installation.

Important:
This calculator is an operational aid and does not replace approved vessel sounding/calibration documents or vessel procedures.

Copyright:
© 2026 Mohamad Razri Abdul Razak. All rights reserved.
