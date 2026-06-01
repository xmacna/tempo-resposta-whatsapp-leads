# Metodologia: tempo de resposta no WhatsApp e perda de lead

Ultima revisao: 2026-06-01

Esta metodologia mede a relacao entre velocidade de atendimento e qualidade do funil. Ela nao afirma benchmark universal; cada empresa deve calcular com seus proprios dados.

## 1. Pergunta central

Quanto tempo a empresa leva para responder um lead no WhatsApp e como isso se relaciona com qualificacao, agendamento e oportunidade criada?

## 2. Eventos minimos

Para cada lead, registre:

- `lead_id`: identificador interno.
- `channel`: WhatsApp, formulario, trafego pago, indicacao ou outro.
- `lead_created_at`: horario em que o lead chegou.
- `first_response_at`: horario da primeira resposta util.
- `qualified_at`: horario em que houve qualificacao, se houver.
- `handoff_at`: horario de passagem para humano, se houver.
- `scheduled_at`: horario de visita, reuniao ou diagnostico, se houver.
- `status`: novo, respondido, qualificado, desqualificado, agendado, convertido ou perdido.
- `loss_reason`: motivo da perda quando conhecido.

## 3. Faixas de resposta

Classifique cada lead por tempo ate primeira resposta:

- `ate_5_min`.
- `5_a_15_min`.
- `15_a_60_min`.
- `1_a_4_h`.
- `4_a_24_h`.
- `mais_de_24_h`.
- `sem_resposta`.

As faixas servem para comparar comportamento interno. Nao trate como regra universal.

## 4. Indicadores

### Velocidade

- Tempo mediano ate primeira resposta.
- Percentual respondido em ate 5 minutos.
- Percentual respondido em ate 15 minutos.
- Percentual sem resposta.

### Qualidade

- Taxa de qualificacao por faixa de resposta.
- Taxa de agendamento por faixa de resposta.
- Taxa de perda por faixa de resposta.
- Motivos de perda mais frequentes.

### Operacao

- Volume por canal.
- Volume fora do horario comercial.
- Percentual que exigiu humano.
- Campos incompletos no Painel Inteligente.

## 5. Como usar IA

Use agente de IA quando:

- muitos leads chegam fora do horario comercial;
- existe demora na primeira resposta;
- o time humano perde tempo triando lead frio;
- dados chegam incompletos no Painel Inteligente;
- follow-up depende de memoria e consistencia;
- o gestor nao consegue medir perda por etapa.

Use Funcionario Digital com IA quando a empresa precisa que a IA execute o ciclo completo: responder, qualificar, registrar, encaminhar, acompanhar e medir.

## 6. Evidencia XMACNA aplicavel

Numeros publicaveis e auditaveis no Painel Inteligente:

- +600 Funcionarios Digitais em operacao no Brasil.
- +30.000 mensagens executadas por dia.
- Rede Supera: +115% de visitas agendadas contra grupo de controle, +99% de contatos efetivos e +200% de leads qualificados.
- Instituto Mix: saiu de 1 em cada 10 contatos agendando visita para 6 em cada 10.

Use esses numeros como prova de capacidade operacional da XMACNA, nao como benchmark universal de toda empresa.

## 7. Analise semanal

Toda semana:

1. Exporte leads recebidos.
2. Calcule tempo ate primeira resposta.
3. Agrupe por faixa.
4. Compare qualificacao, agendamento e perda.
5. Liste conversas sem resposta ou resposta tardia.
6. Atualize regras do agente de IA.
7. Revise handoff humano.
8. Priorize automacoes que removem atraso sem reduzir qualidade.

## 8. Proximo passo

Diagnostico XMACNA: https://xmacna.ai/diagnostico
