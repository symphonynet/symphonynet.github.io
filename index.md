---
driveId: ikmgqp3V7k8
layout: default
title: SymphonyNet
---
# Table of Contents
*   **Video Demostration**
*   **More Samples**
*   **Dataset Introduction and Analysis**


## Video Demonstration

<!---
Include this next line in your .md file for Google Drive videos, make sure to put your video ID up there!

Example:     driveId: 0B7L_dMcaZknxVTRndmdSQ0F5OFE/preview
-->

{% include googleDrivePlayer.html id=page.driveId %}

We choose the first four measures from *Doctor Who - 11th Doctor Theme "I am the Doctor!"* as our model input. The generated excerpt sounds both intense and grand with tremendous momentum. So we take it as a new soundtrack for the Wave Scene in the movie *Interstellar*. Hope you enjoy and like it.
## More Samples

### Continuation of a given prime

<table>
   <tr>
      <td></td>
      <td align="center"><b>Prime I (5-bar length)</b></td>
      <td align="center"><b>Prime II (8-bar length)</b></td>
   </tr>
   <tr>
      <td align="center">Input</td>
      <td><audio src="{{ site.url }}/assets/prime/prime_5.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
      <td><audio src="{{ site.url }}/assets/prime/prime_8.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
   </tr>
   <tr>
      <td rowspan="4" align="center">SymphonyNet</td>
      <td><audio src="{{ site.url }}/assets/prime/prime_51.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
      <td><audio src="{{ site.url }}/assets/prime/prime_81.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
   </tr>
   <tr>
      
      <td><audio src="{{ site.url }}/assets/prime/prime_52.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
      <td><audio src="{{ site.url }}/assets/prime/prime_82.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
   </tr>
   <tr>
      
      <td><audio src="{{ site.url }}/assets/prime/prime_53.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
      <td><audio src="{{ site.url }}/assets/prime/prime_83.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
   </tr>
   <tr>
      
      <td><audio src="{{ site.url }}/assets/prime/prime_54.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
      <td><audio src="{{ site.url }}/assets/prime/prime_84.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
   </tr>
   <tr>
      <td align="center">Human</td>
      <td><audio src="{{ site.url }}/assets/prime/prime_50.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
      <td><audio src="{{ site.url }}/assets/prime/prime_80.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
   </tr>
</table>

### Generation with less restriction



<table> 
   <tr>
      <td align="center"><b>      Conditioned on chord progression    </b></td>
      <td align="center"><b>              From scratch              </b></td>
   </tr>
   <tr>
      <td>  <audio src="{{ site.url }}/assets/chord/chord1.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
      <td><audio src="{{ site.url }}/assets/unconditioned/scratch1.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
   </tr>
   <tr>
      <td>  <audio src="{{ site.url }}/assets/chord/chord2.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
      <td><audio src="{{ site.url }}/assets/unconditioned/scratch2.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
   </tr>
   <tr>
      <td>  <audio src="{{ site.url }}/assets/chord/chord3.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
      <td><audio src="{{ site.url }}/assets/unconditioned/scratch3.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
   </tr>
   <tr>
      <td>  <audio src="{{ site.url }}/assets/chord/chord4.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
      <td><audio src="{{ site.url }}/assets/unconditioned/scratch4.mp3" preload="none" controls>   Your browser doesn't support audio tag. </audio></td>
   </tr>
   <tr>
      <td></td>
   </tr>
</table>


## Dataset Introduction and Analysis
The first worldwide large-scale symbolic symphonic music dataset.

### Symphony MIDI Dataset Overview
<style type="text/css">
.tg  {border-collapse:collapse;border-color:#ccc;border-spacing:0;}
.tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{background-color:#f0f0f0;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-l3uw{font-family:Verdana, Geneva, sans-serif !important;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-l3uw"><span style="font-style:normal;text-decoration:none">Total Count (MIDIs)</span></th>
    <th class="tg-l3uw">Total Length</th>
    <th class="tg-l3uw"> Avg. Length</th>
    <th class="tg-l3uw">Avg. Tracks</th>
    <th class="tg-l3uw"><span style="font-style:normal;text-decoration:none">Time Signature</span></th>
    <th class="tg-l3uw">Keys</th>
    <th class="tg-l3uw">Instruments</th>
    <th class="tg-l3uw">Total Count (Notes)</th>
    <th class="tg-l3uw">Avg. Notes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-l3uw">46359</td>
    <td class="tg-l3uw">3284 Hours</td>
    <td class="tg-l3uw">256 Sec</td>
    <td class="tg-l3uw">20</td>
    <td class="tg-l3uw">108</td>
    <td class="tg-l3uw">29</td>
    <td class="tg-l3uw">128</td>
    <td class="tg-l3uw"><span style="font-weight:400;font-style:normal;text-decoration:none">279 million</span></td>
    <td class="tg-l3uw">6013</td>
  </tr>
</tbody>
</table>

### Comparison With Other Datasets

<style type="text/css">
.tg  {border-collapse:collapse;border-color:#ccc;border-spacing:0;}
.tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{background-color:#f0f0f0;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-1wig{font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-1wig">Dataset</th>
    <th class="tg-amwm">Scores Count</th>
    <th class="tg-amwm">Notes Count (M)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">MAETRO</td>
    <td class="tg-baqh">1184</td>
    <td class="tg-baqh">6</td>
  </tr>
  <tr>
    <td class="tg-0lax">GiantMIDI-Piano</td>
    <td class="tg-baqh">10854</td>
    <td class="tg-baqh">39</td>
  </tr>
  <tr>
    <td class="tg-0lax">MMD</td>
    <td class="tg-baqh">1524557</td>
    <td class="tg-baqh">2075</td>
  </tr>
  <tr>
    <td class="tg-0lax">LMD</td>
    <td class="tg-baqh">148403</td>
    <td class="tg-baqh">535</td>
  </tr>
  <tr>
    <td class="tg-1wig">Symphony MIDI Dataset</td>
    <td class="tg-amwm">46187</td>
    <td class="tg-amwm">279</td>
  </tr>
</tbody>
</table>

### Further exploration and Analysis

- **Time Signature and Key Signature**

<img src="/assets/graphs/ts_ks.png" style="width:80%;height:80%;">

- **Instruments and tracks**

<img src="/assets/graphs/instru_track_pct.png" style="width:80%;height:80%;">

- **Measures**

<img src="/assets/graphs/measure_stats.png" style="width:80%;height:80%;">


