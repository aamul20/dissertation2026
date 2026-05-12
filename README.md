# dissertation2026

# Title: Landslide Susceptibility Mapping in the Bagmati Province, Nepal
#### An Integrated Geospatial and Machine Learning Framework Using Google Earth Engine

##### Abstract
The Bagmati Province of Nepal is a globally recognised geohazard hotspot, which experiences both extreme topographical fragility and intense monsoonal precipitation, triggering critical landslide events. Though the development of regional predictive models in developing nations like Nepal has been attempted, it is frequently constrained by computational bottlenecks, fragmented text-based disaster reporting, and structural biases inherent in spatial sampling. This study developed a fully automated, cloud-native Landslide Susceptibility Mapping (LSM) pipeline using Google Earth Engine and a Random Forest (RF) ensemble classifier. To address the issue of scarcity in the regional data, a novel spatial geocoding algorithm was engineered to convert administrative text records from Nepalese national databases and integrate them with an available global dataset into precise spatial coordinates, generating a robust 1,419-landslide-point inventory.
One of the primary objectives of this research was to investigate the structural data leakage caused by standard pseudo-absence sampling methodologies. The initial RF model, trained using established strict slope thresholds (<10° and >50°), achieved an artificially inflated Area Under the Curve (AUC) of 0.9772, with the slope variable dominating around 50% of the predictive logic. To test for this methodological bias, an original Ablation Study was executed, for which the slope variable was completely removed. The ablated model successfully exposed the true secondary geomorphological drivers, maintaining a highly robust AUC of 0.887 and proving that Elevation (38%) and Rainfall (23%) independently influence the landslide susceptibility of the region. In conclusion, this research provides a highly accurate, statically mapped spatial susceptibility projection for the Bagmati Province.



// It requires geemap, scikit-learn, geopandas, and an authenticated Google Earth Engine account to make use of the scripts.

