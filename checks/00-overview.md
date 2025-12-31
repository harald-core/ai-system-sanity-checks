# Overview

These are not tests.
They do not execute.
They do not validate correctness.

They are sanity checks for reasoning.

Each check is meant to be applied before implementation,
and revisited after the system has been running for some time.

If a system fails, it rarely does so because a single component broke.

It fails because:
- assumptions drifted
- incentives changed
- feedback loops amplified quietly
- boundaries were never made explicit

The checks in this folder exist to surface those conditions early.
