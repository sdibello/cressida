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
| FR-001 | Allow a login through the existing Identity service in the d:/git/Janus application. | User can log in, and be authorized to use Cressida. |
| FR-002 | Cressida will allow 3 auth roles, admin, contributor, user. | Admin's can set a role to any user, that role will dictate when they can do. |
| FR-003 | Cressida will allow users in the Contributor, Admin, and User role to maintain a list of characters they have created. | Log in, and see a list of characters they have created.  Edit name, create, delete. |
| FR-004 | Characters will each have 1-20 spell books.  Each spell book will have a list of spells for the character to RP with. | Cressida will allow a unique character name, and a set of unique spellbooks names under it.  Each spell book will store a number of first through ninth levels spells. |
| FR-005 |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
| UI-001 |  |  |

- Data the product stores or processes: TBD
- External systems and API needs: TBD

## Quality and constraints

- Accessibility, performance, security, privacy, and operational needs: TBD
- Known legal, platform, or delivery constraints: TBD

## Open questions

- TBD
