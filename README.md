# Baseline_Framework_for_Image_Text_Matching
PyTorch implementation for a strong baseline for image-text matching (earliest come in mid-year).  
It is built on top of the [SGRAF](https://github.com/Paranioar/SGRAF) and [Cross-modal_Retrieval_Tutorial](https://github.com/Paranioar/Cross-modal_Retrieval_Tutorial).

**The reported results**
<table>
   <tr> <td rowspan="2">Dataset</td> <td rowspan="2", align="center">Model</td> 
        <td colspan="3", align="center">Sentence retrieval</td> <td colspan="3", align="center">Image retrieval</td> </tr>
   <tr> <td>R@1</td><td>R@5</td><td>R@10</td> <td>R@1</td><td>R@5</td><td>R@10</td> </tr>
   <tr> <td rowspan="3">Flick30k</td>
        <td>Baseline(single model)</td> <td>78.1</td><td>94.5</td><td>97.6</td> <td>57.7</td><td>82.5</td><td>88.9</td> </tr>
   <tr> <td>Baseline(two model)</td> <td>80.2</td><td>95.4</td><td>98.3</td> <td>59.4</td><td>83.2</td><td>89.3</td> </tr>
   <tr> <td>Base+VSRN(sinle model)</td> <td>77.7</td><td>93.8</td><td>96.8</td> <td>59.0</td><td>83.2</td><td>89.3</td> </tr>
   <tr> <td>Base+VSRN(two model)</td> <td>79.8</td><td>95.0</td><td>97.9</td> <td>62.2</td><td>85.5</td><td>91.1</td> </tr>
</table> 
