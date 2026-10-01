# Power Automate Workflow

The consolidated request workflow is designed around the request Status.

- Start processing when Status becomes Submitted.
- Resolve the requester's manager.
- If manager lookup fails, route to a predefined fallback approver and log/notify the exception.
- Capture approval outcome/comments.
- Continue approved requests to laboratory/supervisor review.
- Stop/reclassify rejected requests.
- Assign technician and send notifications.
- Update lifecycle status through completion.
- Use trigger conditions, limited trigger columns, and status guards to prevent duplicate processing.
