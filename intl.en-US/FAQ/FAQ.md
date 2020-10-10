# FAQ

Common questions

-   [Do I need to configure a data transfer plan after I purchase it?](#section_ykp_2cy_b2b)
-   [Do data transfer plans change the peak bandwidth of the cloud resources that use the data transfer plans?](#section_zmb_vcy_b2b)

Data transfer plan questions

-   [Are data transfer plans used to offset the costs of data transfer based on the purchase dates in ascending order?](#section_kz7_cbg_gj0)
-   [Can I use a data transfer plan to offset the costs of data transfer incurred by cloud resources that are deployed in a region other than the regions listed on the buy page?](#section_ogk_6pn_qqw)
-   [Can I use data transfer plans to offset the costs of data transfer incurred by cloud resources that are charged on a pay-by-bandwidth basis?](#section_sfe_1ar_usx)

## Do I need to configure a data transfer plan after I purchase it?

No.

The system will automatically use the purchased data transfer plan to offset the costs of IPv4 data transfer incurred by certain resources that are charged on a pay-by-data-transfer basis. These resources include Elastic Compute Service \(ECS\) instances, elastic IP addresses, Server Load Balancer \(SLB\) instances, and EIP bandwidth plans.

## Do data transfer plans change the peak bandwidth of the cloud resources that use the data transfer plans?

No. Data transfer plans are resource packages. They do not change the peak bandwidth of the cloud resources that use the data transfer plans.

## Are data transfer plans used to offset the costs of data transfer based on the purchase dates in ascending order?

No.

Data transfer plans are used to offset the costs of data transfer based on the expiration dates. The data transfer plan with the earliest expiration date is first used. For example, you have purchased two data transfer plans. One data transfer plan will expire on June 1 and the other one will expire on February 1. The system will first use the second data transfer plan to offset data transfer costs because the expiration date of the second data transfer plan is earlier than that of the first one.

**Note:** If the expiration dates of the two data transfer plans are the same, the one with the earlier purchase date is first used to offset the data transfer costs.

## Can I use a data transfer plan to offset the costs of data transfer incurred by cloud resources that are deployed in a region other than the regions listed on the buy page?

No.

You cannot use a data transfer plan to offset the costs of data transfer incurred by cloud resources that are deployed in a region other than the regions listed on the buy page.

## Can I use data transfer plans to offset the costs of data transfer incurred by cloud resources that are charged on a pay-by-bandwidth basis?

No.

Data transfer plans can be used to offset only the costs of data transfer incurred by certain cloud resources that are charged on a pay-by-data-transfer basis. These cloud resources include ECS instances, elastic IP addresses, SLB instances, and EIP bandwidth plans.

