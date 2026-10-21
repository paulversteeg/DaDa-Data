# DaDa Data

DaDa Data is the 2027 indoor percussion program for Jubal Indoor Percussion, written for the ensemble members. It is a production that tells the story of how to break free from, learn about and live with artificial intelligence. Audiences come to see the show, and at performances a jury team adjudicates it.

## How this repo works

This repo holds the context of the project, so people and AI tools work from the same source of truth.
Figma, ClickUp and Storybook stay the place where the work happens. This repo explains it.

- `CLAUDE.md` and `AGENTS.md`: the front door for AI tools
- `context/project/`: why the project exists, who is involved, where things live
- `context/platform/`: everything that holds for the whole product
- `context/features/`: one folder per feature, all with the same structure
- `context/research/`: research that is broader than a single feature

## Starting a new feature

```bash
./scripts/new-feature.sh my-feature
```

This copies `context/features/_template/` into a new folder.
