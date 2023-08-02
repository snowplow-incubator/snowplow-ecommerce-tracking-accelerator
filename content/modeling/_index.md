+++
title = "Modeling"
date = 2022-08-16T17:24:05+01:00
weight = 4
chapter = true
pre = "3. "
+++

<!-- ### Chapter 2 -->

# Modeling your Data

{{<mermaid>}}
flowchart LR
    id1(Track)-->id2(Model)-->id3(Visualize)-->id4(Next steps)
    style id1 fill:#f5f5f5,stroke:#333,stroke-width:1px
    style id2 fill:#f5f5f5,stroke:#6638B8,stroke-width:3px
    style id3 fill:#f5f5f5,stroke:#333,stroke-width:1px
    style id4 fill:#f5f5f5,stroke:#333,stroke-width:1px
{{</mermaid >}}

The [snowplow-ecommerce dbt package](https://hub.getdbt.com/snowplow/snowplow_ecommerce/latest/) transforms and aggregates the raw e-commerce event data collected from the [Snowplow JavaScript tracker](https://github.com/snowplow/snowplow-javascript-tracker) into a set of derived tables including *carts*, *transactions*, and *products*. Modeling the data makes it easier to digest and derive business value from the Snowplow data either through AI or BI.

In this chapter you will learn how to set-up an run the snowplow-ecommerce package to model the sample data.
