# 3. Project Design Phase

## ServiceNow Components

| Component | Purpose |
|---|---|
| UI Policy | Controls conditional field behavior |
| UI Policy Action | Makes Assignment Group mandatory / Urgency read-only |
| onChange Client Script | Sets Urgency automatically |
| onSubmit Client Script | Validates Assigned To before save |
| onCellEdit Client Script | Blocks State changes from list editing |

## Main Condition
`Impact = 1 - High`
