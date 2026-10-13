# Governance Timeline Version

This repository holds one file, version.json, which the backend of the Governance Timeline (https://abcdataworks.com/timeline/) rewrites whenever a history changes on its Google Sheet. The file maps each history's key to a fingerprint of its current content. The timeline page reads it through GitHub Pages and compares it with the fingerprints in its cached data file, so it shows a cached history only when that history is current.

The file holds fingerprints and timestamps only, never history text. Do not edit it by hand; the backend overwrites it.
