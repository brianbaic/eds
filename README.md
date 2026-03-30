# Spreadsheet Demo Playbook

This project is a single-page spreadsheet demo focused on drag-to-upload behavior, rich visual preview, and clean public-safe demo data.

## Demo flow

1. Drag one virtual report from the file manager into the upload card.
2. Review generated charts, field profile, and table explorer.
3. Switch between `Canvas` and `Individual Performance` using the `Demo` selector.
4. Export chart image or visible CSV when needed.
5. Reset canvas to restore all virtual reports and load another file.

## Current demo assets

- dashboard.html: main one-page demo application.
- demo-data/individual-performance.json: individual performance sample dataset.
- demo-data/individual-performance.csv: CSV form of the same sample dataset.

### Virtual file manager reports

**Operations**
- regional_traffic_model.xlsx — 3 sheets | 54 rows | mixed types
- capacity_scenarios.xlsx — 2 sheets | 42 rows | scenario data

**Learning**
- learning_progression.xlsx — 2 sheets | 36 rows | completion timeline
- quality_observations.xlsx — 1 sheet | 30 rows | categorical + numeric

**People**
- individual_performance_demo.xlsx — 1 sheet | 12 rows | rich person-level signals

**Finance**
- monthly_budget_variance.xlsx — 1 sheet | 36 rows | dept budget vs actual
- spend_vs_plan_by_region.xlsx — 1 sheet | 32 rows | regional spend tracking
- operating_margin_trend.xlsx — 1 sheet | 24 rows | quarterly margin trend

**Customer Experience**
- sentiment_and_feedback_mix.xlsx — 1 sheet | 40 rows | channel sentiment scores
- case_resolution_journey.xlsx — 1 sheet | 35 rows | case lifecycle data
- channel_response_time_benchmark.xlsx — 1 sheet | 28 rows | response vs benchmark

## Local preview

1. Open dashboard.html directly in a browser, or
2. Serve the folder statically and open dashboard.html.

## Pre-commit safety checks

1. Keep private notes and source artifacts in _private/.
2. Avoid committing real secrets, credentials, or tokens.
3. Stage specific files intentionally.
4. Re-scan demo content for sensitive strings before push.
