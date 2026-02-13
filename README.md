# Docily — Design System v1.0

## 1. Visão Geral

O Design System da Docily define os padrões visuais, tipográficos e estruturais da marca para garantir consistência, escalabilidade e eficiência no desenvolvimento de interfaces digitais.

### Objetivos

- Garantir coerência visual  
- Facilitar escalabilidade  
- Padronizar componentes  
- Reduzir retrabalho entre design e desenvolvimento  

---

## 2. Identidade Visual

### 2.1 Logotipo

A marca possui duas variações:

- Versão principal (símbolo + tipografia)
- Versão aplicada em fundo primário

#### Regras de uso

- Não distorcer proporções  
- Manter área mínima de respiro equivalente à altura do símbolo  
- Utilizar apenas cores oficiais do sistema  
- Não aplicar sombras, contornos ou efeitos não definidos  

---

## 3. Cores

### 3.1 Estrutura

As cores são organizadas por função semântica.

#### Primária

Uso:
- Cabeçalhos
- Botões principais
- Elementos de destaque
- Áreas de alto contraste

#### Secundária

Uso:
- Destaques suaves
- Elementos de apoio
- Componentes secundários

#### Fundo

Uso:
- Fundo principal de telas
- Áreas de leitura prolongada
- Containers amplos

---

### 3.2 Tokens de Cor (exemplo)

```css
:root {
  --color-primary: #XXXXXX;
  --color-secondary: #XXXXXX;
  --color-background: #XXXXXX;
  --color-text-primary: #XXXXXX;
  --color-text-on-primary: #XXXXXX;
}
