# Code for the transmitter aboard the Leffell Space Program's HAB Mission!

## Callsign Setup

Before building or uploading, you must set your own APRS callsign:

1. Copy `LightAPRS-2-hab/callsign_secret.h.template` to `LightAPRS-2-hab/callsign_secret.h`.
2. Edit `callsign_secret.h` and replace `"N0CALL"` with your actual callsign (max 6 characters).
3. Do **not** commit `callsign_secret.h` to version control; it is ignored by `.gitignore`.

Example:
```cpp
char CallSign[7] = "N0CALL";
```
