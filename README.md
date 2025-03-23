This repository contains the datasets for the paper: **Assessing lexical ambiguity resolution in language models with new WiC datasets in Galician and Spanish.**  


## Datasets 

The repository includes:  
- **Galician**: Training, development, and test sets.  
- **Spanish**: Development and test sets.

| Split      | Inst. | Uniq. | V   | N   | R  | A   |
|------------|-------|-------|-----|-----|----|-----|
| Gl_Train   | 1500  | 1187  | 271 | 454 | 7  | 768 |
| Gl_Dev     | 400   | 278   | 71  | 113 | 7  | 209 |
| Gl_Test    | 1400  | 905   | 274 | 536 | 13 | 577 |
|------------|-------|-------|-----|-----|----|-----|
| Spa_Dev    | 200   | 190   | 46  | 104 | 2  | 48  |
| Spa_Test   | 800   | 641   | 168 | 451 | 4  | 177 |

## Dataset Format  

Each dataset follows the [**WiC structure**](https://arxiv.org/abs/1808.09121):  


| Target Word | PoS | Position | Context 1 | Context 2 | Label |
|-------------|---------|----------|-----------|-----------|-------|
| estoupar | V       | 2-2      | *A botella estoupou.* | *O xefe estoupou cando soubo da dimisión do secretario.* | **0** |
| incapaz   | A       | 1-1      | *É incapaz de chegar á cidade sen coche.* | *Foi incapaz de obter fondos.* | **1** |
| depósito  | N       | 2-4      | *Tengo un depósito de mil euros.* | *Tienen mucho dinero en depósito.* | **0** |
| importante| A       | 7-8      | *Tu camino ya no parece ser tan importante.* | *El sistema de registro de población sigue teniendo importantes funciones.* | **1** |


## Citation  

If you use the dataset, please cite the following paper: 

