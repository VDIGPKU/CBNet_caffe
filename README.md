# CBNet: A Novel Composite Backbone Network Architecture for Object Detection

by Yudong Liu



## Introduction

This repository is modified on [Cascade R-CNN](https://github.com/zhaoweicai/Detectron-Cascade-RCNN), which is re-implemented by by Zhaowei Cai and Nuno Vasconcelos on the base of [Detectron](https://github.com/facebookresearch/Detectron). 

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
