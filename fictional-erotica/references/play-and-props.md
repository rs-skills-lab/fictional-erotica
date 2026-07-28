# Play And Props / 玩法与道具

Load this reference only when sexual play, experimentation, kink structure, props, or toys materially matters. Do not activate novelty merely because a scene is sexual.

只有性玩法、探索、kink 结构、道具或玩具会实质影响场景时，才加载此参考。不要仅因场景具有性内容就自动启用新奇变化。

## Conditional Controls / 条件控制

```yaml
play_controls:
  experimentation: inferred  # fallback: familiar
  prop_use: inferred          # fallback: none
```

Experimentation:

探索度：

- `familiar`: use established shared patterns / 使用已经建立的共同模式；
- `playful`: allow light variation / 允许轻度变化；
- `exploratory`: permit one plausible new element with learning and adjustment / 允许一个合理的新元素，并保留学习与调整；
- `kink-forward`: play structure becomes central / 玩法结构成为核心；
- `maximalist`: allow dense type-driven combinations while preserving coherence / 允许密集的类型化组合，但保持连贯。

Prop use:

道具使用度：

- `none`: no dedicated toy or prop / 不使用专门玩具或道具；
- `incidental`: one simple object may appear without structuring the scene / 可偶尔出现一件简单物件，但不支配结构；
- `integrated`: one or two established or plausible objects materially affect the scene / 一至两件既有或合理物件实质影响场景；
- `prop-forward`: objects organize pacing, topology, or attention / 物件组织节奏、拓扑或注意力；
- `maximalist`: multiple objects under one coherent design / 多件物件服从一个连贯设计。

Specific restrictions override broad presets. `prop_use: none` remains none under maximal experimentation.

具体限制优先于宽泛预设。最高探索度下，`prop_use: none` 仍然是不使用道具。

## Relationship-Specific Repertoire / 关系特定曲目

Treat play as a relationship-specific repertoire, not a checklist:

将玩法视为特定关系共同形成的曲目，而不是行为清单：

```yaml
play_profile:
  repertoire_breadth:
  novelty_appetite:
  technical_experience:
  intensity_preference:
  improvisation:
  ritualization:

play_item:
  fantasy_interest:
  willingness_in_reality:
  prior_experience:
  technical_confidence:
  partner_specific_consent:
  desired_meaning:
  undesired_meaning:
```

Fantasy, willingness, experience, competence, and consent are not interchangeable. Persona traits may suggest hypotheses, not deterministic kinks. Profession, intelligence, wealth, trauma, confidence, gender, anatomy, or sexual role does not automatically imply a practice.

幻想兴趣、现实意愿、既往经验、熟练度与同意不能互换。人物特征只能提出假设，不能机械决定癖好。职业、智力、财富、创伤、自信、性别、身体结构或性角色都不自动意味着某种玩法。

Possible families include sensory or verbal play, power exchange, restraint, impact, teasing and denial, roleplay and costume, observation or exhibition themes, service and protocol, toys, and multi-partner attention structures. Do not load a conventional package merely because one family appears.

可能的玩法家族包括感官或语言、权力交换、限制、冲击、挑逗与延迟、角色与服装、观看或展示主题、服务与仪式、玩具，以及多人注意力结构。不要因为出现一个家族，就自动加载整套常见脚本。

## Scene Budget / 场景预算

Normally use:

通常使用：

```yaml
scene_play_budget:
  anchor_play: 0_to_1
  supporting_elements: 0_to_2
  novelty_items: 0_to_1
```

A familiar scene may use none. Do not display the entire repertoire at once.

熟悉场景可以没有核心玩法。不要一次性展示全部曲目。

## Props And Failure / 道具与失败

Infer props from established preferences, relationship history, setting, access, and requested experimentation. An object should change sensation, pacing, topology, attention, power, or emotional meaning, not merely display variety.

根据既有偏好、关系历史、场景地点、实际可获得性与指定探索度推断道具。物件应改变感官、节奏、拓扑、注意力、权力或情感意义，而不是只用来展示种类。

Track familiarity, availability, location, operation, and current placement. Under grounded realism, props may fail, make noise, require adjustment, charging, cleaning, storage, or different lubrication. Under stylized realism, ordinary logistics may remain off-page, but established constraints and object continuity still apply.

追踪熟悉度、可获得性、地点、操作与当前位置。现实向模式中，道具可能失效、产生噪音，需要调整、充电、清洁、收纳或不同润滑。类型化模式中，普通后勤可以留在页面外，但既定限制与物件连续性仍然有效。

Do not turn practical failure into emotional crisis by default. A casual redirection may be enough.

不要默认把现实失败升级为情感危机。普通改道已经足够。
