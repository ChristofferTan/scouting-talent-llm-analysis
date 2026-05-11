# NHL Scouting Trait Dataset

This dataset contains structured trait annotations extracted from amateur NHL scouting reports using a Large Language Model (LLM)-based processing pipeline.

The pipeline automatically:
1. Extracts talent-related phrases from scouting reports  
2. Classifies each phrase as a:
   - `strength`
   - `weakness`
   - `neutral`
3. Categorizes each phrase into one of four trait dimensions:
   - `physical`
   - `technical`
   - `tactical`
   - `psychological`

---

## File

`scouting_traits_processed.xlsx`

---

## Sheets

| Sheet | Description |
|---|---|
| Sheet 1 | Strength-related phrases |
| Sheet 2 | Weakness-related phrases |

Each row represents a single extracted phrase.

---

## Variables

| Variable | Description |
|---|---|
| `Player Name` | Anonymized player identifier |
| `Draft Year` | NHL draft year |
| `Position` | Player position (`F` = Forward, `D` = Defenseman) |
| `Phrase` | Extracted scouting phrase |
| `Label` | Phrase sentiment |
| `Trait` | Trait category |

---

## Trait Categories

| Trait | Description |
|---|---|
| Physical | Athleticism, skating, size, strength |
| Technical | Shooting, puck skills, passing |
| Tactical | Positioning, awareness, decision-making |
| Psychological | Work ethic, competitiveness, leadership |

---

## Notes

- Player names have been anonymized for privacy.
- All phrases were normalized to lowercase text.
- Trait annotations were generated using an LLM pipeline and may contain minor classification errors.

---

## Intended Use

This dataset is intended for academic and research purposes, including:

- Sports analytics
- Talent identification research
- Natural language processing
- Text mining and qualitative analysis

---

## Citation

If you use this dataset, please cite the associated paper:

Tan, C., et al. *Reconstructing the Perception of Sports Talent Through the View of Scouts: A Textual Analysis with Large Language Models.*
