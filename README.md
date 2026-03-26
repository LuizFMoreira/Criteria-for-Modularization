📄 On the Criteria To Be Used in Decomposing Systems into Modules
Resenha e reflexão acadêmica sobre o paper clássico de D.L. Parnas (1972), produzida como atividade da disciplina de Projeto de Software.

👨‍🎓 Informações Acadêmicas
CampoInformaçãoAlunoLuiz Fernando Batista MoreiraCursoEngenharia de SoftwareSemestre4º SemestreInstituiçãoPUC MinasDisciplinaProjeto de SoftwareProfessorJoão Paulo Aramuni

📖 Sobre o Paper
O artigo "On the Criteria To Be Used in Decomposing Systems into Modules", publicado por D.L. Parnas em dezembro de 1972 na Communications of the ACM, é um dos textos mais importantes da história da Engenharia de Software.
Nele, Parnas questiona algo que parecia óbvio na época: qual é o critério certo para dividir um sistema em módulos? A resposta que ele propõe, usando o princípio de information hiding, mudou a forma como pensamos em arquitetura de software até hoje.
O paper compara duas formas de decompor o mesmo sistema (um índice KWIC) e demonstra, de forma prática, que dividir um sistema seguindo o fluxo de execução gera módulos frágeis e difíceis de manter. A alternativa proposta é que cada módulo deve esconder uma decisão de design dos outros, expondo apenas uma interface abstrata.
Conceitos discutidos no paper:

Critérios de modularização
Information Hiding
Changeability (facilidade de mudança)
Desenvolvimento independente de módulos
Estrutura hierárquica de sistemas


🔗 Acesso ao Paper
O paper completo está disponível no repositório do professor:
📎 Criteria-for-Modularization.pdf
Repositório do professor João Paulo Aramuni:
🐙 github.com/joaopauloaramuni

💡 Por que você deveria ler esse paper?
Esse texto tem mais de 50 anos e ainda descreve exatamente os problemas que aparecem em projetos de software hoje. Se você já teve dificuldade de mudar uma parte do sistema sem quebrar outra, ou sentiu que o código estava difícil de entender porque tudo dependia de tudo, o Parnas já tinha diagnosticado esse problema em 1972.
A leitura é curta, direta e com exemplos práticos. Vale muito o tempo investido, especialmente se você está estudando arquitetura, microsserviços ou boas práticas de design de software.

✍️ Sobre a Resenha
Este repositório acompanha uma resenha crítica do paper, conectando os conceitos de information hiding e modularização com projetos práticos desenvolvidos na PUC Minas, como o RE.USE (sistema de doação de roupas) e o Detalhes Prata (e-commerce de joias artesanais), ambos de 2025.
A resenha também traça uma ponte entre as ideias do Parnas e arquiteturas modernas como microsserviços, mostrando que os problemas de decomposição de sistemas que ele identificou ainda são centrais no desenvolvimento de software atual.

Atividade acadêmica — 4º Semestre de Engenharia de Software, PUC Minas, 2026.
