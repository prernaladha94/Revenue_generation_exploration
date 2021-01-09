# Revenue_generation_exploration

PROBLEM STATEMENT
The dataset provided to you has data for several websites owned by the same company and they are asking for your help for what should be their approach to set reserve prices and what is the range for reserve prices they should be setting for July. The data is only of the actual revenue generation and not at bid level. The dataset has the following columns:

Date
site_id : each id denotes a different website
ad_type_id : each id denotes a different ad_type. These can be display ads , video ads, text ads etc
geo_id : each id denotes a different country. our maximum traffic is from english speaking countries
device_category_id : each id denoted a different device_category like desktop , mobile, tablet
advertiser_id: each id denotes a different bidder in the auction
order_id : can be ignored
line_item_type_id : can be ignored
os_id : each id denotes a different operating system for mobile device category only (android , ios etc) . for all other device categories, os_id will correspond to not_mobile
integration_type_id : it describes how the demand partner is setup within a publisher's ecosystem - can be adserver (running through the publisher adserver) or hardcoded
monetization_channel_id : it describes the mode through which demand partner integrates with a particular publisher - it can be header bidding (running via prebid.js), dynamic allocation, exchange bidding, direct etc
ad_unit_id - each id denotes a different ad unit (one page can have more than one ad units)
total_impressions - total number of eligible impressions
total_revenue - measurement column measuring the revenue for the particular set of dimensions
viewable_impressions - Number of impressions on the site that were viewable out of all measurable impressions. A display ad is counted as viewable if at least 50% of its area was displayed on screen for at least one second
measurable_impressions - Impressions that were measurable by Active View out of the total number of eligible impressions. This value should generally be close to 100%. For example, an impression that is rendering in a cross-domain iframe may not be measurable.
Revenue_share_percent - not every advertiser gives all the revenue to the publisher. They charge a certain share for the services they provide. This captures the fraction of revenue that will actually reach the publishers pocket.
QUESTIONS –

The person compiling the data recorded some inconsistencies within the numbers. Can you identify and categorize these inconsistencies and errors? (ex: revenue_share_percent cannot be more than 1 [100%])
For each site, which advertiser has the highest CPM, and can you track this CPM over time?
What is the potential revenue range our publisher can make in July?
