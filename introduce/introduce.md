## About GrainPest
### What is GrainPest
  GrainPest is an image dataset for stored-grain pest detection on the surface of grain bulks. It contains 16358 images, including six common species of stored-grain pest: Rusty grain beetle, Sawtoothed grain beetle, Lesser grain borer, Red flour beetle, Maize weevil, and Rice weevil. A total of 66372 pest instances with detection bounding boxes were annotated. All the pest images were taken by dome cameras. Figure 1 shows the images of specimen pests of these six species of stored-grain pests.
  ![图片名称](https://github.com/tjdhhx/GrainPest/blob/main/img/fig1.png)  
Figure 1. Images of specimen pests of (a) Rusty grain beetle, (b) Sawtoothed grain beetle, (c) Lesser grain borer, (d) Red flour beetle, (e) Maize weevil, and (f) Rice weevil adults.
### How to Collect Pest Images
GrainPest contains three Parts. The images in Part I were naturally grown pests in granaries, these images were derived from the videos taken by grain keepers. As the quality of these images varies greatly due to the non-normative operations of grain keepers, we further collected images by introducing pests in both granaries and the laboratory to acquire more high-quality pest images. As a result, the images in Part II and Part III consist of introduced pests from granaries and the laboratory, respectively. We developed an image collection system to acquire images of introduced pests in trays in granaries and laboratory. We acquired the pest images by controlling the dome camera to sequentially capture pests in trays at each capture point. The spatial relationship between the dome camera capture points and the trays is shown in figure 2. The schematic diagram of the capture points is shown in Figure 3.
![图片名称](https://github.com/tjdhhx/GrainPest/blob/main/img/fig2a.png)  
Figure 2. The sketch of the spatial relationship between the dome camera, capture points and the trays.
![图片名称](https://github.com/tjdhhx/GrainPest/blob/main/img/fig3.png)  
Figure 3. The schematic diagram of the capture points.
### Small Size of Pest Instances
The pest instances in GrainPest are in small size. We define the pixel size as the maximum dimension (either length or width) of a pest instance's bounding box. Figure 4 shows the distribution of the pixel size of each pest category in GrainPest in three parts.
![图片名称](https://github.com/tjdhhx/GrainPest/blob/main/img/fig4.png)  
Figure 4. Distribution of the pixel size of each category in GrainPest. (a) Distribution of the pixel size of each pest category in Part I. (b) Distribution of the pixel size of each pest category in Part II. (c) Distribution of the pixel size of each pest category in Part III.
As demonstrated in figure 4, the pixel size of most pest instances does not exceed 64 pixels. This indicates that the pest instances in GrainPest are smaller compared to object instances in other common datasets such as Pascal VOC [1] or MS COCO [2].
### Dataset Reference
[1] Everingham, M., Van Gool, L., Williams, C. K. I., Winn, J., & Zisserman, A. (2010). The Pascal Visual Object Classes (VOC) Challenge. Int. J. Comput. Vis., 88(2), 303–338. https://doi.org/10.1007/s11263-009-0275-4

[2] Lin, T. Y., Maire, M., Belongie, S., Bourdev, L., Girshick, R., Hays, J., ... Dollar, P. (2014). Microsoft COCO: Common Objects in Context. Proc. European Conf. on Computer Vision. pp. 740–755. Berlin: Springer. https://doi.org/10.1007/978-3-319-10602-1_48
