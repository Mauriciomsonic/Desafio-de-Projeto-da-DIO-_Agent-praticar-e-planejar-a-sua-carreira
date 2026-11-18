# DIO Agent na Prática

Desafio de Projeto da [DIO](https://dio.me): configure o [DIO Agent](https://github.com/digitalinnovationone/dio-agent) e use as skills dele para estudar, praticar e planejar a sua carreira.

## Como fazer

1. Clique em **Use this template** para criar a sua cópia deste repositório.
2. Siga os passos abaixo, copiando cada prompt para o DIO Agent.
3. Preencha a seção [Minha entrega](#minha-entrega) e entregue o link da sua cópia na DIO.

## 1. Configure o DIO Agent

- Instale um harness. Recomendamos o [Google Antigravity](https://antigravity.google/docs), mas qualquer um [da lista do DIO Agent](https://github.com/digitalinnovationone/dio-agent#-comece-em-3-passos) funciona.
- Baixe o [DIO Agent](https://github.com/digitalinnovationone/dio-agent) em **Code**, **Download ZIP**, e extraia.
- No harness, abra a pasta que tem o arquivo `AGENTS.md` e mande:

```
Oi!
Quem é você e como pode me ajudar nos meus estudos na DIO?
```

Se ele se apresentar como DIO Agent, está tudo certo.

## 2. Estudar

Troque o conceito pelo que você quer entender:

```
Me explica o que é uma skill de um agente de IA.
Meu nível: uso IA no dia a dia, mas nunca configurei um agente.
```

## 3. Praticar

Use um desafio em que você travou ou este exemplo:

```
Estou travado em um Desafio de Código da DIO.
O desafio pede a soma de todos os números de 1 até N.
Meu código imprime só o último número, não a soma:
let n = parseInt(gets());
let soma = 0;
for (let i = 1; i <= n; i++) {
  soma = i;
}
print(soma);
Me ajuda a destravar sem dar a resposta pronta.
```

## 4. Planejar

Preencha os colchetes com a sua Trilha:

```
Quero montar um plano de estudos.
Trilha: [link do seu Bootcamp ou Formação]
Objetivo: concluir em [4 semanas].
Meu nível: [iniciante, intermediário ou avançado].
Tempo: [1 hora por dia, de segunda a sexta].
```

## Bônus: seu próximo passo

Se você quer construir com IA:

```
Quero escolher meu próximo passo na Carreira AI Builder.
Quero construir: [um app para os pedidos do meu negócio].
Programação: [nenhuma, o básico ou trabalho com isso].
Objetivo: [tirar uma ideia do papel].
```

---

## Minha entrega

> **Aluno:** Mauricio (DIO Nível 23 | XP 55.000+)  
> **Repositório de Práticas:** [laboratoriomsonicA.I](https://github.com/Mauriciomsonic/laboratoriomsonicA.I)  
> **Harness Utilizado:** Google Antigravity  
> **Skill de Referência:** Rota de Carreira DIO (`AGENTS.md`)

---

### Configure

**Prompt enviado ao DIO Agent:**
```text
Oi!
Quem é você e como pode me ajudar nos meus estudos na DIO?
```

**Evidência da resposta do DIO Agent:**
> *"Olá, Mauricio! Eu sou o **DIO Agent**, seu copiloto de estudos e desenvolvimento profissional na DIO, operando aqui no harness **Google Antigravity** com a skill **Rota de Carreira DIO**.*
>
> *Estou configurado para apoiar sua jornada técnica em três frentes fundamentais:*
> 1. **Estudar:** Explicar conceitos e arquiteturas técnicas adaptados ao seu nível de proficiência.
> 2. **Praticar:** Orientar a resolução de desafios de código e arquitetura através do método socrático (com pistas e diagnósticos, sem entregar soluções prontas).
> 3. **Planejar:** Estruturar trilhas, cronogramas operacionais e preparação para o mercado (como na Carreira AI Builder e certificações de nuvem e IA), respeitando sua disponibilidade real de tempo.
>
> *Como posso impulsionar seu laboratório de IA e seus projetos hoje?"*

---

### Estudar

**Prompt enviado ao DIO Agent:**
```text
Me explica o que é uma skill e um harness no contexto de um agente de IA (DIO Agent).
Meu nível: uso IA no dia a dia, mas nunca configurei um agente.
```

**Evidência da resposta do DIO Agent:**
> *"Para compreender a arquitetura do DIO Agent, uma excelente analogia é pensar em um **piloto profissional de corrida**:*
>
> #### 1. O que é o Harness? *(O Cockpit e a Estrutura de Sustentação)*
> O **Harness** (como o Google Antigravity ou VS Code com extensões de agente) é a plataforma de execução que dá suporte ao agente:
> * Gerencia o ciclo de vida da conversa e o runtime.
> * Conecta o modelo de linguagem (LLM) aos arquivos do projeto (como `AGENTS.md` e `README.md`).
> * Controla o ambiente seguro (sandbox) para leitura, execução de ferramentas e comandos.
>
> #### 2. O que é uma Skill? *(O Treinamento Especializado e o Manual de Instruções)*
> Uma **Skill** é um conjunto modular de instruções, regras de governança e ferramentas acopladas que ensinam o agente a agir como especialista em determinado domínio:
> * Define o tom pedagógico (ensinar guiando em vez de apenas dar respostas).
> * Estabelece limites éticos e separação entre fatos documentados e suposições.
> * No DIO Agent, a skill **Rota de Carreira DIO** padroniza a mentoria de estudos, resolução de bloqueios práticos e planos de carreira.
>
> **Em resumo:** A LLM é o motor; o **Harness** é o chassi e o painel de instrumentos que permite interagir com o mundo; e a **Skill** é a especialização que orienta o agente a resolver problemas de forma confiável."*

---

### Praticar

**Prompt enviado ao DIO Agent:**
```javascript
Estou travado em um Desafio de Código da DIO.
O desafio pede a soma de todos os números de 1 até N.
Meu código imprime só o último número, não a soma:
let n = parseInt(gets());
let soma = 0;
for (let i = 1; i <= n; i++) {
  soma = i;
}
print(soma);
Me ajuda a destravar sem dar a resposta pronta.
```

**Evidência da resposta do DIO Agent:**
> *"Excelente iniciativa de depuração! Vamos analisar o comportamento do laço de repetição (`for`) passo a passo:
>
> 1. **Diagnóstico do Sintoma:** Na linha 44, você escreveu:
>    ```javascript
>    soma = i;
>    ```
> 2. **O que está acontecendo na memória:** A cada iteração da variável `i`, a atribuição simples `=` descarta o valor anterior de `soma` e o substitui pelo valor corrente de `i`. Por isso, ao término da execução quando $i = n$, a variável `soma` conterá unicamente o valor final $n$.
> 3. **Pista Orientadora:** Para calcular um total acumulado, o novo valor de `soma` deve ser o valor que ela **já possuía** adicionado ao valor atual de `i`.
>    * 👉 *Dica:* Como você pode usar o operador de adição com atribuição (`+=`) ou expressar `soma = soma + i;`?
>
> *(Nota técnica de engenharia: Após validar seu laço $O(N)$, experimente pesquisar sobre a fórmula da progressão aritmética de Gauss $\frac{n \times (n + 1)}{2}$, que resolve essa soma em tempo constante $O(1)$!)*"*

---

### Planejar

**Prompt enviado ao DIO Agent:**
```text
Quero montar um plano de estudos.
Trilha: Formação Inteligência Artificial na Prática & Laboratório de IA (https://github.com/Mauriciomsonic/laboratoriomsonicA.I)
Objetivo: consolidar a Carreira AI Builder (Engenharia de Agentes, LLMOps e Integração Multi-Cloud) em 4 semanas.
Meu nível: intermediário/avançado (experiência prática em Python, GCP, Azure OpenAI, Amazon Bedrock, N8N e CrewAI).
Tempo: 1 hora por dia, de segunda a sexta (5 horas semanais / 20 horas totais).
```

**Evidência da resposta do DIO Agent:**
> *"Excelente, Mauricio! Com base na sua base em Python, Nuvem (GCP, Azure, AWS) e automação de IA, aqui está o seu **Cronograma Operacional Semanal** focado na evolução prática do seu repositório `laboratoriomsonicA.I`:*
>
> | Semana | Foco Temático | Atividades Práticas (1h/dia - Seg a Sex) | Marco de Entrega |
> | :---: | :--- | :--- | :--- |
> | **Semana 1** | **Arquitetura de Agentes & Harnesses** | • Seg/Ter: Configuração avançada de harnesses (Google Antigravity, MCP, Tool Calling).<br>• Qua/Qui: Criação de especificações formais de Skills (`AGENTS.md`) e governança de contexto.<br>• Sex: Validação de instruções contra alucinações. | `AGENTS.md` modular documentado no laboratório. |
> | **Semana 2** | **Conexão Multi-Cloud de LLMs** | • Seg/Ter: Integração de modelos no Azure OpenAI e Azure AI Foundry.<br>• Qua/Qui: Configuração e teste de modelos via Amazon Bedrock em Python.<br>• Sex: Padronização de saídas com JSON Schema / TypeSafe outputs. | Módulo Python de roteamento inteligente de LLMs. |
> | **Semana 3** | **Orquestração Multi-Agente & Automação** | • Seg/Ter: Integração de fluxos complexos com N8N.<br>• Qua/Qui: Criação de squads de agentes com CrewAI para análise e processamento de dados.<br>• Sex: Testes de ponta a ponta no repositório. | Pipeline funcional integrando N8N + CrewAI. |
> | **Semana 4** | **LLMOps, CI/CD e Governança** | • Seg/Ter: Automação de testes de regressão de prompts com GitHub Actions.<br>• Qua/Qui: Estruturação do README executivo e arquitetura do `laboratoriomsonicA.I`.<br>• Sex: Retrospectiva e planejamento de certificações Cloud/AI. | Laboratório público documentado e portfólio atualizado. |
>
> *Critério de Revisão:* As sextas-feiras são destinadas a avaliar o avanço real e replanejar a carga da semana seguinte caso surjam impedimentos.*"

---

### Bônus: Seu Próximo Passo (AI Builder)

**Prompt enviado ao DIO Agent:**
```text
Quero escolher meu próximo passo na Carreira AI Builder.
Quero construir: um orquestrador multi-agente inteligente para triagem de dados e geração de insights no laboratoriomsonicA.I.
Programação: trabalho com isso / nível avançado em Python, Cloud e IA.
Objetivo: consolidar portfólio prático de alto impacto em IA Generativa para o mercado.
```

**Evidência da resposta do DIO Agent:**
> *"Para consolidar seu perfil como **AI Builder** de alto nível, sua próxima meta deve ser a transição de scripts isolados para um **Ecossistema de IA Orientado a Eventos**:
>
> 1. **Camada de Orquestração:** Utilize o CrewAI integrado ao N8N para receber gatilhos externos (webhooks, commits ou mensagens).
> 2. **Camada de Execução Multi-Cloud:** Deixe o agente decidir a melhor rota: tarefas de raciocínio lógico enviadas para modelos no Azure OpenAI e tarefas de síntese/análise de custo reduzido roteadas via Amazon Bedrock.
> 3. **Governança de Skills:** Aplique o padrão de `AGENTS.md` testado neste projeto para garantir que cada sub-agente tenha papéis e limites estritos.
> 4. **Divulgação Técnica:** Publique um artigo na DIO e no LinkedIn demonstrando a arquitetura do [laboratoriomsonicA.I](https://github.com/Mauriciomsonic/laboratoriomsonicA.I), destacando métricas de latência, governança e custos."*

---

### Como foi para você

_Usar o DIO Agent integrado a um harness avançado como o Google Antigravity proporcionou uma experiência muito superior à de um simples chatbot conversacional. A separação clara entre o **Harness** (o ambiente com acesso a arquivos e ferramentas) e as **Skills** (as diretrizes de comportamento do `AGENTS.md`) permitiu interações precisas, que respeitaram o meu nível real de conhecimento em IA e Cloud sem simplificações desnecessárias._

_O método de mentoria socrática na etapa de prática reforça o aprendizado ao instigar a resolução do problema pela raiz, enquanto o planejamento estruturado permitiu conectar diretamente a Formação da DIO com o desenvolvimento ativo do meu repositório de experimentos ([laboratoriomsonicA.I](https://github.com/Mauriciomsonic/laboratoriomsonicA.I)). O projeto demonstrou na prática como a IA generativa, quando governada por diretrizes de engenharia e contextos bem definidos, se torna uma ferramenta indispensável para o desenvolvimento profissional de ponta a ponta._

