[**Trabalho Explicando o Python**Arthur Fernandes · Lucas · Murilo](#inicio) [Visão geral](#visao)[Python](#python)[Hello World](#hello)[Execução](#exec)[Ferramentas](#tools)[Robótica](#robo)[Criador](#criador)[Conclusão](#fim)[Por trás do projeto](#prompt)

Arthur Fernandes · Lucas · Murilo

# Trabalho Explicando o Python

Uma jornada pela linguagem Python, pelos fundamentos da engenharia de software e pelas possibilidades da automação e da robótica.

Este trabalho explica o que é Python, como um programa vira resultado e onde a linguagem entra em sistemas de engenharia. A leitura principal leva cerca de três minutos; cada seção continua com exemplos para quem quiser aprofundar.

Símbolo do Python, duas formas entrelaçadas em azul e amarelo

Sumário executivo

## O que existe por trás de uma linha de código?

Python permite escrever instruções que, executadas em um ambiente apropriado, produzem resultados observáveis: cálculos, processamento de dados, automação de tarefas, comunicação com serviços e integração com sistemas de engenharia.

Problema*→*Algoritmo*→*Código*→*Execução*→*Resultado

Python não é a única tecnologia usada nessas áreas, nem a melhor escolha para todo problema: a decisão depende de requisitos, desempenho e integração.

O que é Python?

## Uma linguagem, diferentes possibilidades.

Uma **linguagem de programação** é um conjunto de regras formais para descrever instruções. Diferente de uma linguagem natural, ela não admite ambiguidade: o computador executa exatamente o que está escrito. O texto que o programador escreve é o **código-fonte**, organizado em instruções executadas em sequência.

**Bibliotecas** e **módulos** reúnem código reutilizável, o que evita reescrever tarefas comuns. Executar um programa é pedir a um ambiente de execução que processe essas instruções. Python é valorizado pela sintaxe legível e pela produtividade, mas legibilidade não significa que seja sempre a opção mais rápida.

```
nome = "Sistema de engenharia"
print(f"Iniciando: {nome}")
```

`nome = ...` guarda um texto em uma variável. `print(f"...")` monta uma mensagem com o valor de `nome` e a envia à saída. Resultado: `Iniciando: Sistema de engenharia`.

### Cinco conceitos que não se confundem

História

## De uma ideia experimental a uma ferramenta global.

Uma linguagem evolui por manutenção, comunidade, bibliotecas, documentação e compatibilidade. Python é desenvolvido por uma comunidade internacional de colaboradores. O nome vem do grupo britânico Monty Python. Fontes: [python.org](https://www.python.org/) e [cwi.nl](https://www.cwi.nl/).

Primeiro programa

## Toda grande engenharia começa com uma primeira instrução.

Editor com sete linhas de código Python Hello World e a saída correspondente no terminal

Do código ao resultado: imagem de referência enviada pela equipe. Clique para ampliar.

Pressione “Executar código”.

Simulação didática: este editor interpreta só print, variáveis, f-strings e escapes, em JavaScript. Não é um interpretador Python completo. A tabulação pode variar conforme o terminal.

Execução

## Do código-fonte à execução.

Clique em cada etapa. Este é o modelo geral do CPython; outras implementações podem funcionar de forma diferente.

### Erro de sintaxe

```
print("Olá"
```

Detectado antes de qualquer linha rodar: a estrutura do programa é inválida (`SyntaxError`).

### Erro em execução

```
print("Olá")
print(10 / 0)
```

A sintaxe é válida, então a primeira linha roda e imprime. A segunda falha durante a execução (`ZeroDivisionError`).

Fundamentos

## A lógica que transforma instruções em comportamento.

Os resultados exibidos foram conferidos manualmente, não gerados por esta página.

Ecossistema

## O código é apenas uma parte do processo.

Editar*→*Testar*→*Depurar*→*Versionar*→*Distribuir

As ferramentas têm funções diferentes e nenhuma é obrigatória em todo projeto: editor e IDE, por exemplo, são alternativas parecidas, enquanto pip, venv e Git resolvem problemas distintos.

Engenharia e robótica

## Quando o software encontra o mundo físico.

Sensores*→*Aquisição*→*Processamento*→*Decisão*→*Comando*→*Atuadores*→*Feedback

### Onde Python participa

Por bibliotecas, interfaces e sistemas compatíveis, Python aparece em partes desse fluxo:

### Limitações

Tempo real estrito, segurança funcional, latência, hardware e determinismo podem exigir outras linguagens, controladores ou arquiteturas. Um script Python sozinho não basta para controlar com segurança um robô industrial.

Sem fotografias de robôs enviadas pela equipe, esta versão usa diagramas em vez de imagens de terceiros.

Laboratório

## Experimente a lógica de um sistema.

```

```

Temperatura de entrada: °C

Entrada: `—`

Condição avaliada: `—`

Mensagem: `—`

Simulação didática, sem conexão com sensores reais.

Criador

## A pessoa por trás da linguagem.

### Guido van Rossum

Programador neerlandês que começou a desenvolver Python no final de 1989, no CWI, e publicou a primeira versão em 1991. Ele criou a linguagem com foco em legibilidade e clareza, princípios que seguem associados ao Python.

Fotos enviadas pela equipe, sem licença verificada. Confirme procedência e atribuição antes de publicar.

Guido van Rossum, criador da linguagem Python

Guido van Rossum, criador da linguagem Python, em foto recente

Logotipo do Python

## Tecnologia começa com uma ideia. Engenharia transforma essa ideia em sistemas.

Python oferece uma forma acessível de escrever instruções; o ecossistema permite atuar em várias áreas; testes e boas práticas dão confiabilidade; a robótica exige integrar software, hardware, dados e segurança.

Do código à execução: compreender a lógica é o primeiro passo para construir sistemas mais inteligentes.

Arthur Fernandes · Lucas · Murilo

Transparência

## Por trás do projeto: Engenharia de Prompt e Inteligência Artificial

Este site começou como uma ideia: criar uma apresentação educativa sobre Python. Ela evoluiu por instruções, chamadas de *prompts*, cada vez mais detalhadas, enviadas ao Claude, uma inteligência artificial da Anthropic. A IA foi uma ferramenta de apoio para estruturar o conteúdo, propor soluções de design, escrever o código e aperfeiçoar a apresentação. A equipe definiu o tema, forneceu os materiais, avaliou cada versão e decidiu o que mudar.

Ideia inicial*→*Planejamento*→*Engenharia de prompt*→*Geração do projeto*→*Avaliação visual*→*Refinamento*→*Resultado final

O resultado foi construído de forma iterativa: cada versão foi analisada e os novos pedidos corrigiram o que ainda não funcionava.

### As rodadas do projeto

1. **1**Prompt inicial: papel, objetivo, público, identidade visual e 9 seções. Gerou a primeira versão, com cena 3D.
2. **2**Página Hello World: a imagem enviada pela equipe entrou como parte do conteúdo, junto de um editor interativo.
3. **3**Reformulação: a equipe achou a versão básica e vazia. Pediu menos 3D e mais conteúdo editorial, em 12 seções.
4. **4**Identidade: o título passou a ser “Trabalho Explicando o Python”.
5. **5**Símbolo do Python em 3D no lugar do mecanismo robótico, e logo do SENAI fixa no canto.
6. **6**Esta seção, para explicar o processo com transparência.

### Técnicas de engenharia de prompt usadas

### Papel e objetivo

O primeiro prompt definiu quem a IA deveria ser (engenheiro de software e diretor criativo) e o que o site precisava alcançar.

### Público e tempo

O pedido indicou um executivo com cerca de três minutos, o que orientou a hierarquia: ideia, demonstração, explicação e detalhes opcionais.

### Restrições claras

Instruções como “não invente” fatos, cargos ou métricas, e “não use simulação como se fosse hardware real”, reduzem erros e exageros.

### Critérios de aceitação

Listas do que precisava estar pronto para o trabalho ser considerado concluído deixaram a avaliação objetiva.

### Material de referência

Imagens enviadas (código Hello World, fotos de Guido, logos) deram à IA dados reais, em vez de inventados.

### Feedback concreto

Dizer o que estava errado (“muito básico, grandes espaços vazios”) rendeu melhorias mais úteis que pedir “melhore”.

### Trechos reais dos prompts

```
Não invente cargos, títulos acadêmicos, certificações, clientes,
empresas, resultados financeiros ou experiência profissional.
```

```
Reduza drasticamente a presença do 3D. Menos efeitos gratuitos,
mais substância, precisão e credibilidade.
```

### Papel de cada parte

**Equipe:** escolheu o tema, enviou imagens e logos, avaliou as versões e tomou as decisões.\
**IA:** organizou o conteúdo, escreveu textos, código HTML, CSS e JavaScript, e propôs o design.

### Limitações e cuidados

A IA pode errar, por isso fatos e datas devem ser conferidos nas fontes oficiais, como python.org. Neste site, o editor do Hello World é uma simulação em JavaScript e não roda Python real. Os resultados da seção de fundamentos foram conferidos manualmente. As fotos de Guido e as logos foram enviadas pela equipe e a licença delas não foi verificada.

Trabalho Explicando o Python

Trabalho acadêmico desenvolvido por:

Arthur Fernandes · Lucas · Murilo

SENAI — Serviço Nacional de Aprendizagem Industrial

Referências: [python.org](https://www.python.org/) · [docs.python.org](https://docs.python.org/3/) · [cwi.nl](https://www.cwi.nl/)

Logomarca do SENAI