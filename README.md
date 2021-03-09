# coseismic_product
> HySDS localizer, sling extractors / wrappers, and evaluator wrapper for coseismic co-registered product

This repository contains code that will create a Program Executable (PGE) that allows a science data processing pipeline to download data products from Sentinel-1 spacecraft imaging repositories per a given acquisition list, and will generate a resulting TopsApp
configuration metadata product which will be used to create interferograms.

## Build Instructions

Built using the ARIA HySDS Jenkins Continuous Integration (CI) pipeline.

More information about this process can be found [here](https://hysds-core.atlassian.net/wiki/spaces/HYS/pages/455114757/Deploy+PGE+s+onto+Cluster)

## Run Instructions

You may run your customized PGE via two methods that are documented below:
- An [on-demand (one-time) job](https://hysds-core.atlassian.net/wiki/spaces/HYS/pages/378601499/Submit+an+On-Demand+Job+in+Facet+Search)
- [Create a trigger rule](https://hysds-core.atlassian.net/wiki/spaces/HYS/pages/442728660/Create+Edit+Delete+Trigger+Rules) to invoke your PGE based on conditions

## Release History

N/A

## Contributing

1. Create an GitHub issue ticket describing what changes you need (e.g. issue-1)
2. Fork this repo (<https://github.com/aria-jpl/coseismic_product/fork>)
3. Make your modifications in your own fork
4. Make a pull-request in this repo with the code in your fork and tag the repo owner / largest contributor as a reviewer

## Support

Contact `@riverma` for support.
