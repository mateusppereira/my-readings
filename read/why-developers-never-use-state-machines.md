#[Why Developers Never Use State Machines](https://adrianco.medium.com/platform-engineering-teams-done-right-b3b3d4a8ad23)

The article expalins the value of state-machines and reason about the lack of usage in real scenarios.

The hypothesis presented by the author that would justify the non usage is:
- The complexity comming from the theory of state machines that we try to prevent (YAGNI).
- When we notice that we need it, in general, we consider it's to late. Not useless.

The author points that there are a bunch of libs that helps us. So the problem is not the tool.

He brings a real scenario and share come insights:
- The learning curve wasn't a problem
- Start migrating as soon as possible. "had we done this when our objects only had a couple of states it would have been a breeze"
- Benefits the user, because they could easily create another states
- Consistency on state transactions
- Audit on state transitions


> We seem to shy away from state machines due to misunderstanding of their complexity and/or an inability to quantify the benefits
