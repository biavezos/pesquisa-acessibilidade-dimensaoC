# pesquisa-acessibilidade-dimensaoC 📊 Acessibilidade Digital e Inclusão — Dimensão C (DAD)

## 🧠 Sobre essa pesquisa
Esta pesquisa analisa a inclusão de pessoas com deficiência (PCDs) no Brasil, com foco em acessibilidade digital, legislação vigente e desafios na aplicação prática das normas.

Mesmo com avanços legais como a Lei Brasileira de Inclusão, ainda existem barreiras significativas no acesso a serviços, mercado de trabalho e ambientes digitais. O estudo também compara diretrizes internacionais e apresenta dados atualizados sobre violações de direitos e falta de acessibilidade.

---

## 🔍 O que descobrimos (Principais Achados)

- O Brasil possui cerca de **14,4 milhões de pessoas com deficiência (7,3% da população)**
- Em 2025, o **Disque 100 registrou mais de 617 mil denúncias** e 4,4 milhões de violações de direitos humanos
- **82,4% das empresas paulistas descumpriram a Lei de Cotas (2019)**
- Processos por **acessibilidade digital nos EUA cresceram**, com mais de 4.600 casos em 2023
- Problemas mais comuns em sistemas digitais:
  - Falta de texto alternativo
  - Baixo contraste
  - Incompatibilidade com leitores de tela

---

## 🛠️ Ferramentas / Casos / Legislação

### 📜 Principais Leis e Normas

| Norma / Lei | Descrição |
|------------|----------|
| Lei 13.146/2015 (LBI) | Garante direitos e acessibilidade para PCDs |
| ADA (EUA) | Lei internacional contra discriminação |
| e-MAG | Modelo brasileiro de acessibilidade digital |
| WCAG (W3C) | Diretrizes internacionais de acessibilidade |
| ABNT NBR 17225 (2025) | Norma brasileira para acessibilidade web |

---

### 🧩 Comparativo (Brasil x Internacional)

| Aspecto | Brasil (LBI + e-MAG) | EUA (ADA) |
|--------|---------------------|-----------|
| Acessibilidade digital | Obrigatória no setor público | Forte judicialização |
| Fiscalização | Limitada | Mais ativa |
| Aplicação prática | Baixa | Média/Alta |

---

## 💻 Como isso afeta o nosso trabalho como desenvolvedores

Depois dessa pesquisa, algumas práticas passam a ser **obrigatórias (e estratégicas)** no desenvolvimento:

### 1. Usar HTML semântico + acessível
```html
<img src="produto.jpg" alt="Tênis esportivo preto com detalhes brancos"> 

### 2. Garantir navegação por teclado
```html
<button tabindex="0">Comprar</button> 

### 3. Aplicar contraste e acessibilidade visual (CSS)
body {
  background-color: #ffffff;
  color: #000000;
  font-size: 16px;
} 

---

# 📚 Referências

- Brasil. Lei Brasileira de Inclusão (Lei 13.146). 2015.  
- IBGE. Dados sobre pessoas com deficiência no Brasil. 2023.  
- Ministério dos Direitos Humanos. Relatório Disque 100. 2025.  
- W3C. Web Content Accessibility Guidelines (WCAG). 2018.  
- Governo Federal. e-MAG — Modelo de Acessibilidade em Governo Eletrônico.  
- ABNT. NBR 17225 — Acessibilidade Web. 2025.  
- United States. Americans with Disabilities Act (ADA). 1990.  