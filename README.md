# Optic Flow Encoding by Neurons in the Visual Cortex

This repository contains primary data and analysis code for the paper <b>"Binocular Integration of Retinal Motion Information Underlies Optic Flow Processing by the Cortex"</b> by Rasmussen and Matsumoto et al. (2021, Current Biology).

[Link to publication](https://doi.org/10.1016/j.cub.2020.12.034)
<br> 

Folder structure and content
--------
The main folders contain data obtained from the four visual cortical areas sampled from: V1, RL/A, AM, and PM. 

The subfolders contain data from a given visual cortical area obtained from either wild-type or Frmd7tm mice.

Within each subfolder (wild-type and Frmd7tm) is a .mat file containing several data matrices:
<ul>
<li> "Cells_master_RR" contain tuning curves of all visually responsive and reliable (RR) cells at 10 and 40 <span>&#176;</span>/s
<li> "Cells_master_RR_traces_10ds/40ds" contain Ca<sup>2+</sup> response traces of all RR cells at 10 or 40 <span>&#176;</span>/s
<li> "StimOrder" contains a string of the ordered stimulus conditions   
</ul>

Contact 
--------
Questions or further inquiries can be directed to: 
<ul>
<li>Rune N. Rasmussen (E: rune.nguyen.rasmussen@sund.ku.dk)
<li>Akihiro Matsumoto (E: aki.matsumoto@dandrite.au.dk)
<li>Keisuke Yonehara (E: keisuke.yonehara@dandrite.au.dk)
<ul>
