# Expo Managed Workflow: Error Importing Unsupported Native Modules

This repository demonstrates a common error encountered when using Expo's managed workflow and attempting to import or use native modules that aren't compatible with Expo's environment. The issue is often characterized by unclear error messages, making debugging challenging.  The example shows how to reproduce the error and the correct solution using Expo's recommended approach.

## Reproducing the Error

The `bug.js` file demonstrates the problematic import. Attempting to run this file directly will result in an error.

## Solution

The `bugSolution.js` file illustrates the correct approach to using native modules with Expo. This involves using Expo-compatible alternatives or, if unavailable, leveraging the Expo SDK's capabilities or moving to a bare workflow.