+++
title = "E-commerce Web Accelerator"
menuTitle="Introduction"
chapter = false
weight = 1
post = ""

aliases = [
    "/en/",
    "/en/introduction/"
]
+++

### E-commerce Web and Mobile Accelerator
#### Introduction

This accelerator helps you analyze customer behavior, identify potential growth opportunities, and improve your e-commerce website and app (native iOS and Android) sales performance.


Here you will learn to:

- Set-up the required e-commerce tracking on your website or mobile app
- Model and Visualize Snowplow data
  - using the [snowplow-ecommerce](https://hub.getdbt.com/snowplow/snowplow_ecommerce/latest/) dbt package and Streamlit
- Apply these to your own pipeline to gain insights

---

#### Who is this guide for?

- Data practitioners who would like to get familiar with Snowplow data.
- Data practitioners who want to learn how to use the snowplow-ecommerce dbt package and set-up tracking on their e-commerce store, so they can learn more about visitor and customer behavioral data as quickly as possible.

---

#### What you will learn

In approximately 1.5 working days (~10 working hours) you can achieve the following:

- **Track -** Set up e-commerce actions tracking on your store
- **Model -** Configure and run the snowplow-ecommerce data model
- **Visualize -** Visualize the modeled data with Streamlit
- **Next steps -** Gain value from your own pipeline data through modeling and visualization

{{<mermaid>}}
gantt
dateFormat HH-mm
axisFormat %M
section 1. Track
6h :track, 00-00, 6m
section 2. Model
1h :model, after track, 1m
section 3. Visualize
1h :visualize, after model, 1m
section 4. Next steps
2h :next steps, after visualize, 2m

{{</mermaid >}}

---

#### Prerequisites

{{% notice tip %}}
Complete our [Advanced Analytics for Web](https://docs.snowplow.io/accelerators/web/) or [Advanced Analytics for Mobile](https://snowplow.io/data-product-accelerators/advanced-analytics-mobile/) accelerators or if you haven't yet started collecting data from your website or mobile app.
{{% /notice %}}

**Tracking and Enrichment**

- Snowplow pipeline
- Online store to add the tracking code

**Modeling and Visualization**

- dbt CLI installed / dbt Cloud account available
  - New dbt project created and configured
- Python 3 Installed
- BigQuery, Snowflake, or Databricks account and a user with access to create schemas and tables


{{% notice tip %}}
The tracking and dbt package are supported on Redshift as well as the above warehouses, but the Visualization in this accelerator is not set up to connect to a Redshift warehouse.
{{% /notice %}}

#### What you will build

An example E-commerce Dashboard with Streamlit

{{< tabs groupId="dashboard_images" >}}

{{% tab name="Streamlit" %}}

!['Streamlit Dashboard Example'](images/streamlit_dashboard.png?height=40pc)

{{% /tab %}}

{{< /tabs >}}
