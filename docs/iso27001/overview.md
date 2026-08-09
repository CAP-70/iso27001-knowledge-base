# ISO/IEC 27001:2022 — Visão Geral

A norma tem duas partes. As cláusulas 4 a 10 trazem os requisitos obrigatórios. O Anexo A traz 93 controles de referência.

A diferença entre as duas partes decide o custo do seu projeto.

Você precisa atender todas as cláusulas de 4 a 10. Você **não** precisa implementar todos os 93 controles do Anexo A. Você seleciona os controles que tratam os riscos inaceitáveis.

!!! warning "O erro que mais encarece projetos"
    Muita empresa implementa os 93 controles porque acredita que a norma exige todos.

    A cláusula 6.1.3 diz o contrário. [Veja o erro 02 na lista dos oito erros](oito-erros.md).

---

## O mapa das sete cláusulas

| Cláusula | O que ela exige | Entrega principal |
|---|---|---|
| **4** Contexto | Entender onde a organização opera e definir o que o SGSI protege | Análise de contexto, mapa de partes interessadas, declaração de escopo |
| **5** Liderança | Comprometimento formal da alta direção | Política de Segurança da Informação, papéis e responsabilidades |
| **6** Planejamento | Estabelecer o processo de risco e os objetivos | Critérios de aceitação, avaliação de riscos, Plano de Tratamento, Declaração de Aplicabilidade |
| **7** Apoio | Garantir recursos, pessoas e documentos | Matriz de competência, programa de conscientização, plano de comunicação, controle de documentos |
| **8** Operação | Executar o que foi planejado | Registros de operação, reavaliação de riscos, gestão de mudanças |
| **9** Avaliação | Medir se o SGSI funciona | Indicadores, auditoria interna, análise crítica pela direção |
| **10** Melhoria | Corrigir as falhas e evoluir | Registro de não conformidades, ações corretivas, log de melhorias |

---

## Cláusula 4 — Contexto da Organização

A cláusula 4 tem quatro subitens. Ela pede que você entenda o ambiente antes de construir qualquer coisa.

- **4.1** — as questões internas e externas que afetam o SGSI.
- **4.2** — as partes interessadas e os requisitos de cada uma.
- **4.3** — o escopo do SGSI, documentado.
- **4.4** — o SGSI estabelecido, implementado e mantido.

!!! info "O que o auditor pede"
    A norma não prescreve método. Ela exige resultado.

    PESTEL, SWOT e CANVAS são ferramentas, não requisitos. O auditor pede a análise documentada, aprovada pela direção e revisada com regularidade.

!!! success "Recomendação"
    Comece com um escopo menor e bem controlado.

    Um SGSI eficaz cobrindo 60% dos processos vale mais que um SGSI frágil cobrindo 100%. Você amplia o escopo nos ciclos anuais de manutenção.

---

## Cláusula 5 — Liderança

A cláusula 5 tem três subitens que formam uma cadeia. Sem o primeiro, os outros dois não sustentam.

- **5.1** — liderança e comprometimento da alta direção.
- **5.2** — a Política de Segurança da Informação.
- **5.3** — papéis, responsabilidades e autoridades.

!!! info "O que o auditor pede"
    Portaria interna, ata de reunião ou ordem de serviço assinada pela direção.

    A descrição das atribuições e da autoridade do ponto focal.

    A evidência de que o ponto focal reporta direto à alta direção.

!!! warning "O erro mais comum"
    A empresa copia uma Política genérica da internet.

    A Política precisa espelhar a identidade da organização: a missão, os valores e os objetivos reais de segurança. Uma cópia genérica não sobrevive à primeira pergunta do auditor sobre como ela foi elaborada.

---

## Cláusula 6 — Planejamento

Esta é a cláusula que define o custo de todo o projeto. Ela concentra o processo de risco.

- **6.1.2** — o processo de avaliação de riscos.
- **6.1.3** — o tratamento dos riscos e a Declaração de Aplicabilidade.
- **6.2** — os objetivos de segurança da informação.
- **6.3** — o planejamento de mudanças.

O processo de avaliação precisa cumprir quatro tarefas:

1. Estabelecer os critérios de aceitação de risco.
2. Identificar os riscos de perda de confidencialidade, integridade e disponibilidade.
3. Analisar a probabilidade e o impacto de cada risco.
4. Priorizar os riscos para tratamento.

!!! info "O que o auditor pede"
    Os critérios de aceitação de risco aprovados pela direção.

    O Plano de Tratamento de Riscos com proprietário definido para cada risco.

    A assinatura do proprietário nos riscos aceitos formalmente.

    A Declaração de Aplicabilidade com justificativa para cada inclusão e cada exclusão.

---

## Cláusula 7 — Apoio

Um bom plano de riscos não funciona sem recursos, pessoas capacitadas e comunicação.

