# Changelog Vocabulary with the namespace http://data.europa.eu/s1n/

This changelog provides an overview of the changes incorporated in the `s1n` namespace vocabulary supporting StatDCAT-AP 3.0.0.

Since StatDCAT-AP 1.0.1, the following changes were done:
1. namespace document created
2. for existing properties: dimension, attribute, numSeries and statUnitMeasure, range was defined as `dcat:Dataset`, as based on the discussions in the WG it was determined, that these properties are not applicable to Distributions, Data Services or Dataset Series. [#7](https://github.com/SEMICeu/StatDCAT-AP/issues/7), [#8](https://github.com/SEMICeu/StatDCAT-AP/issues/8), [#9](https://github.com/SEMICeu/StatDCAT-AP/issues/9), [#11](https://github.com/SEMICeu/StatDCAT-AP/issues/11)
3. added property: measure [#19](https://github.com/SEMICeu/StatDCAT-AP/issues/19)
4. added property: data structure definition [#21](https://github.com/SEMICeu/StatDCAT-AP/issues/21)
5. added class: Dataflow [#24](https://github.com/SEMICeu/StatDCAT-AP/issues/24)