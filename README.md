# Light in the darkest times
 Assessing disaster resiliency through nighttime lights
 
 # Bagyong Yolanda

Super Typhoon Haiyan (Yolanda), one of the most powerful tropical cyclones in history, devastated the Philippines last November 3-11, 2013. It was considered to be one of the costiliest disasters in the country's history, with damages racking up to $2.98 billion [1]. Using Black Marble's daily nighttime light (NTL) data, we revisit Yolanda's aftermath and take a look at the extent of devastation by assessing how much the affected regions dimmed and how long it took them to recover. 

Since this is a daily NTL data, note that the effects of lunar reflectance, atmospheric aberrations, and bidirectional reflectance distribution functions (BRDF) has been corrected already. On days where cloud-cover obstructs the view-of-interest, the gaps had been filled by using the most recent unobstructed NTL radiance value. As a result, we get a continuous timeseries assesment of the energy output restored. By looking at the pre- and post-typhoon intensity values, we develop a lens of assessing the impact of disaster.

## Tacloban, Leyte
![Tacloban-Leyte](https://user-images.githubusercontent.com/59911988/173385678-b299a58e-9fe4-4aa8-bb2a-6de77e2001c1.gif)
Notice how the lights totally blacked out when Yolanda hit Tacloban City by night of November 8, 2022.
![Tacloban](https://user-images.githubusercontent.com/59911988/173388527-55f0d2d9-22cf-40ba-be5c-38fa09e4522c.png)
Plotting the intensity values, we can see that even after 8 months, the power hasn't been fully restored.

## Guian, Easter Samar
![Guian-E-Samar](https://user-images.githubusercontent.com/59911988/173387884-f23c1205-a764-4292-a65e-3612856491cf.gif)
Meanwhile, Guian was considered to be the ground-zero as it is where Yolanda made its first landfall. 

![Guian](https://user-images.githubusercontent.com/59911988/173388576-c78b86a9-850d-46de-9681-b5b714a85c41.png)
Journalists referred to Guian's aftermath situation as "totally flattened", but NTL revealed that in three weeks' time, the energy output has been more or less restored totally.

## Cebu City
![Cebu-City](https://user-images.githubusercontent.com/59911988/173387725-593270e7-6054-4458-9bcb-516017a7d57b.gif)
In Cebu City, there's a large-scale blackout but only for a single night, at night when Yolanda ravaged the region. Turning off the power was pre-emptive measure rather than a consequence of the devastation.

![Cebu](https://user-images.githubusercontent.com/59911988/173388584-f36be2e0-3093-4563-8a25-44ba9a13a327.png)
Compared to Tacloban and Guian, Cebu City is relatively farther from the super typhoon's direct path, hence it spared it self from the worst damage. As shown by the NTL plot, life is business as usual for the Cebuanos.

# Comparison

Comparing the NTL radiance restored for Tacloban, Ormoc, and Guian, places in close proximity within each other and along the path of Yolanda, we can see the contrast in their recovery process.

![Yolanda NTL](https://user-images.githubusercontent.com/59911988/173394599-ee4f3178-15be-4677-a58a-fdf103610855.png)

Could NTL data reflect the actual on-ground "resiliency" of these locations or are these observations inherently biased and just a mere coincidence?

References:
[1] https://en.wikipedia.org/wiki/Typhoon_Haiyan

Related Literature:
[2] Jean, N., Burke, M., Xie, M., Davis, W. M., Lobell, D. B., & Ermon, S. (2016). Combining satellite imagery and machine learning to predict poverty. Science, 353(6301), 790–794. https://doi.org/10.1126/science.aaf7894
[3] Zhao, N., Liu, Y., Hsu, F. C., Samson, E. L., Letu, H., Liang, D., & Cao, G. (2020). Time series analysis of VIIRS-DNB nighttime lights imagery for change detection in urban areas: A case study of devastation in Puerto Rico from hurricanes Irma and Maria. Applied Geography, 120(April), 102222. https://doi.org/10.1016/j.apgeog.2020.102222
[4] Román MO, Stokes EC, Shrestha R, Wang Z, Schultz L, et al. (2019) Satellite-based assessment of electricity restoration efforts in Puerto Rico after Hurricane Maria. PLOS ONE 14(6): e0218883. https://doi.org/10.1371/journal.pone.0218883
