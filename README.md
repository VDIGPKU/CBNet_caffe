# CBNet: A Novel Composite Backbone Network Architecture for Object Detection

by Yudong Liu



## Introduction

This repository is modified on [Cascade R-CNN](https://github.com/zhaoweicai/Detectron-Cascade-RCNN), which is re-implemented by by Zhaowei Cai and Nuno Vasconcelos on the base of [Detectron](https://github.com/facebookresearch/Detectron). 

Please follow [Detectron](https://github.com/facebookresearch/Detectron) on how to install the environment.


## Citation

If you use our code/model/data, please cite our paper:
https://arxiv.org/abs/1909.03625

Our code is free for research, but needs authorization for commerce.


### Cascade Mask R-CNN without Bells & Whistles

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
<!--th valign="bottom"><sup><sub>download<br/>links</sub></sup></th>
<!-- TABLE BODY -->
  
<tr>
<td align="left"><sup><sub>[X-152-32x8d-FPN-IN5k-cascade]</sub></sup></td>
<td align="left"><sup><sub>Mask</sub></sup></td>
<td align="left"><sup><sub>s1x</sub></sup></td>
<td align="right"><sup><sub>1</sub></sup></td>
<td align="right"><sup><sub>48.3</sub></sup></td>
<td align="right"><sup><sub>67.0</sub></sup></td>
<td align="right"><sup><sub>52.8</sub></sup></td>
<td align="right"><sup><sub>41.0</sub></sup></td>
<td align="right"><sup><sub>64.1</sub></sup></td>
<td align="right"><sup><sub>44.2</sub></sup></td>
</tr> 

<tr>
<td align="left"><sup><sub>Dual-X-152-32x8d-FPN-IN5k-cascade</sub></sup></td>
<td align="left"><sup><sub>Mask</sub></sup></td>
<td align="left"><sup><sub>s1x</sub></sup></td>
<td align="right"><sup><sub>1</sub></sup></td>
<td align="right"><sup><sub>50.0</sub></sup></td>
<td align="right"><sup><sub>68.8</sub></sup></td>
<td align="right"><sup><sub>54.6</sub></sup></td>
<td align="right"><sup><sub>42.0</sub></sup></td>
<td align="right"><sup><sub>64.6</sub></sup></td>
<td align="right"><sup><sub>45.6</sub></sup></td>
</tr>

<!-- END BELLS TABLE -->
</tbody></table>


<!-- END E2E FASTER AND MASK TABLE -->
</tbody></table>
