# Dataverse Data Model

| Table | Purpose |
|---|---|
| Laboratory Request | Main transactional request |
| Department | Department code, description, manager, active flag |
| Laboratory Location | Laboratory/location reference |
| Laboratory Request Type | Controlled request classification |

## Choices
- Status: Draft, Submitted, Pending Manager Approval, Manager Rejected, Pending Laboratory Review, Additional Information Required, Approved, Assigned, In Progress, Completed, Cancelled
- Priority: Low, Normal, High, Critical
- Approval Outcome: Not Started, Pending, Approved, Rejected, Information Required
- Confidentiality: Internal, Confidential, Highly Confidential
