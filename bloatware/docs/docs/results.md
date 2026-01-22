# Bloatware Analysis Results

## Sample Detected Apps

| App Name               | Type                  | Safe to Disable? | Notes                         |
|------------------------|---------------------|----------------|-------------------------------|
| Facebook               | Third-party          | Yes            | Pre-installed social app      |
| Google Play Movies     | Optional system app  | Yes            | Rarely used, safe to disable  |
| Android System UI      | System-critical      | No             | Do not disable                |
| Carrier Messaging App  | Optional system app  | Yes            | Can disable if unused         |

## Observations
- Many devices include **5–15 pre-installed apps** that users rarely use.
- Disabling optional apps can **free up RAM and reduce background battery usage**.

## Future Steps
- Add scripts for **automatic detection and logging** per device.
- Combine with battery experiment to create a **full Android optimization toolkit**.
