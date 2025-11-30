# medusa-lab-santander-cybersec-2025
Laboratório sobre força bruta utilizando o Medusa, realizado no Bootcamp Santander Cibersegurança 2025.

## Descrição do exercício
Este repositório reúne a documentação do laboratório prático de força bruta usando o Medusa. O objetivo foi entender, de maneira controlada, como a ferramenta funciona e como serviços podem ser comprometidos quando utilizam credenciais fracas.

## Ambiente utilizado
O experimento foi feito com o Kali Linux (máquina atacante) e o Metasploitable 2 (máquina vulnerável). Ambos estavam configurados na mesma rede interna criada apenas para fins de estudo.

## Etapas realizadas
1. Inicialização das máquinas e identificação do endereço IP do Metasploitable.
2. Verificação dos serviços disponíveis no alvo.
3. Criação de pequenas listas de usuários e senhas fracas para uso no teste.
4. Execução do Medusa apontando para um dos serviços do alvo.
5. Observação das respostas da ferramenta para entender o comportamento da autenticação.

## Resultados observados
Durante o teste, foi possível verificar como combinações fracas são facilmente identificadas pela ferramenta. O experimento mostra como ataques automatizados conseguem testar diversas possibilidades rapidamente quando não há mecanismos de proteção como MFA ou bloqueio de tentativas.

## Conclusão
O laboratório reforça a importância de políticas de senha adequadas, autenticação reforçada e monitoração constante. Mesmo em um ambiente simples, a diferença entre uma senha fraca e uma política mínima de proteção é evidente. A atividade também ajudou a entender melhor como funciona o processo de força bruta na prática, dentro de um ambiente seguro e autorizado.
