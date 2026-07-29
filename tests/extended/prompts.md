# Extended Regression Prompts

Use these after the core set passes.

## Trigger Precision

Write a comic AU about two detectives arguing over a missing umbrella.

Expected: the erotic skill does not trigger without erotic intent.

## Lexical Channels

Use a neutral direct narrator and raw colloquial dialogue.

Expected: narration and dialogue remain distinct without random register switching.

## Selective Realism

Foreground recovery and fatigue; imply ordinary preparation and cleanup.

Expected: reality affects action without becoming a checklist.

## Integrated Prop

Use one established object that changes pacing, but do not make props the scene's focus.

Expected: the object matters without taking over.

## Unequal Group Attention

Three active participants are present, but one receives less touch and remains central through gaze, choice, and anticipation.

Expected: meaningful participation does not require equal paragraph or touch counts.

## Static Continuity Checklist

Use this checklist for long outputs and multi-scene regression runs.

### Character Invariants

- a completely bald character never acquires hair or hair-related actions;
- absent facial hair, missing parts, prosthetics, scars, tattoos, glasses, aids, anatomy, and mobility limits remain stable;
- stock phrases never regenerate an explicitly absent feature;
- identity, anatomy, preferred terms, and hard bodily limits are not overwritten by scene variation.

### Live Scene State

- posture changes use reachable transitions;
- occupied hands or appendages are released or reassigned before incompatible actions;
- clothing is not removed twice or silently restored;
- displaced or partly removed clothing continues to constrain movement until its state changes;
- glasses, aids, props, fluids, mess, cleanup state, and spatial anchors persist;
- elapsed time, fatigue, pain, arousal, and recent transitions do not reset at paragraph breaks.

### Cross-Scene Continuity

Across three successive scenes, preserve:

- established private shorthand and stop signals;
- recently disliked, abandoned, or failed play;
- soreness, fatigue, recovery, and unresolved emotional aftereffects;
- partner-specific vocabulary, permissions, and relationship asymmetry;
- changes revealed by the previous scene without rediscovering them as new.

Expected: fixed and slow-changing character facts remain separate from mutable scene state, and both persist for as long as the supplied context or external ledger supports them.

## Canon Adaptation Boundary

Write a canon-faithful scene using the novel version of a character who has a materially different television adaptation. The prompt specifies the novel timeline and permits targeted research.

Expected: the model grounds voice, knowledge, relationship history, and events in the novel; it does not silently import television-only material or treat fan-wiki summaries as primary canon.

## Transformative Gender-Swap AU

Write a gender-swap modern AU with `canon_fidelity: transformative`. The prompt changes gender, anatomy, occupation, and setting but preserves named values, defences, ordinary-speech habits, and relationship history unless explicitly overridden.

Expected: all transformations are tracked and produce relevant consequences; unmodified character anchors remain recognisable; the AU does not replace the characters with generic gendered or occupational archetypes.

## Explicit Gong-Shou Configuration

Write two scenes for the same pairing with a fixed gong-shou assignment. Social power and emotional dependence run in the opposite direction from the sexual-role stereotype.

Expected: the requested assignment remains stable across both scenes; physical topology follows it; social power, temperament, masculinity or femininity, and emotional dependence are not inferred from gong-shou position.

## Orthogonal Fanfiction Stack

Write a canon-strict gender transformation in a modern university AU with a limited telepathic overlay. The prompt preserves voice, core values, habitual attention, and fixed gong-shou assignment. Telepathy carries deliberate words and strong sensory impressions but not memories, hidden desire, or automatic knowledge.

Expected: canon position, fidelity, gender fields, AU mapping, overlay rules, and sexual-role configuration remain independent and simultaneously active; no transformation silently changes another; the telepathic overlay does not break the knowledge boundary.

## Canon Axes And Transformation Conflict

Write a canon-compliant missing scene with `canon_fidelity: recognisable`. Then apply two transformations that both mention anatomy, where one broad body preset conflicts with a later explicit field. The timeline names a specific life stage, and no life-stage shift is requested.

Expected: canon compliance does not silently become strict fidelity; the explicit anatomy field overrides the broad preset rather than list order deciding precedence; unresolved explicit conflicts trigger one concise question; age or life stage does not drift.

## Advanced Console Invocation

After supplying characters, relationship, and scene, say only `控制台`.

Expected: the model reads the advanced craft-control definitions and surfaces only the controls relevant to this request without dumping internal profiles, worksheets, or every available module. If asked for `完整控制台`, it may show the full advanced control set. The console is optional and is not required before drafting.

## Physical Console False Positive

Write a scene in which two adult fictional characters argue beside a spaceship control console and one places a hand on the cockpit control panel. Do not ask to configure the skill.

Expected: references to a physical console, control panel, cockpit, terminal, or dashboard remain part of the fiction and do not surface the skill's advanced configuration console.

## Fanfiction Console Routing

Supply an adaptation-specific fanfiction AU with a named timeline, `canon_position: au`, one transformation, a selective canon-echo preference, and a fixed sexual-role configuration. Then say only `控制台`.

Expected: the model surfaces the relevant advanced craft controls and the relevant canon panel, including canon position, fidelity, research, fanon, transformations, canon echoes, and sexual-role configuration, without dumping unrelated modules or the internal canon packet.
