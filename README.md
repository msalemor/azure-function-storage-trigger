# Storage trigger - Azure Functions consumption plan

## Problem Statement

## Solution 1

Switch to premium plan where you can have AlwaysOn

## Solution 2 (More like a hack)

Keep the service on warm by executing a timer function every 9 minutes.

### Steps

On the same consumption plan, deploy:

- The Azure Function with the Blob Storage trigger
- Deploys a second function using a Timer trigger on a 9 minute interval




