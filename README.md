# Ethernet Traffic Analyzer

Simple tool to analyze, shape, and generate ethernet traffic. <br/>
Features include:
* Monitor traffic type distribution
* Throttle selected tcp connections
* Improve throughput with smarter drop policies
* Customize network for latency vs. throughput
* Raise alerts during suspicious port connections
* Visualize bandwidth usage

## Setup

Who knows yet.

## Related resources:

http://www.flukenetworks.com/enterprise-network/network-monitoring/Tap-Solutions

## Architecture

### Ethernet input goes to several stages of parsing.

1. Analytic parsing: In-depth packet analysis.
2. Filter parsing: Parsing just enough to filter appropriate packets so as to avoid latency.

###Analytics:

1. Source
2. Determine traffic categories
3. Bandwidth usage
4. Latency

### Filter:

1. Elastic vs inelastic traffic.
2. Blocking certain sources.
3. Throttling certain sources.
4. Expediting certain sources.

### Audio:

### Video:

1. VGA controller

### Output:

1. Traffic rules that apply to all traffic.
2. Buffering rules.
3. Smarter drop policies.
4. Widen MTU.
