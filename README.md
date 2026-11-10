repository: motivation-direction-works/remediation-brigade
cross_reference:
  - subsystem: "executive-deployment-manifest"
  - tracking: "supply-chain-overhead-breakdown"
tags:
  - #ExecutiveBrief
  - #SupplyChain
  - #OverheadBreakdown
  - #QuickSetupInstructions

Executive Operational Brief: The Remediation Brigade & Sentinel Pods
This is the operational blueprint designed for executive leadership, capital backers, and project managers—the folks who manage payroll, clear supply chains, and greenlight deployment while the engineering team turns the wrenches.
1. Overhead & Operational Cost Structure
To maintain a fast-moving, agile brigade without bureaucratic bloat, overhead is lean and hyper-focused on raw throughput:
 * Engineering & Field Technicians (Core Payroll):
   * 1 Systems Architect / Lead Engineer (oversight, sensor calibration, firmware management).
   * 2 Field Assembly Techs (wiring, soldering, mechanical integration, 3D printing/hull assembly).
   * 1 Logistics & Deployment Operator (field site setup, marine transport, regulatory/site clearing).
 * Facility & Utilities:
   * Small light-industrial workshop/garage space (600–1,200 sq ft) with basic benchtop power, ventilation for soldering/printing, and water testing tank access.
 * Capital Expense (CapEx) Hardware:
   * High-speed industrial 3D printers (FDM/SLA for custom enclosures and impellers).
   * Electronics bench setup (oscilloscopes, soldering stations, multimeters, bench power supplies).
   * Field deployment vehicle/trailer and small utility boat.
2. Materials & Supply Chain Sourcing Matrix
Everything in the bill of materials (BOM) is off-the-shelf and available through existing global commercial logistics (Mouser, Digi-Key, Amazon Supply, McMaster-Carr, local marine supply yards).
| Component Category | Specific Off-The-Shelf Item | Primary Function | Sourcing Channel |
|---|---|---|---|
| Compute & Logic | Raspberry Pi 4 / ESP32-S3 boards | Central processing, logic control, sensor reading | Standard electronics distributors |
| Telemetry & Radio | SX1262 LoRa Mesh Modules / 4G LTE HATs | Long-range mesh network & cloud dashboard feeds | Commercial radio/IOT suppliers |
| Sensor Array | Optical refraction sensors, fluorometric VOC sniffers, hydrostatic pressure sensors | Hydrocarbon detection & bilge pressure monitoring | Industrial sensor suppliers |
| Fluid Mechanics | 12V DC heavy-duty bilge pumps, oleophilic drum belts, mini centripetal separators | Oil/water separation & fluid transfer | Marine supply & industrial fluid handlers |
| Hulls & Enclosures | IP68 waterproof Pelican-style cases, recycled HDPE twin-catamaran hulls | Modular flotation & electronics weatherproofing | Industrial hardware & marine plastics |
| Power Storage | 12V LiFePO4 battery packs + flexible solar panels | Continuous off-grid power & field operations | Commercial energy & battery distributors |
3. Quick Setup & Field Deployment Instructions
Step 1: Bench Setup & Firmware Flash (15 Minutes)
 * Load the pre-compiled M.A.D. Core Remediation OS image onto the micro-SD card/ESP32 flash.
 * Plug in the pre-wired sensor harness (optical sniffer, telemetry radio, pump relay).
 * Power up the unit and verify live telemetry connection on the M.A.D. Core Operations Dashboard.
Step 2: Mechanical Assembly & Hull Lock (30 Minutes)
 * Mount the electronics enclosure into the IP68 waterproof bay on the catamaran hull or Sentinel Pod casing.
 * Connect the 12V DC bilge pump leads to the auto-relay outputs.
 * Attach the oleophilic skimmer drum belt or inline oleophilic filter module to the intake/exhaust manifold.
Step 3: Water Deployment & Calibration (15 Minutes)
 * Drop the unit into the water line (marina slip, bilge sump, or open spill perimeter).
 * Run automated self-test via mobile web interface to verify pump draw, sensor baseline, and mesh signal strength.
 * Lock unit to autonomous mode—the brigade begins active hydrocarbon monitoring and remediation immediately.
# Executive-Operational-Brief-The-Remediation-Brigade-Sentinel-Pods