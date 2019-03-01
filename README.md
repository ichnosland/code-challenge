# Save the boat

It's a sunny sunday and Denis is on a boat trip on his bow rider.
Unfortunately the engine stops and he is sending an SOS signal.

He's far away from the coast and the signal is degraded and gets
corrupted, e.g. MOSSOS is received instead of the SOSSOS sent.

Implement a `sendHalp` function that takes a string and returns the
number of letters corrupted.
Please add some tests to check it's working fine.

## Constraints

- message is at least 3 chars long and up to 99 chars long
- message length is a multiple of 3
- string will contains only uppercase letters

## Example

```
sendHalp('SOM')
1

sendHalp('SOS')
0
```
