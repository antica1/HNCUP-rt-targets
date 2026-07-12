# HNCUP — RT Target Delineation Skill

Postoperative & definitive radiotherapy target volume delineation for **head and neck cancer of unknown primary** (HNCUP).

## What This Skill Does

Given a cervical lymph node with metastatic SCC and no visible primary, this skill guides you through a standardized 6-step decision chain:

1. **True CUP definition** — exhaustive workup must have failed
2. **NPC exclusion** (Step 1) — mandatory in Chinese/endemic populations
3. **Reverse-engineer the primary** from nodal location + viral status
4. **Selective mucosal irradiation** — not pan-mucosal, not full oral cavity
5. **Ipsilateral neck only** — unless contralateral cN+
6. **Retrograde flow rule** — post-dissection lymphatic disruption

## Quick Install

### Hermes Agent
```bash
hermes skills install https://raw.githubusercontent.com/antica1/head-neck-cup-rt-targets/master/SKILL.md
```

### Claude Code
Copy `SKILL.md` into your Claude skills directory.

## Trigger Keywords

`unknown primary` `HNCUP` `occult primary` `neck node SCC no primary`

## Key References

- Dou S et al. *Oncotarget* 2016 (PMID: 27223430)
- Dou S et al. *Cancer Med* 2020 (PMID: 31953927)
- Ghatasheh et al. *Radiother Oncol* 2022 (PMID: 35905781)
- Oebel et al. *Clin Transl Radiat Oncol* 2024 (PMID: 38192301)
- DAHANCA. *Radiother Oncol* 2025 (PMID: 41016667)

## Author

Dou Shengjin, Zhu Guopei — Department of Radiation Oncology, Shanghai Ninth People's Hospital, Shanghai Jiao Tong University School of Medicine.  
Contact: antica@gmail.com

## License

MIT

## Related Skills — Shanghai Ninth People's Hospital Head & Neck RT Series

| Skill | Description |
|-------|-------------|
| [NPC Target Delineation](https://github.com/antica1/npc-rt-target-delineation) | Lancet 2025 + IG-2024, skull base millimeter-level |
| [**HNCUP Target Delineation**](https://github.com/antica1/HNCUP-rt-targets) | Occult primary, selective mucosal RT |
| [ACC Post-op RT](https://github.com/antica1/head-neck-acc-rt-targets) | Sensory nerve pathway, facial nerve management |
| [Orbital Tumor RT](https://github.com/antica1/orbital-tumor-rt-targets) | Compartment irradiation, VIII/IX/IIa cascade |
| [DVH Plan Review](https://github.com/antica1/head-neck-dvh-review) | One-glance pass/fail, dual-track physicist/physician reports |
| [Re-Irradiation Planning](https://github.com/antica1/head-neck-reirradiation) | Quad-Shot + SBRT + IO/ADC, cumulative BED |
| [All Skills](https://github.com/antica1) | Six skills from Shanghai Ninth People's Hospital |
