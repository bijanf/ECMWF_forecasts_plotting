# Model Comparison for added value

As observation dataset I have used the CHELSA and CHIRPS. It was recommended that the grided observation is finer than the model run. I used the [spatially distributed added value index](https://link.springer.com/article/10.1007/s00382-020-05400-5) as the metric to calculate the added value of RCM simulations. This metric measures the difference in the probability density functions (PDFs) at each grid-cell between a model and an observation source, and then compares the results of the RCM and GCM in order to spatially compute the added value index.



## Downscaling added value for the Precipitation

### Relative probability difference (D) and added value (D_GCM minus D_RCM)
<table>
  <tr>
      <td> </td>
      <td>CHIRPS climatology (mm/day)</td>
      <td>CHELSA climatology (mm/day)</td>
  </tr>
  <tr>
      <td> </td>
      <td><img src="./pr_chirps_climatology_50th.png" alt="time series" width="400"></td>
      <td><img src="./pr_chelsa_climatology_50th.png" alt="seasonal cycle" width="400"></td>
  </tr>




  <tr>
        <td> </td>
        <td> D GCM </td>
	      <td> D RCM </td>
	      <td>Added Value</td>
  </tr>
  <tr>
        <td>CCLM-ERAInterim w.r.t. CHIRPS</td>
        <td><img src="./DM_GCM_chirps.png" alt="time series" width="400"></td>
        <td><img src="./DM_RCM_chirps.png" alt="seasonal cycle" width="400"></td>
	<td><img src="./added_value_chirps.png" alt="seasonal cycle" width="400"></td>
    </tr>


  <tr>
        <td> </td>
        <td>D GCM</td>
	      <td>D RCM</td>
	      <td>Added Value</td>
  </tr>
  <tr>
        <td>CCLM-ERAInterim w.r.t. CHELSA</td>
        <td><img src="./DM_GCM_chelsa.png" alt="time series" width="400"></td>
        <td><img src="./DM_RCM_chelsa.png" alt="seasonal cycle" width="400"></td>
	<td><img src="./added_value_chelsa.png" alt="seasonal cycle" width="400"></td>
  </tr>

<tr>
      <td> </td>
      <td>D GCM</td>
      <td>D RCM</td>
      <td>Added Value</td>
</tr>
<tr>
      <td>CCLM-MPI-ESM w.r.t. CHIRPS</td>
      <td><img src="./DM_GCM_MPI-ESM_chirps.png" alt="time series" width="400"></td>
      <td><img src="./DM_RCM_MPI-ESM_chirps.png" alt="seasonal cycle" width="400"></td>
<td><img src="./added_value_MPI-ESM_chirps.png" alt="seasonal cycle" width="400"></td>
</tr>

<tr>
      <td> </td>
      <td>D GCM</td>
      <td>D RCM</td>
      <td>Added Value</td>
</tr>
<tr>
      <td>CCLM-MPI-ESM w.r.t. CHELSA</td>
      <td><img src="./DM_GCM_MPI-ESM_chelsa.png" alt="time series" width="400"></td>
      <td><img src="./DM_RCM_MPI-ESM_chelsa.png" alt="seasonal cycle" width="400"></td>
<td><img src="./added_value_MPI-ESM_chelsa.png" alt="seasonal cycle" width="400"></td>
</tr>


</table>
# ECMWF_forecasts_plotting
