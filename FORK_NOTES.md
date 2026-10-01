# Palisade longitudinal fork (sunnypilot)

Base: sunnypilot `staging-tici` (0.10.1, comma 3 / TICI), commit 1f7233c.

Hyundai Palisade 2020-22 is not in UNSUPPORTED_LONGITUDINAL_CAR, so alpha longitudinal is
available. On a stock build the toggle is hidden when the git branch is in RELEASE_BRANCHES
(system/version.py); this fork's branch `palisade-long-sp` is not, so it shows.

After install: enable alpha longitudinal in the vehicle/developer settings, reboot with the
car on. Optional: enable Hyundai custom longitudinal tuning (Dynamic or Predictive).
The Palisade has no car-specific tune in opendbc/sunnypilot/car/hyundai/longitudinal/config.py,
so it uses the generic gas-car DEFAULT tune.

No source changes.
