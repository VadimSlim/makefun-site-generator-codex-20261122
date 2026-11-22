# Site Generator — Performance Engineering Challenge

> A Node.js 22 solution focused on output-compatible optimization of a website-generation workload.

[![Node.js](https://img.shields.io/badge/Node.js-22-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Competition](https://img.shields.io/badge/make.fun-First%20Crown-6C63FF)](https://make.fun/bounty/site-generator-speed-01-run-20261122)

## Overview

This project is an independent optimization of the official make.fun Site Generator baseline. The engineering goal is to improve execution performance **without changing the expected output**.

The repository retains upstream materials and attribution under `vendor/makefun-site`.

## How it works

The provided driver reads an array of test cases from `cases.json`, calls `run(input)` from `solve.js` for each input, and writes results to `answers.json`.

**Requirements:** Node.js 22.

```bash
# Run with directories containing cases.json and receiving answers.json
MAKEFUN_INPUT_DIR=./input MAKEFUN_OUTPUT_DIR=./output node main.ts
```

Create the input and output directories and supply valid competition-format test cases before running. On Windows PowerShell, set the environment variables with `$env:MAKEFUN_INPUT_DIR` and `$env:MAKEFUN_OUTPUT_DIR`.

## Verification

During development, output compatibility was checked against the three official practice cases. This is **not a claim of complete correctness across hidden tests**.

## Skills demonstrated

- JavaScript and Node.js performance optimization
- Behavioral compatibility and regression checks
- Reproducible command-line workflows
- Working within competition constraints

## Competition

[make.fun — Site Generator Speed](https://make.fun/bounty/site-generator-speed-01-run-20261122)

Final ranking and reward, if any, are determined by the organizer.

## Attribution

Original vendor license and NOTICE are preserved in `vendor/makefun-site`.

---

<sub>Explore more projects at [VadimSlim](https://github.com/VadimSlim).</sub>
