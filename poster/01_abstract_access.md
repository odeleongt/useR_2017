---
title: "Estimating health service accessibility in Guatemala"
author:
   de León O^1^
   $^1$ Centro de Estudios en Salud, Universidad del Valle de Guatemala
institute: 
   - $^1$ Universidad del Valle de Guatemala
output: pdf_document
bibliography: service-access.bib
---

**Keywords**: Health, accessibility, distance, equity, GIS

**Webpages**: https://github.com/odeleongt/useR_2017/tree/master/01_gt_health_service_access

Guatemala (Central America) is a developing country with wide disparity issues
regarding income and basic needs coverage [@worldbank-gt].
Primary health service facilities are available in Guatemala over the whole
country at a reasonable geographic distribution [@equip2], 
in principle allowing for equitative access to health care for all the population.
Physical accessibility to health services has been evaluated previously for some areas
of the country [@annis-access-center; @owen-access-av],
but several shortcomings preclude the availability and usefulness of this information.

Physical accessibility to services is usually evaluated based on distance from
the communities to the health services, either over a shortest path or through
a known network of possible routes [@delamater-suboptimally].
These analyses typically require a considerable amount of analysis effort,
and the use of traditional analysis tools (i.e. point-and-click style analysis software)
has limited previous efforts to a few regions of the country [@annis-access-center; @owen-access-av].
Previous analyses have not taken into account altitude changes in the routing,
which heavily influences transportation costs.
Given the economic disparity in the country, altitude change should be considered
to provide a better assessment of physical accessibility to health services.

This work relies on the use of R [@R] to provide an extensible analysis template
which allows to
update physical accessibility estimates,
include new areas for which information is now available,
and efficiently use currently available altitude data [@aster].
Usability is improved by taking advantage of recent developments in spatial data use [@sf]
and visualization [@leaflet] in R to improve ease of analysis and provide more
relevant result dissemination.


# References
