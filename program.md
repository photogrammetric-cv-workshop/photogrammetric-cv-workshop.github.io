---
layout: page
---

# Schedule

(Tentative)

| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 13h - 13h15 | Welcome |
| 13h15 - 14h00 | <img src="/img/diamond.png"  width="20"> **Konrad Schindler**, *ETH Zurich* <br><em>High-Resolution, Country-Scale Snow Depth Estimation From Satellite Images</em><br><details>Monitoring snow depth is important for hydrology, hydro-power planning, ecology, and Alpine safety. Existing methods to estimate snow depth over large areas are typically limited to ground sampling distances of ca. 1km. This limits their usage in high alpine areas, where that resolution fails to capture local snow distribution patterns caused by the pronounced topography. I will present recent advances that make it possible to map snow depth at spatial resolution down to 10m GSD, with weekly updates. By fusing an elevation model and time series of Sentinel-1 and Sentinel-2 images with a recurrent convolutional neural network, we are able to produce country-wide high-resolution snow depth maps without in-situ data. Optionally, these maps can be further refined by combining them with sparse point observations from ground measurement stations. All maps are accompanied by spatially explicit maps of prediction uncertainty, thanks to a probabilistic deep learning framework.</details> |
| 14h00 - 14h30 | Orals 1-2 |
| 14h30 - 15h15 | <img src="/img/diamond.png"  width="20"> **Federica Arrigoni**, *Politecnico di Milano* <br><em>Graph solvability in structure from motion</em><br><details>  Structure from Motion (SfM) is a fundamental task in computer vision that aims at recovering both cameras and the 3D scene starting from multiple images. The problem can be conveniently represented as a “viewing graph”: each node corresponds to a camera/image and an edge is present between two nodes if the fundamental (or essential) matrix is available. While several research efforts on SfM have focused on devising more accurate and efficient algorithms, much less attention have been devoted to investigating theoretical aspects. In particular, a relevant question is establishing whether a viewing graph is “solvable”, i.e., it uniquely determines a configuration of cameras. This talk will give an overview on existing results on viewing graph solvability, starting from the calibrated case (where it is known that solvable graphs are those that are parallel rigid), reaching up the more complicated uncalibrated case (where the problem reduces to solving polynomial equations and it still offers open issues). </details> |
| | <span style="color:orange"> <b>Afternoon break</b> </span> <span style="color:orange"><b>& poster session </b></span> |
| 16h15 - 17h00 | <img src="/img/diamond.png"  width="20"> **Derek Lichti**, *The University of Calgary* <br><em>Efficient computation of object precision for terrestrial laser scanner viewpoint planning</em> <br><details> Building information models (BIMs) and digital twins (DTs) see increasing use in many sectors including construction, mining, energy, chemical processing and heritage, to respectively improve the construction and effective management of capital assets. A terrestrial laser scanner (TLS) is recognized as a highly effective reality capture technology for the creation of accurate models of the built environment. A key planning task is the determination of a set of TLS instrument locations or viewpoints (VPs) that will provide complete site coverage at the required level of positional accuracy. Under the assumption of an existing prior site model, greedy algorithm methods are commonly used to determine the set of VPs. Positional accuracy is most often measured in terms of single point radiated precision. However, this measure does not represent the quality of model objects, such as planes and cylinders, that would be derived from a TLS point cloud. Rigorous quantification of object positional accuracy requires point cloud simulation from the VPs by ray casting, which is computationally expensive. A new, more efficient approach is therefore proposed. Its basis is a model for the geometric distribution of range observations in angular space that is introduced into the least-squares normal equations formed to compute the covariance matrix of each object. This allows object precision to be more efficiently estimated by the evaluation of integrals. This presentation will first provide a brief overview of the TLS VP planning problem. The proposed method for object precision modelling will then be described and results from real data experiments will be presented. </details> |
| 17h00 - 17h45 | Orals 3-5 |
| 17h45 - 18h00 | Closing remarks |

<style>
.collapsible p {
  margin-top: 0;
}

.collapsible summary::-webkit-details-marker {
  display: none;
}

.collapsible summary {
  cursor: pointer;
  margin-left: 10px;
  font-weight: bold;
}

.collapsible p {
  margin: 0 0 10px 0;
}

table {
  border-collapse: collapse;
  border: none;
  background-color: transparent;
}

table td,
table th {
  border: none;
}

</style>
