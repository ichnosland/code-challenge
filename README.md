# Save the boat

It's a sunny sunday and Alessandra is on a boat trip on her bow rider.
Unfortunately the engine stops and she is sending an SOS signal.

She's far away from the coast and the signal is degraded and gets
corrupted, e.g. MOSSOS is received instead of the SOSSOS sent.

Implement a `sendHelp` function that takes a string and returns the
number of letters corrupted.
Please add some tests to check it's working fine.

## Constraints

- message is at least 3 chars long and up to 99 chars long
- message length is a multiple of 3
- string will contains only uppercase letters

## Example

```
sendHelp('MOS')
1

sendHelp('SOS')
0
```
