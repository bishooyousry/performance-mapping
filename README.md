# Performance Mapping Lab (Activity 4): Efficiency × Effectiveness, in groups

One HTML file, English and Arabic (RTL), official Skills Bank palette and logo. Built from your scenario file and the matrix flipchart: same 10 scenarios (text verbatim), same four quadrants, same P/Q and risk list, same debrief notes.

## How a group works
1. Players type a name, enter the session code and pick a **group** (Group 1 to 6; 3-5 people per group, one group per breakout room).
2. All members of a group share **one live board** from their own devices (any member can move cards; one person can drive while the group talks). Groups never see each other's boards.
3. **Select a card** in the list (the scenario opens with its facts), then **place it** in a quadrant: tap "Place card N here", or drag the card onto the matrix.
4. For each placed card: **P / Q** (P = Productivity risk, Q = Quality risk), the **risks** it creates (quality defects, customer dissatisfaction, rework, missed deadlines, excessive labour / time, unnecessary workload, low-value output, or "No risk: sustain it"), and the **managerial action** to move it toward High / High (up to 140 characters).
5. Diagnoses stay hidden until the trainer presses **Reveal diagnoses**. Then each group sees its placements against the facilitator diagnosis with the debrief note per scenario (cards 2 and 8 are flagged for debate; card 8 accepts two quadrants), and writes the **leadership principles** that achieve and sustain High Effectiveness and High Efficiency.
Without a session code a single device works on its own and can check its own answers.

## Trainer dashboard
Code 2026 (hides the interface only). Per group: members, progress, live mini-matrix. A **consensus table** (how many groups placed each card in each quadrant, diagnosis marked, "groups differ" flag), the groups' principles, Reveal / Hide diagnoses, a projector view (group matrices side by side, where groups differ, scenario notes, principles), and CSV export (group, card, quadrant, match, P/Q, risks, action, principles).

## Quadrants (efficiency up, effectiveness right)
| | Low effectiveness | High effectiveness |
| --- | --- | --- |
| **High efficiency** | Efficient & Ineffective (cards 2, 3, 6, 8) | Efficient & Effective (cards 5, 10) |
| **Low efficiency** | Inefficient & Ineffective (card 9) | Inefficient & Effective (cards 1, 4, 7) |

## Please check
1. **P/Q and risk suggestions** shown after the reveal are my suggestions (rule: low efficiency suggests P, low effectiveness suggests Q); your scenario file has no key for them. They are labelled "added for this tool" and are not scored. Edit `sugg` in the code if you want different ones.
2. The **Arabic text** of the cards and the debrief notes is my translation: please have it reviewed.
3. Scoring is only "placed as diagnosed" (10 cards). Card 2 accepts only Efficient & Ineffective; card 8 accepts Efficient & Ineffective or Inefficient & Ineffective (per your note about the debate).
4. Tested with simulated devices and a test relay (two groups, several devices per group), not on real phones or the live ntfy.sh relay. The public relay is not confidential: fictional scenarios only.

## Publish (GitHub Pages)
Upload `index.html` and `.nojekyll` to the repo root; Settings > Pages > Deploy from branch. Open the published address, not a preview viewer.
