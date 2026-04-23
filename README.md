

### Dataset:
https://colab.research.google.com/drive/1V5_scElgR9ReoHiPwzVCMTZLINxCaMOh?usp=sharing

Foi utilizado o dataset de detecção de dengue disponível no Kaggle, contendo dados clínicos e laboratoriais de pacientes.

Link:
https://www.kaggle.com/datasets/aravind3505/dengue-detection-dataset-clinical-data

### Features

- **age**: idade do paciente  
- **gender**: sexo do paciente  
- **hemoglobin_g_dl**: nível de hemoglobina (g/dL)  
- **wbc_count**: contagem de leucócitos  
- **differential_count**: contagem diferencial de leucócitos  
- **rbc_count**: contagem de hemácias  
- **platelet_count**: contagem de plaquetas  
- **platelet_distribution_width**: variação do tamanho das plaquetas (PDW)  
- **dengue_label**: variável alvo (0 = não possui dengue, 1 = possui dengue)

### Pré-processamento de dados

Foram realizadas etapas básicas de limpeza e preparação dos dados:

- remoção de valores ausentes  
- remoção de registros duplicados  
- padronização dos nomes das variáveis para manter consistência na análise  
