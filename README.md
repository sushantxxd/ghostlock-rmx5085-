# ghostlock-rmx5085-
GhostLock &amp; KernelSU research for the Realme GT 7T (RMX5085) running stock Realme UI. Includes device specifications, kernel and firmware details, screenshots, and compatibility findings.
GhostLock / DF Root + KernelSU Guide — realme GT 7T (RMX5085)

Device: realme GT 7T
ROM: Stock Realme UI
Tested firmware: "RMX5085_16.0.7.202 (EX01)"
Kernel: "6.6.89-android15-8-g97a9aaefab9a-ab14519050-4k"

Requirements

Before starting, download:

1. DF Root — obtain it from the original, trusted project source.
2. KernelSU Manager — use the latest compatible release from the official "KernelSU repository" (https://github.com/tiann/KernelSU).
3. Required firmware — "RMX5085_16.0.7.202 (EX01)", from a trusted source that matches your exact device model and region.
4. Back up your data and make sure you understand the device recovery procedure.

Steps

1. Prepare the firmware

Verify your current firmware version and confirm that the required package is specifically intended for the RMX5085.

If you need to downgrade, verify the official rollback procedure first. Downgrading can wipe data or fail because of rollback protection, so do not flash an unverified package.

2. Install KernelSU Manager

Install the compatible KernelSU Manager APK and open it to confirm that the app launches correctly.

Installing the manager app alone does not install or activate KernelSU.

3. Install DF Root

Obtain DF Root from its original source and follow the instructions for the exact firmware and kernel combination.

Do not use an exploit or payload intended for a different build.

4. Complete the root setup

Follow the project's documented procedure, then verify the resulting root status. Grant root access only to apps you trust and actually need to run with elevated privileges.

5. Troubleshoot payment-app crashes

If a payment app such as PhonePe crashes after the setup, first check the app's error message and logs. Removing the KernelSU Manager APK may help identify an app-specific conflict, but it does not remove root or guarantee that the payment app will work.

Do not assume that deleting the manager app disables root or resolves security checks. Use payment apps only in configurations permitted by their security requirements.

Verification

After setup, record:

- Firmware and kernel versions
- KernelSU Manager version and status
- Whether root access works as expected
- Any boot, stability, or app compatibility issues

Disclaimer

This procedure is specific to the reported device and firmware. Results may differ across builds. Back up important data, use trusted files, and understand the recovery procedure before modifying the device.

Please report your exact firmware and test results when sharing compatibility findings.
