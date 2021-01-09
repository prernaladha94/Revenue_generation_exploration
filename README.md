# Revenue_generation_exploration

PROBLEM STATEMENT
The dataset provided to you has data for several websites owned by the same company and they are asking for your help for what should be their approach to set reserve prices and what is the range for reserve prices they should be setting for July. The data is only of the actual revenue generation and not at bid level. The dataset has the following columns:

1. Date

2. site_id : each id denotes a different website

3. ad_type_id : each id denotes a different ad_type. These can be display ads , video ads, text ads etc

4. geo_id : each id denotes a different country. our maximum traffic is from english speaking countries

5. device_category_id : each id denoted a different device_category like desktop , mobile, tablet

6. advertiser_id: each id denotes a different bidder in the auction

7. order_id : can be ignored

8. line_item_type_id : can be ignored

9. os_id : each id denotes a different operating system for mobile device category only (android , ios etc) . for all other device categories, os_id will correspond to not_mobile

10. integration_type_id : it describes how the demand partner is setup within a publisher's ecosystem - can be adserver (running through the publisher adserver) or hardcoded

11. monetization_channel_id : it describes the mode through which demand partner integrates with a particular publisher - it can be header bidding (running via prebid.js), dynamic allocation, exchange bidding, direct etc

12. ad_unit_id - each id denotes a different ad unit (one page can have more than one ad units)

13. total_impressions - total number of eligible impressions

14. total_revenue - measurement column measuring the revenue for the particular set of dimensions

15. viewable_impressions - Number of impressions on the site that were viewable out of all measurable impressions. A display ad is counted as viewable if at least 50% of its area was displayed on screen for at least one second

16. measurable_impressions - Impressions that were measurable by Active View out of the total number of eligible impressions. This value should generally be close to 100%. For example, an impression that is rendering in a cross-domain iframe may not be measurable.

17. Revenue_share_percent - not every advertiser gives all the revenue to the publisher. They charge a certain share for the services they provide. This captures the fraction of revenue that will actually reach the publishers pocket.

QUESTIONS –

1. The person compiling the data recorded some inconsistencies within the numbers. Can you identify and categorize these inconsistencies and errors? (ex: revenue_share_percent cannot be more than 1 [100%])

2. For each site, which advertiser has the highest CPM, and can you track this CPM over time?

3. What is the potential revenue range our publisher can make in July?
