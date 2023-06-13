---
layout: page
---

# Schedule


Location: <span style="color:blue"> <b>West 211</b> </span> 
<br>
Accepted papers: [cvf repository](https://openaccess.thecvf.com/CVPR2023_workshops/PCV)

| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 13h - 13h10 | Welcome |
| 13h10-13h50 | <img src="/img/diamond.png"  width="20"> [**Konrad Schindler**](https://igp.ethz.ch/personen/person-detail.html?persid=143986), *ETH Zurich* <br><em>High-Resolution, Country-Scale Snow Depth Estimation From Satellite Images</em><br><details>Monitoring snow depth is important for hydrology, hydro-power planning, ecology, and Alpine safety. Existing methods to estimate snow depth over large areas are typically limited to ground sampling distances of ca. 1km. This limits their usage in high alpine areas, where that resolution fails to capture local snow distribution patterns caused by the pronounced topography. I will present recent advances that make it possible to map snow depth at spatial resolution down to 10m GSD, with weekly updates. By fusing an elevation model and time series of Sentinel-1 and Sentinel-2 images with a recurrent convolutional neural network, we are able to produce country-wide high-resolution snow depth maps without in-situ data. Optionally, these maps can be further refined by combining them with sparse point observations from ground measurement stations. All maps are accompanied by spatially explicit maps of prediction uncertainty, thanks to a probabilistic deep learning framework.</details> |
| 13h50-14h00 | Liyuan Zhu (ETH Zurich) <br> [<em>DeFlow: Self-Supervised 3D Motion Estimation of Debris Flow</em>](https://openaccess.thecvf.com/content/CVPR2023W/PCV/html/Zhu_DeFlow_Self-Supervised_3D_Motion_Estimation_of_Debris_Flow_CVPRW_2023_paper.html) |
| 14h00-14h10 | Weihang Ran (The University of Tokyo) <br> [<em>Few-Shot Depth Completion Using Denoising Diffusion Probabilistic Model </em>](https://openaccess.thecvf.com/content/CVPR2023W/PCV/html/Ran_Few-Shot_Depth_Completion_Using_Denoising_Diffusion_Probabilistic_Model_CVPRW_2023_paper.html) |
| 14h10-14h20 | Teng Wu (LaSTIG, France) <br> [<em>PSMNet-FusionX3: LiDAR-Guided Deep Learning Stereo Dense Matching on Aerial Image</em>](https://openaccess.thecvf.com/content/CVPR2023W/PCV/html/Wu_PSMNet-FusionX3_LiDAR-Guided_Deep_Learning_Stereo_Dense_Matching_on_Aerial_Images_CVPRW_2023_paper.html) |
| 14h20-14h30 | Ewelina Rupnik (LaSTIG, France) <br> [<em>Pointless Global Bundle Adjustment With Relative Motions Hessians</em>](https://openaccess.thecvf.com/content/CVPR2023W/PCV/html/Rupnik_Pointless_Global_Bundle_Adjustment_With_Relative_Motions_Hessians_CVPRW_2023_paper.html) |
| 14h30-14h40 | Olaf Wysocki (Technical University of Munich) <br> [<em>Scan2LoD3: Reconstructing Semantic 3D Building Models at LoD3 Using Ray Casting and Bayesian Networks </em>](https://openaccess.thecvf.com/content/CVPR2023W/PCV/html/Wysocki_Scan2LoD3_Reconstructing_Semantic_3D_Building_Models_at_LoD3_Using_Ray_CVPRW_2023_paper.html) |
| 14h40-14h50 |  Sunghwan Yoo (York University, Canada) <br> [<em>Human Vision Based 3D Point Cloud Semantic Segmentation of Large-Scale Outdoor Scenes</em>](https://openaccess.thecvf.com/content/CVPR2023W/PCV/html/Yoo_Human_Vision_Based_3D_Point_Cloud_Semantic_Segmentation_of_Large-Scale_CVPRW_2023_paper.html) |
| 14h50-15h00 | Abhisek Maiti (University of Twente, The Netherlands)  <br> [<em>TransFusion: Multi-Modal Fusion Network for Semantic Segmentation </em>](https://openaccess.thecvf.com/content/CVPR2023W/PCV/html/Maiti_TransFusion_Multi-Modal_Fusion_Network_for_Semantic_Segmentation_CVPRW_2023_paper.html) |
| 15h00-15h10 | Maryam Jameela (York University, Canada)  <br> [<em>Fusion-SUNet: Spatial Layout Consistency for 3D Semantic Segmentation</em>](https://openaccess.thecvf.com/content/CVPR2023W/PCV/html/Jameela_Fusion-SUNet_Spatial_Layout_Consistency_for_3D_Semantic_Segmentation_CVPRW_2023_paper.html) |
| 15h10-15h40 | <span style="color:orange"> <b>Coffee break</b> </span> | 
| 15h40-16h25 | <span style="color:orange"> <b>Poster session</b> </span> |
| 16h25-17h05 | <img src="/img/diamond.png"  width="20"> [**Federica Arrigoni**](https://www.deib.polimi.it/ita/personale/dettagli/765978), *Politecnico di Milano* <br><em>Graph solvability in structure from motion</em><br><details>  Structure from Motion (SfM) is a fundamental task in computer vision that aims at recovering both cameras and the 3D scene starting from multiple images. The problem can be conveniently represented as a “viewing graph”: each node corresponds to a camera/image and an edge is present between two nodes if the fundamental (or essential) matrix is available. While several research efforts on SfM have focused on devising more accurate and efficient algorithms, much less attention have been devoted to investigating theoretical aspects. In particular, a relevant question is establishing whether a viewing graph is “solvable”, i.e., it uniquely determines a configuration of cameras. This talk will give an overview on existing results on viewing graph solvability, starting from the calibrated case (where it is known that solvable graphs are those that are parallel rigid), reaching up the more complicated uncalibrated case (where the problem reduces to solving polynomial equations and it still offers open issues). </details> |
| 17h05-17h45 | <img src="/img/diamond.png"  width="20"> [**Derek Lichti**](https://profiles.ucalgary.ca/derek-lichti), *The University of Calgary* <br><em>Efficient computation of object precision for terrestrial laser scanner viewpoint planning</em> <br><details> Building information models (BIMs) and digital twins (DTs) see increasing use in many sectors including construction, mining, energy, chemical processing and heritage, to respectively improve the construction and effective management of capital assets. A terrestrial laser scanner (TLS) is recognized as a highly effective reality capture technology for the creation of accurate models of the built environment. A key planning task is the determination of a set of TLS instrument locations or viewpoints (VPs) that will provide complete site coverage at the required level of positional accuracy. Under the assumption of an existing prior site model, greedy algorithm methods are commonly used to determine the set of VPs. Positional accuracy is most often measured in terms of single point radiated precision. However, this measure does not represent the quality of model objects, such as planes and cylinders, that would be derived from a TLS point cloud. Rigorous quantification of object positional accuracy requires point cloud simulation from the VPs by ray casting, which is computationally expensive. A new, more efficient approach is therefore proposed. Its basis is a model for the geometric distribution of range observations in angular space that is introduced into the least-squares normal equations formed to compute the covariance matrix of each object. This allows object precision to be more efficiently estimated by the evaluation of integrals. This presentation will first provide a brief overview of the TLS VP planning problem. The proposed method for object precision modelling will then be described and results from real data experiments will be presented. </details> |
| 17h45-18h00 | Closing remarks |

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
