#  Projeto de gerador de currículos com Lovable

PRD refinado no Copilot Web

```
# ATS Resume Matcher MVP

## Contexto
Aplicação que compara currículos com descrições de vagas e gera versões otimizadas para ATS.  
Público-alvo: candidatos a vagas de tecnologia e primeiro emprego.  
Objetivo: aumentar a compatibilidade entre currículo e vaga, com exportação em PDF/DOCX e acompanhamento da evolução.

---

## Telas

### Tela de Upload
- Upload de currículo (.pdf, .docx)
- Campo para descrição da vaga (texto ou upload)
- Botão primário "Iniciar análise"

### Tela de Análise
- Gráfico de compatibilidade (% match)
- Lista de palavras-chave encontradas e ausentes
- Feedback visual com ícones ✔️ / ⚠️
- Botão "Gerar sugestões ATS"

### Tela de Sugestões
- Lista de ajustes recomendados (formato, linguagem, keywords)
- Botão "Aplicar ajustes"
- Opção de especialização:  
  - Nicho tecnologia  
  - Nicho primeiro emprego  

### Tela Final
- Currículo revisado
- Botões "Exportar PDF" e "Exportar DOCX"
- Mensagem de confirmação

### Dashboard
- Histórico de versões do currículo
- Gráfico de evolução do match ao longo das edições
- Filtro por nicho (tecnologia, primeiro emprego)
- Cards com métricas:  
  - Último match (%)  
  - Melhor versão (%)  
  - Palavras-chave adicionadas  

---

## Fluxo da Análise
1. Upload de currículo e vaga
2. Parsing: extrair dados estruturados (skills, experiências, keywords)
3. Matching: comparar requisitos da vaga com currículo
4. Sugestões ATS: ajustes de formato e linguagem
5. Exportação: PDF e DOCX
6. Dashboard: acompanhar evolução
7. Especialização: adaptar saída para nichos
8. SEO/GEO: otimizar para buscas e discovery em IA

---

## Design System (shadcn/ui preset)
- Tipografia: `Inter`, clara e legível
- Paleta de cores: neutra + azul/verde para feedback positivo
- Componentes:
  - `Button` primário para ações
  - `Card` para análise e sugestões
  - `Progress` e `Chart` para compatibilidade
- Feedback visual: ícones de sucesso/alerta
- Layout: grid responsivo, sidebar para dashboard

---

## SEO/GEO Strategy

### SEO
- Title: "ATS Resume Matcher - Compare Currículo com Vaga"
- Meta description: "Ferramenta que analisa currículos e gera versões otimizadas para ATS."
- Keywords: currículo ATS, análise de vaga, dashboard carreira
- Páginas estáticas (SSG):  
  - `/curriculo-tecnologia`  
  - `/curriculo-primeiro-emprego`

### GEO
- Location: São Paulo, Brasil
- Language: pt-BR, en-US
- Schema.org: LocalBusiness + SoftwareApplication
- Landing pages nichadas:  
  - "Currículo ATS para desenvolvedores"  
  - "Currículo ATS para primeiro emprego"

---

## MVP Features
- Upload de currículo (.pdf, .docx)
- Upload/colagem da vaga
- Análise de compatibilidade (% match)
- Sugestões ATS
- Exportação em PDF e DOCX
- Dashboard com evolução do match
- Especialização por nicho
- SEO/GEO otimizado para discovery

```






<img width="1338" height="627" alt="image" src="https://github.com/user-attachments/assets/ae4bd4a1-5227-46d0-9653-b4b3c68cb489" />

<img width="1342" height="636" alt="image" src="https://github.com/user-attachments/assets/6b50cc69-e6ec-4c7f-b85d-cb27f0e25a87" />



<img width="914" height="588" alt="image" src="https://github.com/user-attachments/assets/f20b4b63-a657-4844-bc65-d05492d67db2" />

<img width="912" height="560" alt="image" src="https://github.com/user-attachments/assets/1a8029e2-eee4-409b-98f6-f5d442acfcce" />



link 
https://app-resume-matcher.lovable.app