- **7.1** — recursos.
- **7.2** — competência.
- **7.3** — conscientização.
- **7.4** — comunicação.
- **7.5** — informação documentada.

!!! info "O que o auditor pede"
    A evidência documentada de competência: educação, treinamento ou experiência de cada pessoa que afeta o SGSI.

    A evidência de que as pessoas conhecem a Política e as consequências do descumprimento.

    O plano de comunicação: o que comunicar, quando, para quem e por qual meio.

!!! warning "O ponto cego mais frequente"
    A cláusula 7.4 alcança também os terceiros.

    Fornecedores, prestadores e parceiros precisam conhecer as suas obrigações de segurança. Um parceiro que não conhece essas obrigações vira porta de entrada de incidente.

---

## Cláusula 8 — Operação

A cláusula 8 transforma o plano em ação.

- **8.1** — planejamento e controle operacional.
- **8.2** — avaliação de riscos em intervalos planejados e a cada mudança significativa.
- **8.3** — tratamento de riscos e o plano em execução.

!!! success "Crie um gatilho formal de reavaliação"
    Toda mudança significativa aciona uma reavaliação de risco. Um sistema novo. Uma mudança regulatória. Um fornecedor novo.

    Não espere o ciclo anual. Documente cada reavaliação e as conclusões dela.

    [O erro 08 mostra o que acontece quando esse gatilho não existe](oito-erros.md).

---

## Cláusula 9 — Avaliação de Desempenho

Três atividades diferentes, com frequências diferentes. Muita gente confunde as três.

| Subitem | O que é | Frequência mínima |
|---|---|---|
| **9.1** Monitoramento | Indicadores medidos pelos responsáveis operacionais | Mensal |
| **9.2** Auditoria interna | Verificação independente de conformidade e eficácia | Anual |
| **9.3** Análise crítica pela direção | Decisões estratégicas da liderança sobre o SGSI | Anual |

As três se conectam. O monitoramento alimenta a auditoria interna com dados. A auditoria e os indicadores alimentam a análise crítica. As decisões da direção geram as ações de melhoria da cláusula 10.

!!! success "Comece com poucos indicadores"
    Selecione de dois a quatro indicadores que reflitam os principais riscos.

    Para cada um, defina a meta, o método de coleta, a frequência e o responsável.

    Não tente medir tudo. Priorize os indicadores que influenciam decisões.

!!! info "Sobre a imparcialidade na 9.2"
    A norma não exige um departamento de auditoria interna. Ela exige objetividade.

    [O erro 06 explica as três formas aceitas de resolver isso](oito-erros.md).

---

## Cláusula 10 — Melhoria

A melhoria contínua não é uma declaração genérica. A norma exige que ela seja sistemática e alimentada por resultados.

- **10.1** — melhoria contínua.
- **10.2** — não conformidades e ação corretiva.

As entradas do processo de melhoria vêm das cláusulas anteriores: os indicadores fora da meta (9.1), as não conformidades de auditoria (9.2), as decisões da direção (9.3) e as lições dos incidentes.

!!! success "Método para a causa raiz"
    Aplique os cinco porquês em cada não conformidade.

    Exemplo: o indicador de phishing está alto. Por quê? Os colaboradores não reconhecem e-mails suspeitos. Por quê? O último treinamento foi há 18 meses. Por quê? Não existe calendário anual definido.

    Causa raiz: ausência de programa de conscientização estruturado.

!!! warning "Encerre pela eficácia, não pela execução"
    Só encerre uma ação corretiva depois de confirmar três coisas: o problema foi resolvido, a causa raiz foi eliminada e o indicador associado melhorou.

    Ação executada não é ação eficaz.

---

## O ciclo completo

As sete cláusulas formam um ciclo PDCA. Elas não são etapas isoladas.

| Fase | Cláusulas | O que acontece |
|---|---|---|
| Planejar | 4, 5, 6 | Você entende o contexto, obtém o comprometimento e planeja o tratamento de risco |
| Fazer | 7, 8 | Você garante os recursos e opera os controles |
| Checar | 9 | Você mede, audita e analisa |
| Agir | 10 | Você corrige, melhora e volta ao início |

O SGSI que para no "Fazer" é o SGSI que passa no Estágio 2 e reprova na manutenção.

---

## Quer o passo a passo completo?

Este panorama mostra o mapa. Ele não mostra o caminho.

Eu escrevi uma **Cartilha de Implementação da ISO 27001:2022** em nove fascículos. Ela cobre cada cláusula com passo a passo e modelos de documento. Cada fascículo traz um checklist de conclusão e a lista de evidências que o auditor solicita.

A Cartilha é gratuita. Peça pela página de Contato e eu envio por e-mail.

[Pedir a Cartilha completa](../contato.md){ .md-button .md-button--primary }
