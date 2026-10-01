# Horizonte Consumidor - caso fictício 2 (chaleira elétrica)
Atividade preparatória para a N1 da disciplina Inteligência Artificial Jurídica (Prof. Edson
Vaz Lopes).
## Problema
Chaleira elétrica cuja tampa abriu durante o uso e causou lesão na consumidora. Ela pede uma
orientação inicial sobre quem responde pelo acidente, o que pode pedir e qual o prazo.
## Como navegar
- entrada/ preserva o relato original (nunca vai para a IA);
- apoio/ contém o caso sanitizado e as únicas fontes permitidas na consulta;
- docs/ define as regras, a especificação e os prompts;
- evidencias/ registra a resposta da IA, a verificação, a auditoria e a revisão humana;
- entrega/ contém a orientação final.
## Ordem do fluxo
1. docs/limites_e_sigilo.md
2. apoio/caso_sanitizado.md, apoio/fonte_1.md (nota fiscal e manual), apoio/fonte_2.md (CDC,
arts. 12, 13 e 27)
3. docs/especificacao.md
4. docs/prompts/consulta_rag.md → evidencias/resposta_inicial.md
5. evidencias/verificacao.md
6. docs/prompts/auditoria.md (em nova conversa) → evidencias/auditoria.md
7. evidencias/revisao_humana.md
8. entrega/orientacao_inicial.md
## Repositório
https://github.com/hinckelsoares-hub/caso-ficticio-chaleira.git
## Como executar
Ler docs/prompts/consulta_rag.md e enviar para a IA somente os arquivos de apoio/.