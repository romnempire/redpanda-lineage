# Red Panda Lineage

[![Build Status](https://travis-ci.org/wwoast/redpanda-lineage.svg?branch=master)](https://travis-ci.org/wwoast/redpanda-lineage)
[![Red Pandas](https://img.shields.io/badge/dynamic/json.svg?query=$._totals.pandas&label=red%20pandas&uri=https%3A%2F%2Fwwoast.github.io%2Fredpanda-lineage%2Fexport%2Fredpanda.json)](https://wwoast.github.io/redpanda-lineage/export/redpanda.json)
[![Zoos](https://img.shields.io/badge/dynamic/json.svg?query=$._totals.zoos&label=zoos&uri=https%3A%2F%2Fwwoast.github.io%2Fredpanda-lineage%2Fexport%2Fredpanda.json)](https://wwoast.github.io/redpanda-lineage/export/redpanda.json)

[![Kokin](https://raw.githubusercontent.com/wwoast/redpanda-lineage/master/docs/images/readme/header.jpg)](https://raw.githubusercontent.com/wwoast/redpanda-lineage/master/pandas/0011_kushiro/0023_kokin.txt)

[Download the dataset (JSON)](https://wwoast.github.io/redpanda-lineage/export/redpanda.json)

## Contribute To The Dataset!

If you love Red Pandas and want to contribute to a public family tree, look into our [Contribution Instructions](https://github.com/wwoast/redpanda-lineage/blob/master/docs/INSTRUCTIONS.md)!

## Summary

The global red panda population is estimated at under 10,000 animals, and between 500-1000 of these animals are distributed across zoos worldwide.

With the goal of producing a web interface for viewing pandas and their offspring, I hope to create a flat-file human-editable dataset of pandas. A small group of passionate red panda lovers will manually curate this dataset by making updates or commits to this repository.

When a commit is accepted, Travis CI will run the bundled Python scripts, and publish a single JSON file to the _GitHub pages_ branch of this repository. This file will be queryable using the [Dagoba](https://github.com/dxnn/dagoba) graph query language, allowing a fully browser-based red panda lineage viewer to be written. Peek at our [Design Documentation](https://github.com/wwoast/redpanda-lineage/blob/master/docs/DESIGN.md) for more details.

## Credits

This Red Panda lineage dataset was started by Justin Fairchild in June 2018, with the help of Daniele Bragaglio, and dedication of Red Panda fans in Japan and world-wide on Instagram and YouTube.
