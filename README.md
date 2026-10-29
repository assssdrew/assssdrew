# Evgenii Potapov

**Revit Automation & BIM Manager (MEP) | Revit API, Dynamo, Navisworks**

I design and automate **Revit coordination across discipline models**: compact save, naming, year upgrades, links, units, health checks, levels/grids, typical-floor schedules, exchange alerts.

**Vietnam** · [LinkedIn](https://www.linkedin.com/in/evgenii-potapov-v) · [Selected automation](https://github.com/assssdrew/bim-revit-automation)

**Open to:** full-time remote roles (US/EU) and freelance Revit automation projects · fully remote · UTC+7

The work is process design in Python, PowerShell and the Revit API — operator UIs, staged pipelines, reports, watchers. Unattended batch runs are one delivery path, not the whole skill set.

**Stack:** Revit API (IronPython, [Revit Batch Processor](https://github.com/bvn-architecture/RevitBatchProcessor)), Dynamo (CPython3), PowerShell, WinForms, OpenXML Excel reports. Revit Batch Processor is a third-party GPL-3.0 tool ([bvn-architecture/RevitBatchProcessor](https://github.com/bvn-architecture/RevitBatchProcessor); see NOTICE in the [portfolio repo](https://github.com/assssdrew/bim-revit-automation)).

## Featured

Tested on real working models. Compact save has run on long lists (~125 models); model operations cover ~50+ models.

| Project | Outcome |
|---------|---------|
| [Compact save](https://github.com/assssdrew/bim-revit-automation/tree/main/cases/05-compact-save) | Fast or deep Compact of workshared centrals, with a size report |
| [Model ops](https://github.com/assssdrew/bim-revit-automation/tree/main/cases/06-model-ops) | Rename, Revit-year upgrade and RVT relink across discipline models (~50+), staged so links are not broken |
| [Health check](https://github.com/assssdrew/bim-revit-automation/tree/main/cases/02-health-check) | Read-only model health audit → Excel report, no Save/Sync |
| [Project units](https://github.com/assssdrew/bim-revit-automation/tree/main/cases/01-project-units) | Batch Length accuracy on local / UNC / Revit Server models |
| [Levels & grids](https://github.com/assssdrew/bim-revit-automation/tree/main/cases/03-levels-grids) | BF↔AR and discipline↔BF levels/grids audit and controlled apply on base files |
| [FTP model alerts](https://github.com/assssdrew/bim-revit-automation/tree/main/cases/04-ftp-model-alerts) | Push alerts when shared exchange folders change, without manual watch |
| [Typical floors](https://github.com/assssdrew/bim-revit-automation/tree/main/cases/07-typical-floors) | Apartment schedule export: Revit → Dynamo → Excel (166 apartments, floors 2–17, 10 groups) |

Safety-first writes: audit ≠ apply; Detach is not used on live production centrals.

[Русский обзор кейсов](https://github.com/assssdrew/bim-revit-automation/blob/main/README.ru.md)
