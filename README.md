# KPI Framework, Business Experiment Analysis & Decision Recommendation

## Business Context

This project evaluates the effectiveness of a new onboarding campaign for a subscription-based digital product. The objective is to determine whether the Treatment group performs better than the Control group.

## Dataset Description

The dataset includes user-level experiment data containing:

* Experiment Group
* Region
* Device Type
* Traffic Source
* Plan Type
* Landing Page Visit
* Trial Start
* Onboarding Completion
* Paid Conversion
* Revenue
* Refund Requests
* Support Tickets
* Engagement Score
* Days to Convert

## North Star Metric

Paid Conversion Rate

## KPI Tree Summary

The KPI Tree identifies Paid Conversion Rate as the primary business metric. Supporting KPIs include Landing Page Visit Rate, Trial Start Rate, and Onboarding Completion Rate. Guardrail metrics include Refund Rate, Support Ticket Rate, and Average Days to Convert.

## Experiment Analysis Approach

The analysis compared the Control and Treatment groups using business KPIs, revenue metrics, engagement metrics, and guardrail metrics.

## Hypothesis Test Summary

The experiment tested whether the Treatment group achieved a higher Paid Conversion Rate than the Control group.

## Guardrail Metrics Considered

* Refund Rate
* Support Ticket Rate
* Average Days to Convert

## Final Recommendation

The recommendation is based on the Paid Conversion Rate together with guardrail metrics to ensure both business growth and customer experience.

## Assumptions

* Dataset is accurate.
* Experiment groups are correctly assigned.
* User behavior is representative.

## Limitations

* Historical experiment data only.
* External factors not included.
* Additional testing may improve confidence.

## Screenshots Included

* summary_metrics.png
* hypothesis_test_output.png
* kpi_tree_preview.png
