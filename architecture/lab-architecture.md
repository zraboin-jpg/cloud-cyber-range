# Lab Architecture

The cyber range is deployed entirely within Microsoft Azure using a
segmented Virtual Network (VNET) and strict Network Security Group (NSG)
controls.

## Key Design Principles
- No vulnerable system exposed to the public internet
- Offensive VM restricted to limited inbound access
- East-west traffic monitored
- Centralized logging and telemetry

## Safety Controls
- Dedicated Azure subscription
- No credential reuse
- Snapshot-based resets
- Resource teardown after exercises
