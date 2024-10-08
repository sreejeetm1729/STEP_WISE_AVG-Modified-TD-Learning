This code differs from standard Temporal Difference (TD) learning primarily through the use of linear function approximation with a projection matrix derived from the feature matrix and stationary distribution. Instead of the iterative updates commonly seen in standard TD, it explicitly calculates the fixed point of the TD learning process by solving a system of linear equations, incorporating both the discount factor and transition probabilities. The code tracks error convergence over multiple epochs, providing robust performance evaluation by averaging these errors. Additionally, it employs two update schemes: one that combines reward-dependent and feature-dependent updates with accumulated gradients, and another that uses direct TD-like updates within the projected feature space. These approaches offer a more nuanced analysis of the algorithm's stability and convergence, making it particularly suitable for research settings where advanced function approximation and error tracking are essential.
<table>
  <tr>
    <td>
      <img src="https://github.com/sreejeetm1729/STEP_WISE_AVG-Modified-TD-Learning/blob/main/Figure_step_wise_avg_TD.png" style="width:800px">
    </td>
  </tr>

