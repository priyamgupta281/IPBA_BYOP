# IPBA_BYOP

The file contains historical sales data (identified with the column titled File_Type) along with current active inventory that is in need of evaluation (i.e., File Type = "Active"). The historical data shows sales for the past 6 months. The binary target (1 = sale, 0 = no sale in past six months) is likely the primary target that should drive the analysis.

The other columns contain numeric and categorical attributes that we deem relevant to sales.

Note that some of the historical sales SKUs are ALSO included in the active inventory.

A few comments about the attributes included, as we realize we may have some attributes that are unnecessary or may need to be explained.

SKU_number: This is the unique identifier for each product.

Order: Just a sequential counter. Can be ignored.

SoldFlag: 1 = sold in past 6 mos. 0 = Not sold

MarketingType = Two categories of how we market the product. This should probably be ignored, or better yet, each type should be considered independently.

NewReleaseFlag = Any product that has had a future release (i.e., Release Number > 1)
