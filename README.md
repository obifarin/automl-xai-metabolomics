# automl-xai-metabolomics
code base for the paper: Automated machine learning and explainable AI (AutoML-XAI) for metabolomics

## How to use code
- Clone the repository. <br>
- Build the docker. 
`docker build -t Dockerfile.`
- Run the docker container. 
- Run jupyter notebook. <br>
Note that the autoML models are saved as `askl_17_OC_3600.pkl` and `askl_RCC_600.pkl` for the OC and RCC dataset respectively. You will need to unzip. 

## Notebook contents
<table>
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>automl-SHAP-RCC.ipynb</td>
    <td>Implementation of autosklearn and SHAP for the RCC Dataset.</td>
  </tr>
  <tr>
    <td>RCC-model-error-analysis.ipynb</td>
    <td>Error analysis of the autoML RCC diagnostic model.</td>
  </tr>
   <tr>
    <td>data-preparation.ipynb</td>
    <td>Data preparation for the RCC metabolomics dataset.</td>
  </tr>
    <tr>
    <td>automl-SHAP-OC.ipynb</td>
    <td>Implementation of autosklearn and SHAP for the RCC Dataset.</td>
  </tr>
    <tr>
    <td>OC-model-error-analysis.ipynb</td>
    <td>Error analysis of the autoML OC diagnostic model.</td>
  </tr>
</table>
