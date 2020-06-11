# mtail-snap

This is a snap for mtail, a tool for extracting metrics from application logs to be exported into a timeseries database or timeseries calculator for alerting and dashboarding.
More information: https://github.com/google/mtail

To build the snap, run `snapcraft` in this directory on Ubuntu 18.04 or later, and install with `sudo snap install mtail*.snap`

## Snap usage
`service snap.mtail.mtail` # copies the config file from the source if needed, and runs mtail

## Daemon arguments:
`$SNAP_DATA/daemon_arguments
