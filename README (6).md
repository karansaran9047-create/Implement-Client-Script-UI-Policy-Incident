# 6. Project Testing

## Test Cases

### 1. Mandatory Enforcement
- Open Incident → Create New.
- Set Impact to High.
- Leave Assigned To empty.
- Click Submit.
- Expected: record is not saved and an error is displayed.

### 2. Successful Save
- Fill Assigned To.
- Click Submit.
- Expected: Incident saves successfully.

### 3. Reverse Condition
- Change Impact from High to Medium.
- Expected: Assigned To is no longer mandatory and Urgency becomes editable.

### 4. List Edit Blocking
- Open Incident → All.
- Double-click State.
- Expected: alert appears and State remains unchanged.

### 5. Form-Based Update
- Open the Incident form.
- Change State.
- Click Update.
- Expected: State change saves successfully.
