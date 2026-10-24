# Project specification

Status: Draft

This file is the source of truth for **what the product should do**. Replace the prompts below as requirements become known. Keep technical implementation decisions in `docs/decisions/`.

## Problem and goals

- Problem to solve: A tool that allows a user to track their character's spellbooks, have quick access to the text of the spell, and create new spells 

## Users and key workflows

- Intended users: Users of the existing stack in the git/Janus.Identity tool.
- This will be a new tool in that stack
- 

## Scope

* allow users to create a number of characters
* characters will have a spellbook.
* this app will allow users to search for spells in a database, and save searches under that character.

## Functional requirements
| ID | Requirement | Acceptance criteria |
| --- | --- | --- |
* **FR-001** - Allow a login through the existing Identity service in the d:/git/Janus application. User can log in, and be authorized to use Cressida, and assigned a role.
* **FR-002**- Cressida will allow 3 auth roles, Admin, Contributor, User.  Admins can set a role to any user, that role will dictate when they can do. 
* **FR-003** -  Cressida will allow users in the Contributor, Admin, and User role to maintain a list of characters they have created.  They should be able to create, update, and edit the characters.
* **FR-004** - Each individual Character will each have 1-25 spell books.  Each spell book will have a list of spells for the character to roleplay with. Cressida will allow a unique character name, and a set of unique spellbooks names under it.  Each spell book will store a number of first through tenth levels spells. It will track the total number of spells written in the book, and the number of spell levels.  Meaning a first level spell is 1 spell level, and a 5th level spell would be 5 spell levels.
* **FR-005** - Characters can have a single prepared spell list.  Each prepared spell list will have a certain number of spell slots based on their character, which the user can define.  The total number of spell slots at each of the levels of 1 through 10 will be sum of the following:  Base Sepll Slots, Bonus Spell Slots, Specialty Spell Slots, Prestige Spell Slots
**FR-006** -
  **FR-007** -

* **S-001** - The data for spell information is currently stored in /docs/dnd.sqlite in a selection of tables.
* **S-002** - The tool should allow the users to search for spells to fill their spellbook.  The search should be similar to https://new.dndtools.org/spells
* **S-008** - 
* **S-009** - 
* **S-010** - 

* **UI-001** - when showing a spell card, the UI should be similar to this page: https://new.dndtools.org/feats/mobility-1975



- Data the product stores or processes: TBD
- External systems and API needs: TBD

## Quality and constraints

- Accessibility, performance, security, privacy, and operational needs: TBD
- Known legal, platform, or delivery constraints: TBD

## Open questions

- TBD
