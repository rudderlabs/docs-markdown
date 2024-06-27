@@ -1,53 +0,0 @@
Modern data teams rely on their warehouse as a single source of truth for customer data. RudderStack's **Profiles** unifies every user touchpoint and trait into comprehensive customer profiles, establishing the data warehouse as the core of the customer data platform.

With Profiles, data teams can efficiently resolve identities and create user features to produce a comprehensive customer 360 table.


<br />

The following self-guided tour shows how to use Profiles:

<div style={{ position: 'relative', paddingBottom: 'calc(68.98305084745763% + 41px)', height: 0}}><iframe src="https://demo.arcade.software/OAaJFyRn1pkMru7HVJr3?embed" title="QuickStart Profiles" frameborder="0" loading="lazy" allowFullScreen style={{"position":"absolute","top":"0","left":"0","width":"100%","height":"100%","colorScheme":"light"}}></iframe></div>

## Highlights

See the following guides to learn more about Profiles features and their usage:

## Why use Profiles?

Data teams often face challenges when building a comprehensive customer view. Maintaining large, complex SQL models or working around the limitations of rigid SaaS platforms is time-consuming and expensive at scale.

Profiles simplifies this process of unifying customer data by automating the manual data engineering and modeling required to build an identity graph, layer new data sources into customer profiles, and compute user features that leverage data from diverse sources.

Using Profiles, data teams can quickly build and easily maintain a comprehensive customer 360 table and make it available to downstream teams and tools.

#### Move faster with an end-to-end platform

Profiles integrates directly with RudderStack's other pipelines:

- [Event Stream]("/sources/event-streams/") and [Cloud Extract]("/sources/extract/") (ETL) pipelines have known schemas and unique identifiers through the ingested customer data. Profiles can produce a baseline identity graph, and user features out of the box. Data teams can then augment the graph and features using any other data in their warehouse.
- [Reverse ETL]("/sources/reverse-etl/") pipeline makes it easy to send data from the customer 360 table directly to the downstream tools used by marketing, customer success, product, and other teams.

#### Enrich user profiles with features

You can [enhance user profiles]("/profiles/core-concepts/feature-development.md") with additional data points and features. When new data sources are added, discovered, or calculated, data teams can add them to their Profiles configuration without having to clean data and update complex models and dependencies.

The features/traits can include demographic information, preferences, purchase history, browsing behavior, or other static or computed data points.

#### Unlock deeper insights

Profiles extends its capabilities to support features derived from complex concepts such as funnels, organizational metrics, and machine learning models. You can understand your customer's journey through your sales funnel or locate each user across the histogram of customer metric values by simply defining a trait.

#### Deliver personalization and recommendations

Using Profiles, you can ship projects like personalization significantly faster by focusing entirely on activating key user features instead of cleaning and modeling data to build them.

#### Predict user conversions and churn

You can leverage [Predictions]('/profiles/predictions/_index.md) to build predictive features that help you predict in advance whether a lead is likely to convert, or a customer is likely to churn or make a purchase.

## Who can leverage Profiles?

Profiles is built for data engineers, data scientists, and technical marketers. You can define identity stitching, and user features as configuration files without requiring deep SQL, Python, or technical knowledge.

You can define the associated properties or attributes that provide detailed information for each new feature. For example, if the feature is `purchase_history`, its properties can include the date of purchase, product category, or order value.
No newline at end of file
