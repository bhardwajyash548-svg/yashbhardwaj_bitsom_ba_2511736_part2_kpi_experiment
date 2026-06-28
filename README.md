# yashbhardwaj_bitsom_ba_2511736_part2_kpi_experiment

# yashbhardwaj_bitsom_ba_2511736_part2_kpi_experiment

KPI Experiment Analysis

Business Context

A subscription-based digital product company launched a new onboarding and activation campaign to improve user conversion and early engagement.

Users were divided into: - Control Group: Existing onboarding experience - Treatment Group: New onboarding experience

The objective of this experiment was to determine whether the new onboarding experience should be launched to all users.

Dataset Description

The dataset contains experiment data including user demographics, onboarding actions, conversion outcomes, revenue, refunds, support tickets, and engagement scores.

North Star Metric

Paid Conversion Rate

This metric directly drives subscription revenue growth.

KPI Tree Summary

Primary Drivers

Landing Page Visit Rate
Trial Start Rate
Onboarding Completion Rate
Guardrail Metrics

Refund Rate
Support Ticket Rate
Average Days to Convert
Engagement Score
Data Quality Checks

Missing values checked
Group count validation completed
Duplicate user ID check completed
Binary value validation completed
Revenue outlier review completed
Segment distribution review completed
Results: - Control Users: 693 - Treatment Users: 715 - Duplicate User IDs Found: 8 - Binary columns contained only valid values (0 and 1) - Revenue outliers were retained because they may represent high-value customers - Segment distribution was reasonably balanced across groups

Hypothesis Test Summary

H0: Treatment conversion ≤ Control conversion
H1: Treatment conversion > Control conversion
Test Type: One-tailed Two-Proportion Z-Test
Alpha: 0.05
Final Recommendation

Launch the new onboarding experience to all users while monitoring guardrail metrics.

Screenshots Included

summary_metrics.png
hypothesis_test_output.png
kpi_tree_preview.png
