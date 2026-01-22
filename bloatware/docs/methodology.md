# Bloatware Analysis Methodology

## Objective
Detect and analyze pre-installed apps ("bloatware") on Android devices to help users improve performance and battery life.

## Steps

1. **List Installed Apps**
   - Gather all installed apps on the device.
   - Conceptual command (for reference only, no need to run):
     ```
     adb shell pm list packages
     ```

2. **Categorize Apps**
   - **System-critical apps:** Required for device functionality, do NOT disable.
   - **Optional system apps:** Can be disabled safely without affecting core functions.
   - **Third-party pre-installed apps:** Usually bloatware, often safe to disable.

3. **Analyze Resource Usage**
   - Identify which apps consume battery, RAM, or storage in the background.
   - Use logs to track potential impact on performance.

4. **Provide Recommendations**
   - Suggest disabling optional apps to improve performance.
   - Warn users against disabling system-critical apps.

## Notes
- This experiment is **for research and learning purposes**.
- Future versions may include **scripts to automate detection** and logging.
