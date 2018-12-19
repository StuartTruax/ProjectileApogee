# ProjectileApogee
Analysis of the apogee achieved by a projectile in fluid media under inviscid fluid assumptions. 

The goal of this analysis is to calculate a realistic estimate of the maximum reach (i.e. apogee) of large-caliber small arms fire from the ground. Many analyses consider only the gravitational potential, which yields grossly unrealistic estimates on the order of 30 km or greater of apogee. However, it is known from practical experience in warfare that aircraft are typically safe from small-arms fire at altitudes of 3000 m or greater.

This notebook shows graphically the maximum displacement  $x_{max}$ (apogee) achieved by a projectile fired in the opposite direction of a graviational field $\textbf{g}$. Two scenarios are considered:

 1.  Gravitational acceleration $g$ and an inviscid drag force $F_{drag}$  acting against the projectile
 2.  An additional viscous force $F_{viscous}$  acting against the projectile. 
 
 
 # Conclusion

Under the assumptions of this analysis, the apogee of a Speer .50 caliber bullet with a muzzle velocity of 928 m/s fired straight up shouldn't exceed about __772 m__. This is in stark contrast to the __30 km__ or more estimated by considering the gravitational potential alone. 


Inviscid drag forces greatly reduce the apogee of the projectile in comparison to the "pure gravity" case. Further considering viscous forces in addition to inviscid drag and gravity, the apogee is only reduced by less than a 10,000th of a percent. Thus inviscid drag yields the dominant correction to the "pure gravity" case. 


## Further Notes

This is first pass/back-of-the-envelope analysis. I did not corroborate these results with any empirical study or outside references specific to the subject.
