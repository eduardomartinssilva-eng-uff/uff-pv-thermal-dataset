# uff-pv-thermal-dataset

Este repositório contém o **UFF-PV-Thermal Dataset**, um conjunto de dados robusto de imagens termográficas aéreas de módulos fotovoltaicos. O dataset foi construído com foco em alta confiabilidade, seguindo rigorosamente as diretrizes da norma **IEC TS 62446-3:2017** para garantir a qualidade e a relevância na análise termográfica quantitativa.

O objetivo principal deste dataset é auxiliar no desenvolvimento e treinamento de modelos de visão computacional e aprendizado de máquina voltados para a detecção automática de falhas em usinas solares.

---

## 📂 Estrutura do Dataset

O conjunto de dados está organizado em um formato amplamente compatível com frameworks de visão computacional (padrão PASCAL VOC), maximizando a acessibilidade:

```text
/UFF-PV-Thermal-Dataset/
|-- /images/               # Imagens visuais (JPG) correspondentes às análises térmicas
|-- /annotations/          # Anotações em formato XML (PASCAL VOC) contendo as bounding boxes
|-- dataset_readme.md      # Documentação do dataset (este arquivo)
|-- classes.txt            # Lista de todas as classes anotadas
