# Projeto DJI geoAG — Fase 1: Coleta e Cruzamento de Imagens por PN

Base estruturada de imagens, fotografias e diagramas para os **1.623 Part Numbers (PNs)** de drones agrícolas DJI (modelos T10, T25, T25P, T30, T40, T50, T55, T70P, T100 e outros) da lista geoAG.

---

## 📊 Estatísticas Consolidadas de Cobertura

| Métrica | Quantidade | Percentual | Observações |
| :--- | :---: | :---: | :--- |
| **Total de PNs da Lista geoAG** | **1.623** | **100,00%** | Ordem original 1-para-1 estritamente preservada |
| **Correspondência Exata Comprovada** | **1.281** | **78,93%** | PN DJI oficial idêntico incluindo sufixo de revisão (`.01`, `.02`, etc.) |
| **Foto Candidata por Descrição / Modelo** | **141** | **8,69%** | Modelo e descrição compatíveis ou PN base idêntico sem revisão comprovada |
| **Diagrama de Conjunto Relacionado** | **7** | **0,43%** | Exploded views / esquemáticos de montagem (todos possuem foto associada) |
| **Sem Nenhuma Imagem** | **201** | **12,38%** | Itens que não retornaram imagens nas fontes confiáveis consultadas |
| **Cobertura Geral com Imagens** | **1.422** | **87,62%** | **1.422 dos 1.623 PNs possuem fotos reais validadas** |

- **Total de registros detalhados de candidatas:** 4.329 linhas
- **Novas imagens identificadas nesta rodada:** +1.597 candidatas
- **URLs ativas validadas com HTTP 200:** 1.768 URLs de imagem distintas

---

## 📁 Arquivos Disponíveis

1. **`geoAG_Fase1_Resultados.zip`** (357 KB)  
   Pacote compactado contendo as duas planilhas completas e documentação de apoio.
2. **`geoAG_1623_PNs_cruzamento_master.csv`** (1,3 MB)  
   Planilha Master com exatamente 1.623 linhas de dados na ordem original do arquivo de entrada. Cada linha traz a melhor imagem selecionada, grau de confiança, status de conferência e fonte.
3. **`geoAG_1623_PNs_todas_candidatas.csv`** (2,2 MB)  
   Planilha analítica detalhada com todas as 4.329 imagens candidatas encontradas, permitindo inspecionar variações de ângulo, embalagem e fotos de peças alternativas.
4. **`LEIAME_RESULTADOS.txt`**  
   Dicionário de colunas e regras de classificação adotadas na Fase 1.

---

## 🛡️ Critérios Rigorosos de Validação Adotados

1. **Correspondência Exata (Tier 1):**  
   Exige que o PN encontrado na fonte oficial/distribuidor seja idêntico ao PN do geoAG, incluindo a revisão completa (ex: `000305.01`, `004655.02`). Se a fonte possuía apenas o código base sem sufixo, o item foi reclassificado para Candidata (Tier 2).
2. **Separação de SKUs Comerciais:**  
   SKUs de varejistas (ex: `DJIAGT50-R08`, `AUSPOST...`) foram desconsiderados como PN DJI oficial.
3. **Fotos Limpas e Verificadas:**  
   Purga de placeholders genéricos (ex: `woocommerce-placeholder-600x600.webp`) e de carrosséis de produtos relacionados em páginas sem foto própria.
