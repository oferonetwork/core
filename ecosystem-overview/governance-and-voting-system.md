---
description: >-
  This page explains how the Governance and Voting system works within the Ofero
  Network, covering proposals, comments, quorum, eligibility, and voting
  mechanics.
icon: gavel
---

# Governance and Voting System

### 1. Overview

The governance system in Ofero Network is designed to give power to verified users holding SFTs. They can create proposals, comment, and vote on changes in the ecosystem. This ensures decentralization and fair decision-making.

***

### 2. Proposals

#### What is a Proposal?

A proposal is a suggestion made by a quorum member to improve the Ofero Network or make a decision about its development.

#### Main Features:

* Created by verified users.
* Visible to the entire community.
* Includes title, description, optional OFE amount, and optional destination wallet.

#### Key Actions:

* **Create**: Users can submit new proposals.
* **Edit/Delete**: Only the creator (initiator) can modify or delete proposals if they are not archived.
* **View**: All users can read proposals and see their status.
* **Viewers**: The platform tracks who has viewed each proposal.

***

### 3. Comments

#### How It Works:

* Each user can comment once per proposal.
* Comments are votable (up/down) by others.
* Comment votes are stored separately from proposal votes.
* Editing a comment removes existing votes.

#### Permissions:

* Only the original author can update or delete their comment.
* No interactions allowed on archived proposals.

***

### 4. Voting System

#### Types of Votes:

* **Upvote** – Agree with the proposal.
* **Downvote** – Disagree with the proposal.
* **Abstain** – Neutral stance.
* **Retract Vote** – Remove your vote.

#### Voting Conditions:

* Only users in the **Governance Quorum** can vote.
* Voting is locked once a proposal is archived.

***

### 5. Quorum System

#### What is the Quorum?

The quorum is a group of verified users eligible to vote on proposals.

#### Eligibility:

To join, a user must:

* Be **at least 23 years old**.
* Own an **Ofero SFT**.
* Have a validated account.
* Have logged in to ofero.me during the past 30 days.

#### Actions:

* **Subscribe**: Join the quorum if you meet all criteria.
* **Unsubscribe**: Leave the quorum. Votes on open proposals are automatically removed.
* **Eligibility Check**: The system checks if a user can join the quorum.

***

### 6. Proposal Finalization

The system automatically finalizes proposals based on voting statistics:

* A proposal is **locked** if further votes can't change its result.
* A proposal is **passed** if it has a clear majority.
* Proposals reaching **80% voter participation** are evaluated and will be automatically marked as `completed`  at the end of the day.

***

### 7. Vote Statistics and Outcome Logic

The platform calculates:

* Number of upvotes, downvotes, and abstains.
* Voter participation percentage.
* Status: `Pending`, `Passing`, or `Failing`.
* If even if **all remaining eligible voters voted one way**, the result wouldn’t change → proposal is locked.

***

### 8. Additional Features

* **Thinking Users**: Users who saw a proposal but haven’t voted are shown.
