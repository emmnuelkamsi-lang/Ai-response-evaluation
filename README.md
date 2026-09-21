# Ai-response-evaluation
Self-directed demo of AI response evaluation: a scoring rubric, side-by-side ratings with reasoning, and edited responses.

# AI Response Evaluation

A self-directed demo of AI response evaluation. My paid evaluation work on Oneforma and Handshake is under NDA, so nothing from those platforms appears here. These are original examples that follow the same workflow: compare two AI responses against a rubric I define, score them with reasoning, then edit the weaker response into a corrected version.

## Rubric

Every response is scored from 1 to 5 on four criteria:

- **Accuracy:** is every claim correct?
- **Completeness:** does it fully answer what was asked?
- **Clarity:** is it easy to follow, with no unnecessary padding?
- **Tone:** natural and appropriate for the question?

## Example 1: factual

**Prompt:** "What causes the seasons on Earth?"

**Response A**

> The seasons happen because the Earth moves around the sun in a big circle every year, and depending on where the Earth is in that circle, different parts of the planet get more or less sunlight, and also the Earth is spinning while it orbits, and this spin combined with the orbit and the distance from the sun creates the seasons we experience throughout the year in different places.

**Response B**

> Seasons are caused by Earth's axial tilt (about 23.5°), not its distance from the sun. As Earth orbits the sun, the tilt means different hemispheres receive more direct sunlight at different times of year, producing summer where sunlight hits more directly, and winter where it hits at a shallower angle.

| | Accuracy | Completeness | Clarity | Tone |
|---|---|---|---|---|
| Response A | 2/5 | 2/5 | 1/5 | 3/5 |
| Response B | 5/5 | 5/5 | 5/5 | 5/5 |

**Reasoning:** Response A never names the actual cause (axial tilt) and implies distance from the sun plays a role, which is a common misconception. It is also a single 70-word run-on sentence. Response B is correct, direct, and complete in three sentences.

**Edited version of Response A**

> Seasons are caused by Earth's 23.5° axial tilt, not by changes in distance from the sun. As Earth orbits, the tilt causes each hemisphere to receive more direct sunlight for part of the year (summer) and less direct sunlight the rest of the year (winter).

## Example 2: creative

**Prompt:** "Write a two-sentence product description for a reusable water bottle."

**Response A**

> This water bottle is great for staying hydrated. It is durable, reusable, and good for the environment.

**Response B**

> Double-walled steel keeps drinks cold for 24 hours or hot for 12, so your coffee is still hot at your 2pm meeting. One bottle, refilled daily, replaces roughly 1,000 single-use plastic bottles a year.

| | Accuracy | Completeness | Clarity | Tone |
|---|---|---|---|---|
| Response A | 3/5 | 2/5 | 3/5 | 2/5 |
| Response B | 4/5 | 5/5 | 5/5 | 5/5 |

**Reasoning:** Response A is generic boilerplate that could describe any product, with no specific detail a buyer could act on. Response B gives concrete, checkable specs (temperature retention, time frames) and a vivid comparison, which is what a product description needs to do.

**Edited version of Response A**

> Insulated stainless steel keeps water cold all day, even left in a hot car or gym bag. Refill it instead of buying bottled water, and it pays for itself within a couple of months.

## What this demonstrates

- Defining criteria before scoring, instead of judging on feel
- Giving reasoning that would hold up if a second rater checked my work
- Turning a critique into a concrete edit, not just a score

This is the same loop used in production rating and annotation work.
