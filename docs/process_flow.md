# Fluxo de Processo

## Descrição Detalhada

- Forneça uma explicação detalhada de cada passo do processo automatizado (utilize imagens das telas da automação se julgar necessário).

## Diagrama de Fluxo

- Use diagramas visuais para representar graficamente o fluxo do processo. ou pode ser via PNG, JPG ou via Mermaid

### Exemplos de fluxos com Mermaid

Fluxo horizontal

```mermaid
graph TD
    A[Fluxo 1] --> B[Fluxo 2]
    B --> C[Fluxo 3]
    C --> A[Fluxo 1]
```

Fluxo Vertifical

```mermaid
graph LR
    A[Fluxo 1] --> B[Fluxo 2]
    B --> C[Fluxo 3]
    C --> A[Fluxo 1]
```

Fluxo Com validação

```mermaid
graph TD
    A[Fluxo 1] --> B[Fluxo 2]
    B -->|Sim| C[Fluxo 3]
    B -->|Não| D[Fluxo 4]
    C --> A[Fluxo 1]
```
