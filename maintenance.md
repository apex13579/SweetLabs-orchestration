# Home Lab Maintenance Checklist
-[ ] Daily/Weekly: Backup Verification

-[ ] Check logs for successful backup completion.

-[ ] Perform a restore test on a non-critical file to ensure data integrity.

-[ ] Verify off-site/cloud sync status (3-2-1 strategy).

-[ ] Monthly: System & Software Updates

-[ ] Run security patches for the host OS (Proxmox/Linux).

-[ ] Update mission-critical container images and apps.

-[ ] Review release notes for breaking changes before updating.

-[ ] Monthly: Storage & Data Scrubbing

-[ ] Run ZFS/Btrfs scrub to detect and correct silent data corruption.

-[ ] Monitor S.M.A.R.T. status for all drives; replace any showing signs of failure.

-[ ] Quarterly: Physical Hardware Inspection

-[ ] Power down and use compressed air to remove dust from intakes, fans, and heatsinks.

-[ ] Inspect cable seating and power connections for wear.

-[ ] Verify all server/rack fans are spinning at nominal RPMs.

-[ ] Bi-Annually: UPS & Power Testing

-[ ] Disconnect UPS from wall power to simulate a utility failure.

-[ ] Verify server/gateway stays online during the transition.

-[ ] Inspect battery health metrics in the UPS management software.

-[ ] As Needed: Thermal Paste & Hygiene

-[ ] Check CPU temperatures during high-load tasks (e.g., AI model training).

-[ ] Consider re-applying thermal paste if temperatures consistently drift above baseline.
