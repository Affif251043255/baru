---
title: "baru"
title-slide: false
---

:::: {.columns}
::: {.column width="50%"}

## Sample slides
#### PlaceHolderName
#### Universiti Malaysia Perlis
#### [placeholder@email.com](mailto:placeholder@email.com)

<audio id="bg-music" src="media/audio/sb.m4a" loop></audio>

<div id="audio-credit"
     style="position: absolute; bottom: 40px; right: 20px; font-size: 0.6em; opacity: 0.6;">
  Music: “Adrift” by Scott Buckley (CC BY 4.0)
</div>

<script>
  document.addEventListener('DOMContentLoaded', () => {
    const audio = document.getElementById('bg-music');
    const credit = document.getElementById('audio-credit');

    // hide credit by default
    credit.style.display = 'none';

    const test = new Audio('media/audio/bgm.mp3');

    test.addEventListener('canplaythrough', () => {
      // bgm.mp3 exists → use it, keep credit hidden
      audio.src = 'media/audio/bgm.mp3';
    }, { once: true });

    test.addEventListener('error', () => {
      // bgm.mp3 missing → sb.m4a will play → show credit
      credit.style.display = 'block';
    }, { once: true });

    document.addEventListener('click', () => {
      if (Reveal.getIndices().h === 0) {
        audio.volume = 0.5;
        audio.play();
      }
    }, { once: true });

    Reveal.on('slidechanged', (event) => {
      if (event.indexh > 0) { audio.pause(); }
      else { audio.play(); }
    });
  });
</script>


:::

::: {.column width="50%"}
![](media/pics/logo1.png)
:::

::::



<span class="slide-title" data-title="My Hidden Slide Name"></span>

![](media/pics/wide.jpeg)



:::: {.columns}
::: {.column width="50%"}
### Visualizing the Gas Law
**Interactive Model:**

- P, V, and T relationships.
- Use the slider to adjust pressure.
- Observe the phase boundary.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/sample.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::


### PartLength Analysis for Machine 1 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 1, Temp: 303, Pres: 100).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 1, Temp: 303, Pres: 100).
</div>
</div>


### PartLength Analysis for Machine 1 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 1, Temp: 303, Pres: 300).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 1, Temp: 303, Pres: 300).
</div>
</div>


### PartLength Analysis for Machine 1 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 1, Temp: 338, Pres: 200).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 1, Temp: 338, Pres: 200).
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 1, Temp: 373, Pres: 100).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 1, Temp: 373, Pres: 100).
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 1, Temp: 373, Pres: 300).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 1, Temp: 373, Pres: 300).
</div>
</div>


### PartLength Analysis for Machine 2 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 2, Temp: 303, Pres: 200).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 2, Temp: 303, Pres: 200).
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 2, Temp: 338, Pres: 100).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 2, Temp: 338, Pres: 100).
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 2, Temp: 338, Pres: 300).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 2, Temp: 338, Pres: 300).
</div>
</div>


### PartLength Analysis for Machine 2 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 2, Temp: 373, Pres: 200).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 2, Temp: 373, Pres: 200).
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 3, Temp: 303, Pres: 100).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 3, Temp: 303, Pres: 100).
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 3, Temp: 303, Pres: 300).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 3, Temp: 303, Pres: 300).
</div>
</div>


### PartLength Analysis for Machine 3 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 3, Temp: 338, Pres: 200).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 3, Temp: 338, Pres: 200).
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 3, Temp: 373, Pres: 100).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 3, Temp: 373, Pres: 100).
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartLength (Machine: 3, Temp: 373, Pres: 300).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartLength (Machine: 3, Temp: 373, Pres: 300).
</div>
</div>


### PartResistance Analysis for Machine 1 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 1, Temp: 303, Pres: 200).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 1, Temp: 303, Pres: 200).
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 1, Temp: 338, Pres: 100).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 1, Temp: 338, Pres: 100).
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 1, Temp: 338, Pres: 300).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 1, Temp: 338, Pres: 300).
</div>
</div>


### PartResistance Analysis for Machine 1 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 1, Temp: 373, Pres: 200).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 1, Temp: 373, Pres: 200).
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 2, Temp: 303, Pres: 100).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 2, Temp: 303, Pres: 100).
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 2, Temp: 303, Pres: 300).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 2, Temp: 303, Pres: 300).
</div>
</div>


### PartResistance Analysis for Machine 2 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 2, Temp: 338, Pres: 200).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 2, Temp: 338, Pres: 200).
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 2, Temp: 373, Pres: 100).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 2, Temp: 373, Pres: 100).
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 2, Temp: 373, Pres: 300).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 2, Temp: 373, Pres: 300).
</div>
</div>


### PartResistance Analysis for Machine 3 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 3, Temp: 303, Pres: 200).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 3, Temp: 303, Pres: 200).
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 3, Temp: 338, Pres: 100).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 3, Temp: 338, Pres: 100).
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 3, Temp: 338, Pres: 300).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 3, Temp: 338, Pres: 300).
</div>
</div>


### PartResistance Analysis for Machine 3 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### No Control Chart Generated
  Not enough valid numeric data was found to generate an Individual Control Chart for PartResistance (Machine: 3, Temp: 373, Pres: 200).
</div>
<div class="column">
  #### No Process Capability Generated
  Not enough valid numeric data was found to generate Process Capability for PartResistance (Machine: 3, Temp: 373, Pres: 200).
</div>
</div>


## Machine Process Analysis: Control Charts & Capability


### PartLength Analysis for Machine 1 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 1 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m1_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m1_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 2 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m2_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m2_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartLength Analysis for Machine 3 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partlength_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartLength under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partlength_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartLength meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 1 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m1_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m1_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t303_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t303_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 303 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t303_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t303_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 338 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t338_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t338_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t373_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t373_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 2 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m2_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m2_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 303 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t303_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t303_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 100 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t338_p100.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t338_p100.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 338 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t338_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t338_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>


### PartResistance Analysis for Machine 3 at 373 K, 200 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t373_p200.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t373_p200.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>

***
### PartResistance Analysis for Machine 3 at 373 K, 300 kPa
<div class="columns">
<div class="column">
  #### Individual Control Chart
  <img src='media/plots/control_chart_partresistance_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  The individual control chart assesses the stability of the process for PartResistance under these conditions. Points outside control limits (red lines) indicate special cause variation.
</div>
<div class="column">
  #### Process Capability
  <img src='media/plots/process_capability_partresistance_m3_t373_p300.png' width='100%' height='auto' style='border:none;'>
  This plot shows how well the process output for PartResistance meets specification limits. Cp (Process Potential) and Cpk (Process Performance) values indicate the capability.
  <br>
  **Note:** Specification Limits (LSL, USL, Target) are assumed for demonstration. For accurate analysis, replace them with actual engineering specifications.
</div>
</div>

# Bibliography
<div id="refs"></div>
