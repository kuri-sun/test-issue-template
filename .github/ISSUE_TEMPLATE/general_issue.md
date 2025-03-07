<!--
This issue template can be used for any kind of UI updates which involves UI/UX design work through Figma by designers.

It is highly encouraged to have a conversation related to this design work on this issue for tracking purpose.
If there is a discussion about this issue on Slack or in a meeting, it is also encouraged to summarize and share it to this issue.
-->

# Summary

What are you going to design?

## Figma Link

(Provide the corresponding Figma link for our quick reference here.)

---

<details><summary>The Procedure of Design Issue Management</summary>

1. Designers create a "Design" issue for their design work
   - Label: `kind: design`
   - Area: `Design` in the [Nobita GitHub Project](https://github.com/orgs/HENNGE/projects/14/views/69)
   - Designers manage its status (`Inbox` → `Todo` → `In Progress`)
1. Designers list this issue as a child issue on the corresponding epic issue in the [HENNGE/nobita2-discovery repo](https://github.com/HENNGE/nobita2-discovery/issues?q=sort:updated-desc+is:issue+is:open+label:%22kind:+epic%22). E.g.: <img width="838" alt="image" src="https://github.com/user-attachments/assets/e334695c-52e8-4cab-a06a-5eee0e93f8e9">

1. If the feature is big enough, designers create a mockup for discussion and we hold a prior spec grooming session to be on the same page
1. Once a hi-fi design work is done and becomes ready for FE review, designers change the Design issue status to `Under Review / Blocked`
   - Designers can also use this status if there is a blocker for their design work (e.g. It requires more spec clarifications)
1. Developers review the design work and if it is good, they give an explicit LGTM comment on this Design issue
   - Designers move the issue status to `Approved` once they confirmed it is actually reviewed by themselves
   - Designers can move the status back to `In Progress` if there is a follow-up design work based on the feedback from on-going development
   - Once an updated design has been confirmed on either GitHub Issue, Slack or Figma (More casual LGTM than the initial FE design review), designers move the issue status to `Approved`
1. Once all designers and developers are satisfied with the finalized design, and no more preliminary effort is planned on the designer's side, they can close this Design issue. (The issue's status automatically becomes `Done`)

</details>