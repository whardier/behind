# behind
Multi-distribution script to query available packages and report the distance between installed and release versions.

## Supported Distributions

None yet

## Immediate Distribution Development

- APT based distributions
- RPM based distributions
- Pacman based distributions

## Adding packages to check

APT itself is very useful for this, as it offers a direct method of getting at branch information for a majority of the packages installed on most systems.  A large file/directory based database will be used and seeded initially via APT to help create a resolver and upstream configuration pool for live comparison.
