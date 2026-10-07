# Professor Confusão

Chatbot de **professor "impostor"** (agente ensinável) para Ciências Biológicas do Ensino Fundamental (6º ao 9º ano).

O estudante assume o papel de professor. O Professor Confusão finge não entender e faz perguntas sobre as explicações, para que o estudante justifique, reformule e perceba lacunas no que sabe. Ele nunca corrige nem entrega a resposta.

## Como funciona

- O professor humano informa o **tema**, o **ano**, a **duração da aula** (6, 10 ou 14 respostas), os **conceitos-chave** e os **equívocos comuns** do tema.
- O personagem faz uma pergunta por vez, repete de propósito os equívocos do estudante em tom de dúvida e dá apenas dicas mínimas quando ele trava.
- Ao fim das respostas previstas (ou ao clicar em "Encerrar aula"), ele resume o que "aprendeu" com as palavras do estudante.
- A conversa pode ser salva em arquivo `.txt`.

## Base pedagógica

Efeito protégé (aprender ao ensinar) e agentes ensináveis (*teachable agents*).

## Arquivos

- `professor-confusao.html`: página única (HTML, CSS e JavaScript).

## Limitação importante

A página usa o recurso de IA do próprio Claude (`window.claude`). Por isso, **o chat só funciona quando ela é aberta dentro do Claude**. Em outros lugares (como GitHub Pages), a tela inicial aparece, mas a conversa não inicia.

Para rodar fora do Claude, é preciso trocar a chamada de IA por um servidor próprio que use a API da Anthropic, sem expor a chave no navegador.
