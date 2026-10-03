## Axis Auto Sign v1.5.11

Little Hub has been updated for the new Axis Hub History layout.

### What's new

- Supports the new mixed History table without the old Unsigned dropdown
- Starts from page 1 and uses individual Sign buttons across History pages
- Does not use Hub's new "Sign all" button, preserving per-transaction gas protection
- Skips rows without a reliable attempt ID
- Legacy Unsigned layout is still supported

### Progress

- Epoch points
- Trajectories
- Unique task count
- Average score
- Epoch start/end dates and remaining time
- Account-scoped history cache
- Fast current-epoch Scan
- Full Scan when a complete history refresh is needed

### Signing & protection

- Automatic task signing
- Duplicate-sign protection
- Failed-sign retry
- $0.01 gas protection
- Live Signed / Unsigned / Pending / Failed counters
- Adjustable delay: 1.7s / 2s / 2.5s / Custom
- Background Hub tab targeting

### Updating from an older version

Do not remove the existing extension if you want to preserve your local ledgers and counters.

1. Stop signing and wait for the current transaction to finish.
2. Extract the new ZIP.
3. Replace the files inside your existing extension folder.
4. Open `chrome://extensions` or `brave://extensions`.
5. Click Reload on Little Hub.
6. Reload the Axis Hub tab once.

### Notes

This is an unofficial community tool for Axis Robotics Hub.

Never share your seed phrase, private key, or wallet credentials with anyone.




