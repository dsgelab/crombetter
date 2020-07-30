# crombetter
Helper script for checking Cromwell jobs

## Requirements
- bash
- curl
- jq

## Usage
### Check status of latest jobs
`./crombetter status`

### Check 5 latest failed jobs
`./crombetter failed 5`

### Check details of last submitted job
`./crombetter details`

### Check all information on a job
`./crombetter meta <JOB-ID>`
