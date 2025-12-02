![Banner da Em Vidros](./banner.png)

# EM Hub

Bem-vindo ao **EM Hub**, o núcleo de inteligência de dados e estratégia da **EM Vidros**.

Este repositório centraliza a documentação técnica, a arquitetura de dados e os códigos responsáveis por transformar nossa operação industrial em uma cultura *data-driven*.

## 🏭 Sobre a EM Vidros

A EM Vidros é referência no beneficiamento e têmpera de vidros, com uma operação robusta e capilaridade logística que atende todo o norte/nordeste. Nossa estrutura é dividida estrategicamente:

* **Matriz (Raposa - MA):** Foco em produção industrial de alta escala e logística.
* **Filial (Imperatriz - MA):** Hub estratégico para atendimento regional.

Apesar do sucesso operacional, o alto volume de dados gerado por essas unidades encontra-se disperso. O desafio atual é conectar essas pontas para garantir que a diretoria tenha uma visão única e padronizada de custos, eficiência e vendas em toda a rede.

## 🎯 O Que Queremos Resolver?

O **EM Hub** nasce para resolver a interseção entre ferramentas inadequadas e a necessidade de decisões rápidas. Nosso objetivo principal é eliminar a dependência de conhecimento onde apenas especialistas no ERP sabem extrair a informação correta.

Atuamos em três pilares estratégicos:

1.  **Padronização Semântica:** Definir oficialmente o que é *Lucro*, *Custo*, *Eficiência* e *Perda* para a empresa, evitando ambiguidades entre departamentos.
2.  **Monitoramento Contínuo:** Substituir relatórios estáticos e manuais por indicadores automáticos que mostram a saúde da produção por máquina e turno.
3.  **Inteligência Preditiva:** Evoluir para análises que antecipam demandas e identificam riscos operacionais antes que eles aconteçam.

## 🚀 Como vamos colocar em prática?

Para garantir entrega de valor imediato sem comprometer a governança futura, dividimos a execução em duas fases:

### Fase 1: Homologação (O "Agora")
*Foco: Velocidade e Validação.*
Criamos um ambiente leve para validar as regras de negócio junto à diretoria. O objetivo é garantir que os números estejam certos antes de automatizar.
* **Ação:** Scripts Python extraem dados e geram visualizações no **Notion**.
* **Entrega:** Portais de indicadores validados para a Diretoria e Produção.

### Fase 2: Produção (O "Futuro")
*Foco: Escala e Governança.*
Com as métricas validadas, migramos para uma infraestrutura robusta de Engenharia de Dados.
* **Ação:** Implementação de Data Warehouse (BigQuery) e orquestradores (Airflow/Estuary).
* **Entrega:** Dashboards oficiais no Power BI, governança com dbt e APIs de predição.

> **Fluxo de Dados Final:**
> ERP Pegasus → Estuary → Google Cloud Storage → BigQuery → dbt → Power BI.

## 📞 Contato e Localização

A sede da EM Vidros fica na **Rua do Campo, 100 - Inhaúma, Raposa - MA**.

* **Dúvidas de Dados:** Abra uma *Issue* neste repositório.
* **Comercial/Geral:** `contato@emvidros.com.br` ou `(98) 3131-4000`.
* **Site:** [emvidros.com.br](http://www.emvidros.com.br)