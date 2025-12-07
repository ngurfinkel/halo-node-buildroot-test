# halo-node-buildroot-test

Test repository for auto-merge workflow validation - Level 3 (top tier).

This repository demonstrates automatic PR creation and auto-merge functionality in a multi-tier setup.

## Purpose

- Contains `halo-node-test` as a submodule in `opt/halo-node-test`
- When the submodule is updated via auto-PR, auto-merge is enabled automatically
- PR merges when all checks pass
- This is the top level - no parent to trigger

## Part of Test Chain

halo-auto-merge-test → halo-node-test → **halo-node-buildroot-test**

