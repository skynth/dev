# PetCode Contribution Guide

How does it all work?

## Stage 1: Feature -> Request for Comments & Initial Proposal

Instead of randomly thinking about issues to solve, we formalize the entire decision-making process into Request For Comment documents—these can be submitted throughout the entire week, and encourages discussion. These **must** follow a specific format to be accepted as an issue. When Request for Comments are created, they initially flow into the `Proposal` category of the Board.

## Stage 2: Review

Board updates are streamed to Slack (if possible), and discussion can take place wherever updates are available. These discussions must follow the guidelines set out in the RFC documents themselves, and have to be verified by everyone (or the majority) to move forward in the development stages.

## Stage 3: Design

As soon as the feature has completed the initial review stage, it moves into the design phase—each phase is explicitly provided, and obviously can be moved between in specific instances (if the RFC is a bug, for instance, we may move it straight to the Ready for Development category). After design work is completed (remember, the whole point of this is to be asynchronous—while design is being done, developers can continue to work on their own tasks in the Development categories), the issue moves on to the `Ready for Development` category, where a given developer will be assigned to the RFC.

## Stage 4: Development

Obviously, the RfD category is where the most stagnation will occur, so we have to specifically keep track of who's doing what, and make sure to bump up issues in Slack (with tagging) if need be.

As soon as someone's tasks are freed up, they can assign more dev tasks to themselves or someone else, fulfilling the asynchronous promise system that works super well for our team. At this stage, a given issue is moved into the InDev column.

Again, progress upates are always kept in a given thread. Development is done in discrete branches (hotfixes MAY be done on `main`, but we have to refrain from doing so unless it's absolutely necessary), eventually culminating in PRs.
## Stage 5: Review

When development is finished, the cycle of iteration begins (like the Indev stage, finished issues go into the Ready for Review section as PRs are submitted, and move into the Reviewing stages when someone is available). I'll be in charge of reviewing PRs (there will be a separate PR template for design-based PRs) on the basis of code & conformance to principles. However, any other senior-level person can also chime in—that's the beauty of this sytem: it's democratic, and doesn't depend on one person's work at all times.

If a decision is made in this stage that iteration is the best option, the issue gets put back into the InDev column, and on approval gets moved into the "done" category, merged, and we can celebrate!

## Meetings?

This new system focuses and puts a focus on the individual team dynamics that we have together—we love working concurrently and independently of others. This new system allows everyone to work on *something* at every single point in time; no more waiting for updates on any other work. It leverages the power that every one of us has, together.
