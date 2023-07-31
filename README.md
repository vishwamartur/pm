# Waku Project Management

Tracks/coordinate effort/tasks that targets Waku as a product across implementations (production readiness, scalability, etc).

## Teams

The Waku Team is currently split in the following subteams:

- Waku Research
- Waku Development (nwaku, js-waku, go-waku)
- Waku Eco Dev (DevRel, Docs)

## Work Tracking and Reporting Guidelines

### Requirements

The current reporting requirements are 2 folds:

#### 1. Weekly Reporting

Weekly reporting by subteam of progress on milestones. See https://notes.status.im/waku-2023-report as the initiating document

#### 2. Monthly Reporting

Monthly reporting is currently done in a private Google Sheet and has the following sections:
- Progress on yearly milestones (10 milestones as defined in https://notes.status.im/Uz9HeCwZTDSYyOq36Q54cA#, now marked as _Epics_).
- Key achievements/highlights of previous month
- Planned achievement for next month
- RAID: Risks, Assumptions, Issues and Dependencies
- Identified Market Opportunities

The Google Sheet will soon be replaced by a dashboard that extract data using GitHub with the ability to organise the data by epic using GitHub labels.

### Terminology

| Name           | Number of                           | Timeframe                            | Team Scope       | Description                                                                 |
|----------------|-------------------------------------|--------------------------------------|------------------|-----------------------------------------------------------------------------|
| Priority Track | 3-5                                 | Set yearly                           | Whole Team       | Focus set for the year, must be aligned with Logos Collective's priorities. |
| Epic           | 2-3 per _Priority Track_, total<=10 | Set yearly, delivered quarterly-ish  | Several subteams | Identified deliverables for each _Priority Track_.                          |
| Milestone      | Some per Epic                       | Set quarterly-ish, delivered monthly | One subteam      | Steps to deliver an _Epic_.                                                 |
| Task           | Many per Milestone                  | Set monthly-ish, delivered weekly    | One individual   | Smallest chunk of work to be delivered.                                     |  

### GitHub Usage

For each:

- _Epic_, there is a GH issue under the https://github.com/waku-org/pm repo.
- _Epic_, there is a label with format `E:<year>-<epic title>` created across all relevant https://github.com/waku-org/ repos.
- _Milestone_, there is a GH issue under the relevant https://github.com/waku-org/ repo with related _Epic_ label and `milestone` label assigned.
- _Task_, there is a GH issue and/or pull request under the relevant https://github.com/waku-org/ repo with related _Epic_ label.

Hence, correct _Epic_ label must be assigned to all GH issues/pull requests representing a _Milestone_ or _Task_.
This will enable the usage of the new reporting dashboard and reduce manual maintenance.

Ideally, every:

- _Epic_ GH issue contains a list of planned _Milestones_.
- _Milestone_ GH issue contains list of planned and completed _Tasks_.

## Work Tracking per Year

### 2023

**Priority Tracks**: https://notes.status.im/Uz9HeCwZTDSYyOq36Q54cA#a

**Epics** (WIP):

- https://github.com/waku-org/pm/issues/25 `E:2023-light-protocols`

