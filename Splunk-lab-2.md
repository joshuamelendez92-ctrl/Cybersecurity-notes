 # Splunk Lab 2
## Objective
Identify the most common sourcetypes in the internal Splunk index.

## Query Used
index=_internal | top limit=10 sourcetype

## What I Learned
- How to find the most frequent log types
- How to use the `top` command in SPL
- How to understand data distribution in logs

## Tools
- Splunk
- SPL (Search Processing Language)
