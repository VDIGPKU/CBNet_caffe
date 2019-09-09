# CBNet: A Novel Composite Backbone Network Architecture for Object Detection

by Yudong Liu

This repository is modified on the base of [Detectron](https://github.com/facebookresearch/Detectron) @ [e8942c8](https://github.com/facebookresearch/Detectron/tree/e8942c882abf6e28fe68a626ec55028c9bdfe1cf) and [Cascade R-CNN](https://github.com/zhaoweicai/Detectron-Cascade-RCNN)

## Introduction

This repository is modified on the base of [Cascade R-CNN](https://github.com/zhaoweicai/Detectron-Cascade-RCNN)
 on the base of [Detectron](https://github.com/facebookresearch/Detectron). 

Please follow [Detectron](https://github.com/facebookresearch/Detectron) on how to install the environment.


## Citation

If you use our code/model/data, please cite our paper:




### Cascade Mask R-CNN with Bells & Whistles

<table><tbody>
<!-- START BELLS TABLE -->
<!-- TABLE HEADER -->
<!-- Info: we use wrap text in <sup><sub></sub><sup> to make is small -->
<th valign="bottom"><sup><sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;backbone&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</sub></sup></th>
<th valign="bottom"><sup><sub>type</sub></sup></th>
<th valign="bottom"><sup><sub>lr<br/>schd</sub></sup></th>
<th valign="bottom"><sup><sub>im/<br/>gpu</sub></sup></th>
<th valign="bottom"><sup><sub>box<br/>AP</sub></sup></th>
<th valign="bottom"><sup><sub>box<br/>AP50</sub></sup></th>
<th valign="bottom"><sup><sub>box<br/>AP75</sub></sup></th>
<th valign="bottom"><sup><sub>mask<br/>AP</sub></sup></th>
<th valign="bottom"><sup><sub>mask<br/>AP50</sub></sup></th>
<th valign="bottom"><sup><sub>mask<br/>AP75</sub></sup></th>
<th valign="bottom"><sup><sub>download<br/>links</sub></sup></th>
<!-- TABLE BODY -->
<tr>
<td align="left"><sup><sub>X-152-32x8d-FPN-IN5k-baseline</sub></sup></td>
<td align="left"><sup><sub>Mask</sub></sup></td>
<td align="left"><sup><sub>s1x</sub></sup></td>
<td align="right"><sup><sub>1</sub></sup></td>
<td align="right"><sup><sub>48.1</sub></sup></td>
<td align="right"><sup><sub>68.3</sub></sup></td>
<td align="right"><sup><sub>52.9</sub></sup></td>
<td align="right"><sup><sub>41.5</sub></sup></td>
<td align="right"><sup><sub>65.1</sub></sup></td>
<td align="right"><sup><sub>44.7</sub></sup></td>
<td align="left"><sup><sub><a href="https://s3-us-west-2.amazonaws.com/detectron/37129812/12_2017_baselines/e2e_mask_rcnn_X-152-32x8d-FPN-IN5k_1.44x.yaml.09_35_36.8pzTQKYK/output/train/coco_2014_train%3Acoco_2014_valminusminival/generalized_rcnn/model_final.pkl">model</a>&nbsp;|&nbsp;<a href="https://s3-us-west-2.amazonaws.com/detectron/37129812/12_2017_baselines/e2e_mask_rcnn_X-152-32x8d-FPN-IN5k_1.44x.yaml.09_35_36.8pzTQKYK/output/test/coco_2014_minival/generalized_rcnn/bbox_coco_2014_minival_results.json">boxes</a>&nbsp;|&nbsp;<a href="https://s3-us-west-2.amazonaws.com/detectron/37129812/12_2017_baselines/e2e_mask_rcnn_X-152-32x8d-FPN-IN5k_1.44x.yaml.09_35_36.8pzTQKYK/output/test/coco_2014_minival/generalized_rcnn/segmentations_coco_2014_minival_results.json">masks</a></sub></sup></td>
</tr>
<tr>
<td align="left"><sup><sub>[above without test-time aug.]</sub></sup></td>
<td align="right"><sup><sub></sub></sup></td>
<td align="right"><sup><sub></sub></sup></td>
<td align="right"><sup><sub></sub></sup></td>
<td align="right"><sup><sub>45.2</sub></sup></td>
<td align="right"><sup><sub>66.9</sub></sup></td>
<td align="right"><sup><sub>49.7</sub></sup></td>
<td align="right"><sup><sub>39.7</sub></sup></td>
<td align="right"><sup><sub>63.5</sub></sup></td>
<td align="right"><sup><sub>42.4</sub></sup></td>
<td align="right"><sup><sub></sub></sup></td>
</tr>
<tr>
<td align="left"><sup><sub>X-152-32x8d-FPN-IN5k-cascade</sub></sup></td>
<td align="left"><sup><sub>Mask</sub></sup></td>
<td align="left"><sup><sub>s1x</sub></sup></td>
<td align="right"><sup><sub>1</sub></sup></td>
<td align="right"><sup><sub>50.2</sub></sup></td>
<td align="right"><sup><sub>68.2</sub></sup></td>
<td align="right"><sup><sub>55.0</sub></sup></td>
<td align="right"><sup><sub>42.3</sub></sup></td>
<td align="right"><sup><sub>65.4</sub></sup></td>
<td align="right"><sup><sub>45.8</sub></sup></td>
<td align="left"><sup><sub><a href="http://www.svcl.ucsd.edu/projects/cascade-rcnn/X152-32x8d-FPN-cascade-rcnn-mask-aug.pkl">model</a>&nbsp;|&nbsp;<a href="http://www.svcl.ucsd.edu/projects/cascade-rcnn/results/bbox_coco_2014_minival_results_X152-32x8d-FPN-cascade-rcnn-mask-aug.json">boxes</a>&nbsp;|&nbsp;<a href="http://www.svcl.ucsd.edu/projects/cascade-rcnn/results/segmentations_coco_2014_minival_results_X152-32x8d-FPN-cascade-rcnn-mask-aug.json">masks</a></sub></sup></td>
</tr>
<tr>
<td align="left"><sup><sub>[above without test-time aug.]</sub></sup></td>
<td align="right"><sup><sub></sub></sup></td>
<td align="right"><sup><sub></sub></sup></td>
<td align="right"><sup><sub></sub></sup></td>
<td align="right"><sup><sub>48.1</sub></sup></td>
<td align="right"><sup><sub>66.7</sub></sup></td>
<td align="right"><sup><sub>52.6</sub></sup></td>
<td align="right"><sup><sub>40.7</sub></sup></td>
<td align="right"><sup><sub>63.7</sub></sup></td>
<td align="right"><sup><sub>43.8</sub></sup></td>
<td align="right"><sup><sub></sub></sup></td>
</tr>
<!-- END BELLS TABLE -->
</tbody></table>


<!-- END E2E FASTER AND MASK TABLE -->
</tbody></table>
