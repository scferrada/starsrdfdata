This is an RDFization of the star data avaliable [here](http://burro.astr.cwru.edu/Academics/Astr221/HW/HW5/yaletrigplx.dat)

We use following prefixes for stars and their properties respectively:

```
@prefix star:<http://stars.dcc.uchile.cl/star/>
@prefix stp:<http://stars.dcc.uchile.cl/prop/>
```
Each star has three properties `stp:color`, its B-V color; `stp:absMagnitude` its computed absolute magnitude; and `stp:parallaxUncertainty`, its parallax uncertainty.

IRIs of this dataset can be changed in the future in order to reuse more well-known vocabularies.
