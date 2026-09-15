# 🏋️‍♂️ MyWorkout – SaaS de Gestão de Performance e Treinos

> Aplicação web profissional desenvolvida para o acompanhamento e gestão avançada de treinos diários, unindo alta performance, design mobile-first e engenharia de software eficiente.

---

## 💡 Sobre o Projeto
O **MyWorkout** nasceu para resolver a complexidade do acompanhamento de treinos de musculação e cardio de forma inteligente. Focada em performance e estabilidade, a plataforma oferece uma interface limpa e um conjunto de ferramentas robustas para registrar cargas, analisar o histórico de performance e visualizar execuções de exercícios com uma arquitetura inovadora.

---

## 🛠️ Stack Tecnológica
* **Front-end:** React.js, Tailwind CSS, Arquitetura PWA
* **Back-end & Banco de Dados:** Supabase, PostgreSQL
* **Fontes de Dados & CDN:** Integração com APIs externas via GitHub Raw / jsDelivr

---

## ✨ Principais Funcionalidades & Engenharia

### 1. Gestão Completa de Treino
* **Registro Inteligente:** Acompanhamento dinâmico de carga (kg) e repetições para musculação, além de tempo (min) e distância (km) para cardio, com identificação automática via Regex.
* **Histórico de Performance:** Sistema inteligente que recupera automaticamente a última marca do usuário para o exercício atual com base no histórico de treinos.
* **Ferramentas de Foco:** Cronômetro flutuante integrado com atalhos rápidos (1:00, 1:30, 2:00) e sistema de anotações por exercício.

### 2. Motor Visual 3D (Anti-Bloqueio)
* **Engenharia sem GIFs Pesados:** Para contornar problemas de peso de arquivos e bloqueios de *Hotlink Protection* (Erro 403) de APIs externas, o app renderiza duas imagens estáticas (`0.jpg` e `1.jpg`) direto via CDN.
* **CSS Crossfade Engine:** Motor construído no React que intercala a opacidade das imagens a cada 1200ms, gerando uma ilusão de movimento 3D fluida e leve.
* **Fallback Corporativo:** Tratamento rigoroso de erros de imagem exibindo uma interface de "Execução Indisponível" elegante.

### 3. Algoritmo de Busca Cirúrgica (2 Camadas)
* **Cruzamento de Idiomas (PT-BR / EN):** Sistema robusto para buscar exercícios no banco de dados de forma precisa.
* **Camada 1 & 2:** Tenta o *match* exato e aplica regras estritas de palavras-chave para evitar falsos positivos (garantindo precisão absoluta nos resultados).

---

## 📸 Demonstração Visual
*(Insira aqui os prints das telas principais do seu app: Dashboard de Treino, Histórico e Visualizador 3D)*

| Dashboard / Registro de Séries |
| :---: | :---: |
| ![Dashboard](<img width="359" height="770" alt="{B6E3AB6D-6527-4AA2-9D80-D548829A7176}" src="https://github.com/user-attachments/assets/f39ce29d-21cf-4cf0-b6fe-cabf3bb6d525" />
) | ![Registro de Séries](<img width="370" height="757" alt="{726C56C2-B378-470C-869F-0AF6285187C1}" src="https://github.com/user-attachments/assets/81b2be18-2c94-47c0-adac-6ef84e8467ad" />
) |

---

## 🌐 Acesse a Aplicação em Produção
O código-fonte principal deste repositório é protegido por propriedade intelectual (SaaS Core), mas você pode testar a aplicação rodando ao vivo no link abaixo:

🔗 **[Acessar o MyWorkout Online](https://yp-myworkout.vercel.app/)**

---

## 👨‍💻 Desenvolvido por
**Ygor Vieira Pontes** *Desenvolvedor Full-Stack & AI-Driven Builder* [LinkedIn](https://www.linkedin.com/in/ygor-vieira-pontes-87a33023a) | [GitHub](https://github.com/ygorvpontes)
