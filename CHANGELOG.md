# Changelog

All user-facing updates and release notes for NAUQ Arch3D are documented here.

---

## [1.9.16] - 2026-09-28

### Performance & Usability
- **Instant DWG Import**: Background pre-warming of SketchUp's native CAD importer eliminates the initial loading freeze on first import.
- **In-App Auto-Update & Progress Display**: Seamless update checking and one-click downloading with real-time progress bar directly inside Settings Dialog.
- **Dynamic Block Detection**: Restored seamless detection and 3D generation for dynamic CAD door blocks with arch swings.

### Geometry & Architecture
- **Jamb & Lintel Alignment**: Opening tops and lintels automatically straighten to a clean rectangular cross-section even when jambs connect to columns or offset walls.
- **Precision Tolerance**: Calibrated door opening tolerances to prevent false-alarm positioning warnings on 90-degree door swing variants.
- **Enhanced Diagnostics**: Clear status indicators during drawing analysis to help verify detected door and window counts.

---

## [1.9.14] - 2026-09-24

### Rebranding & New Identity
- Extension officially renamed to **NAUQ Arch3D** (`nauq_arch3d`).
- Upgraded installer package to Trimble SketchUp extension standards.

### Door & Window Enhancements
- **Real Aluminum Profile Thickness**: Door leaf thickness now automatically adapts to the actual dimensions of your selected aluminum profile (Slim systems, Xingfa systems, or standard profiles).
- **Accurate Frame Rebate Fitting**: Door leaves now sit flush against the standard 20mm frame rebate, ensuring seamless alignment with outer frames.
- **Glass Centering**: Window and door glass panels are automatically centered along the leaf thickness.
- **Consistent 3D Preview**: Hardware positions (handles, locks, hinges) on front, back, or center faces now match 1:1 between the interactive 3D preview window and the 3D model in SketchUp.
- **Window Sill Preservation**: 4-sided window frames now maintain proper lower sills matching floor elevation.
