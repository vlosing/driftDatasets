This is the original description by Gamma et al. :

UP, DOWN

date:	ignore.
day:	1,2,3,4,5,6,7.
period:	continuous.
nswprice:	ignore.
nswdemand:	continuous.
vicprice:	continuous.
vicdemand:	continuous.
transfer:	continuous.
 

 
We used the normalized version as it can be found on moa http://moa.cms.waikato.ac.nz/datasets/
However, we always remove the "date" and "nswprice" as suggested by Gamma et al. from the data before learning. Hence, the used features are the following:
day:	1,2,3,4,5,6,7.
period:	continuous.
nswdemand:	continuous.
vicprice:	continuous.
vicdemand:	continuous.
transfer:	continuous.