# Anexo C (normativo): Determinação de conformidade

## C.1 Introdução
Este anexo normativo estabelece os meios necessários para determinar o cumprimento dos requisitos individuais estabelecidos no corpo do presente documento. Todas as cláusulas, exceto a 12, são de auto-análise. Isto significa que são introduzidas com a frase 'Onde a TIC <pré-condição>'. A conformidade é verificada quando a pré-condição é verdadeira e o teste correspondente (no Anexo C) é positivo, ou quando a pré-condição é falsa (ou seja, a pré-condição não é atendida ou não é válida).

Para apoio ao leitor, foram inseridas algumas cláusulas vazias para que a numeração do anexo reflita a numeração das cláusulas dos requisitos.

As TIC são frequentemente compostas por dois ou mais itens de TIC. Em alguns casos, dois ou mais itens interoperáveis da TIC podem, conjuntamente, cumprir mais requisitos da norma quando um item complementa a funcionalidade do outro e a soma do conjunto satisfaz requisitos de acessibilidade. No entanto, a combinação de dois itens de TIC que cumprem nenhum requisito específico, não levará a um sistema combinado de TIC que atenda a esse requisito.  

O presente documento não prioriza os requisitos. A priorização desses requisitos é deixada ao critério do utilizador do presente documento. 

A priorização dos requisitos que se alinham com o contexto de utilização pode melhorar a acessibilidade, no caso de conformidade parcial, e a justificação para essa priorização, se usada, deve ser declarada. 

A conformidade deve ser reportada num formulário tal que: 
- seja claro se há conformidade com todos os requisitos aplicáveis ou se há conformidade apenas com alguns requisitos; 
- sejam registadas as técnicas de amostragem e avaliação utilizadas para avaliar as TIC; 
- se anote se a funcionalidade acessível equivalente existe em locais onde a não-conformidade tenha sido
encontrada; e 
- se observa se foram utilizados meios equivalentes que atingem o resultado previsto, quando a não-conformidade técnica tenha sido encontrada.

**NOTA 1**: Em algumas situações, quando este documento é usado para outros fins que não a Diretiva 2016/2102 [i.28], as necessidades de acessibilidade do utilizador podem ser atendidas por um subconjunto de requisitos. Por exemplo, onde as TICs são desenvolvidas para serem usadas por um utilizador específico, ou num cenário de utilização bem definido, uma declaração de desempenho funcional particular na cláusula 4.2 e/ou requisito associado das cláusulas 5 a 13, poderia ser omitida, caso essa omissão não tenha impacto negativo nas necessidades de acessibilidade dos utilizadores previstos originalmente. 

**NOTA 2:** A conformidade com os requisitos de acessibilidade pode ser afetada pela implementação ou manutenção subsequente.

**NOTA 3:** A amostragem é frequentemente necessária em TICs complexas, quando há muitas instâncias do objeto a ser testado. Este documento não pode recomendar técnicas específicas de avaliação por amostragem, pois estas são particulares de cada contexto.

## C.2 Cláusula vazia
Esta cláusula está intencionalmente vazia.

## C.3 Cláusula vazia
Esta cláusula está intencionalmente vazia.

## C.4 Desempenho funcional
A Cláusula 4 é informativa e não contém requisitos que precisem de testes.

## C.5 Requisitos gerais
### C.5.1 Funcionalidade fechada
#### C.5.1.1 Introdução
A Cláusula 5.1.1 é informativa e não contém requisitos que precisem de testes.
#### C.5.1.2 Geral
##### C.5.1.2.1 Funcionalidade fechada
As TIC com funcionalidade fechada devem cumprir os requisitos nas cláusulas  C.5.2 a  C.13, como aplicável.
##### C.5.1.2.2 Tecnologia de Apoio
Tipo de avaliação|Teste
-----------------|-------
Pré-condições    |1. A TIC tem funcionalidade fechada.
Procedimento     |1. Determine as funções fechadas da TIC. <br>2. Verifica-se que os testes  C.5.1.3 a  C.5.1.6 podem ser feitos sem a utilização de qualquer tecnologia de apoio, com exceção de headsets ou inductive loops.
Resultado        |Passa: A verificação 2 é verdadeira<br>Falha: A verificação 2 é falsa

#### C.5.1.3 Acesso não visual
##### C.5.1.3.1 Geral
Tipo de avaliação|Teste
-----------------|-------
Pré-condições    |1. É necessária informação visual para ativar as funções da TIC que são fechadas a tecnologias de apoio para leitura de ecrã.
Procedimento     |1. Determinar as funções da TIC que são fechadas a leitor de ecrã.2. Verifica-se que as funções identificadas são operáveis com acesso não visual.
Resultado        |Passa: A verificação 2 é verdadeira<br>Falha: A verificação 2 é falsa

##### C.5.1.3.2 Retorno auditivo incluindo fala
Tipo de avaliação|Inspeção
-----------------|-------
Pré-condições    |1. É fornecida um retorno auditivo como acesso não visual à funcionalidade fechada.
Procedimento     |1. Verificar que o retorno auditivo é fornecida por um mecanismo incluido ou fornecido com a TIC.<br>2. Verifica-se que o retorno auditivo é fornecida por um auscultador pessoal que pode ser ligado através de um audio jack de 3,5 mm ou uma ligação standard da indústria tal que não seja necessário acesso visual.
Resultado        |Passa: A verificação 2 é verdadeira<br>Falha: A verificação 2 é falsa

##### C.5.1.3.3 Correlação do retorno auditivo
A Cláusula 5.1.3.3 é apenas informativa e não contém requisitos que precisem de testes.

##### C.5.1.3.4 Controlo através da fala
Tipo de avaliação|Inspeção
-----------------|-------
Pré-condições    |1. A fala é fornecida como um acesso não-visual à funcionalidade fechada.
Procedimento     |1. Verificar que a fala pode ser interrompida quando requerido pelo utilizador.<br>2. Verificar que a fala pode ser repetida quando requerido pelo utilizador.
Resultado        |Passa: Todas as verificações são verdadeiras<br>Falha: Pelo menos uma das verificações é falsa.

##### C.5.1.3.5 Interrupção automática da fala
Tipo de avaliação|Inspeção
-----------------|-------
Pré-condições    |1. A Fala é fornecida como um acesso não-visual à funcionalidade fechada.
Procedimento     |1. Determinar as funcionalidades fechadas da TIC.<br>2. Verificar que a saída de fala para cada função é interrompida por ação do utilizador.<br>3. Verificar que a saída de fala para cada função é interrompida quando uma nova saída de fala é iniciada.
Resultado        |Passa: As verificações 1 e 3 são verdadeiras. são verdadeiras<br>Falha: As verificações 1 e 3 são falsas.

##### C.5.1.3.6 Fala para conteúdo não-textual
Tipo de avaliação|Teste
-----------------|-------
Pré-condições    |1. A Fala é fornecida como um acesso não-visual à funcionalidade fechada.
Procedimento     |1. Determinar as funcionalidades fechadas da TIC.<br>2. Verificar que texto não é apenas decorativo.<br>3. Verificar que o texto não é usado apenas para formatação visual.<br>4. Verificar que a saída de fala segue orientação da "alternativa de texto" descrita no Critério de Sucesso 1.1.1 da WCAG 2.1.
Resultado        |Passa: Todas as verificações são verdadeiras; ou 1 e 2 são falsas; ou 1 e 3 são falsas.<br>Falha: Verificação 1 é verdadeira e 2 é falsa; 1 é verdadeira e 3 é falsa; ou 1 e 2 e 3 são verdadeiras e 4 é falsa .

##### C.5.1.3.7 Fala para informação em vídeo
Tipo de avaliação|Teste
-----------------|-------
Pré-condições    |1. É necessário conteúdo de vídeo pré-gravado para ativar a utilização de funcionalidades fechadas da TIC.<br>2. A saída de fala é fornecida como acesso não-visual a conteúdo não-textual exibido na funcionalidade fechada.
Procedimento     |1. Verificar que a saída de fala apresenta informação equivalente à do conteúdo pré-gravado do vídeo.
Resultado        |Passa: A verificação 1 é verdadeira<br>Falha: A verificação 1 é falsa.

##### C.5.1.3.8 Masked entry**
Tipo de avaliação|Teste
-----------------|-------
Pré-condições    |1. O retorno auditivo é fornecido como acesso não-visual à funcionalidade fechada.<br>2. Os caracteres exibidos são masking characters***.<br>3. O utilizador não escolhe especificamente permitir saída auditiva não-privada.
Procedimento     |1. Verificar que a saída auditiva não é uma versão falada dos carateres escritos.<br>2. Verificar que é conhecido que a saída auditiva é fornecida apenas para um mecanismo de escuta privada.<br>3. Se 1 e 2 são falsos, verificar que o utilizador escolheu específicamente permitir a saída auditiva não-privada.
Resultado        |Passa: Pelo menos uma das verificações é verdadeira.<br>Falha: Todas as verificações são falsas.

##### C.5.1.3.9 Acesso privado a dados pessoais
Tipo de avaliação|Teste
-----------------|-------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.<br>2. A saída contém dados.<br>3. Aplica-se uma política de privacidade de dados que considera os dados privados.
Procedimento     |1. Verificar que a saída auditiva é fornecida apenas para um mecanismo de escuta privada.<br>2. Verificar que o mecanismo de escuta privada pode ser ligado sem precisar da visão.<br>3. Verificar que a saída auditiva pode ser fornecida por qualquer outro mecanismo escolhido pelo utilizador.
Resultado        |Passa: A verificação 1 ou 2 são verdadeiras; ou 3 é verdadeira.<br>Falha: As verificações 1 ou 2 e 3 são falsas.

##### C.5.1.3.10 Saída de áudio sem interferência
Tipo de avaliação|Inspeção
-----------------|-------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.<br> 2. A TIC reproduz automaticamente saída de áudio com interferência.
Procedimento     |1. Verificar que a interferência audível não dura mais de 3 segundos.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.5.1.3.11 Volume de escuta privada
Tipo de avaliação|Inspeção
-----------------|-------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada. <br>2. A saída auditiva é fornecida por um mecanismo de escuta privada.
Procedimento     |1. Verificar que existe pelo menos um modo de operação não-visual para controlar o volume do som.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.5.1.3.12 Volume do altifalante
Tipo de avaliação|Inspeção e Medida
-----------------|-----------------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.<br>2. A saída auditiva é fornecida por altifalantes.
Procedimento     |1. Verificar que existe um modo de operação não-visual para controlar incrementalmente o volume do som.<br>2. Verificar que a amplificação pode ir o nível, de pelo menos, 65 dBA (-29 dBPaA).
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: As verificações 1 e/ou 2 são falsas.

##### C.5.1.3.13 Reinicialização do volume
Tipo de avaliação|Inspeção e Medida
-----------------|-----------------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.<br>2. A saída auditiva não é dedicada a apenas um utilizador.
Procedimento     |1. Verificar que existe um modo de automaticamente colocar o som a 65 dBA, ou menos, depois de cada utilização.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.5.1.3.14 Idiomas falados
Tipo de avaliação|Teste
-----------------|-----------------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.<br>2. A saída de fala não é nomes próprios, termos técnicos, palavras de idioma indeterminado, e palavras ou frases que fazem parte do vernáculo do texto circundante.<br>3. **O conteúdo não é gerado externamente e está sob controlo do vendedor da TIC.<br>4. Os idiomas exibidos podem ser selecionados usando acesso não-visual.<br>5. O utilizador não selecionou um idioma de saída de fala diferente do idioma do conteúdo exibido.
Procedimento     |1. Verificar que o idioma da saída de fala é o mesmo do conteúdo exibido.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.5.1.3.15 Identificação não-visual de erro
Tipo de avaliação|Teste
-----------------|-----------------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.<br>2. Um erro de entrada é automaticamente detetado.
Procedimento     |1. Verificar que o idioma da saída de fala identifica o elemento que está com erro.<br>2. Verificar que o idioma da saída de fala descreve o elemento que está com erro.
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: As verificações 1 e/ou 2 são falsas.

##### C.5.1.3.16 Recibos, bilhetes e saídas transacionáveis
Tipo de avaliação|Teste
-----------------|-----------------
Pré-condições    |1. A TIC é fechada ao acesso visual. <br>2. A TIC fornece recibos, bilhetes, ou outras saídas como um resultado de uma transação self-service.<br>3. A informação verificada não se trata de cópias impressas de itinerários e mapas.
Procedimento     |1. Verificar que a saída de fala é fornecida, incluindo toda a informação necessária para completar ou verificar a transação.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.5.1.4 Funcionalidade fechada à ampliação de texto
Tipo de avaliação|Inspeção e Medida
-----------------|-----------------
Pré-condições    |1. A funcionalidade da TIC é fechada a características de ampliação da plataforma ou tecnologia de apoio.<br>2. Uma distância de visualização é especificada pelo fornecedor.
Procedimento     |1. Medir a altura da letra maiúscula H.<br>2. Verificar que subtende um ângulo de, pelo menos, 0,7 graus da visualização especificada.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.5.1.5 Retorno visual para informação auditiva
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A informação auditória pré-gravada é necessária para permitir o uso de funcionalidades fechadas da TIC.
Procedimento     |1. Verificar que a informação visual é equivalente à saída auditiva pré-gravada.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.5.1.6 Operação sem interface de teclado
##### C.5.1.6.1 Funcionalidade fechada
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é fechada a teclados e interfaces de teclado. 
Procedimento     |1. Verificar que todas as funcionalidades são operáveis sem visão.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.5.1.6.2 Foco de Entrada
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é fechada a teclados e interfaces de teclado. <br>2. O foco de entrada pode ser movido para um componente de interface de utilizador.
Procedimento     |1. Verificar que é possível mover o foco de entrada desse elemento para outro usando o mesmo mecanismo.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.2 Ativação dos recursos de acessibilidade
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem características de acessibilidade documentadas para cumprir uma determinada necessidade.
Procedimento     |1. Verificar que é possível ativar essas características de acessibilidade sem precisar de um método que não suporta essa necessidade. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.3 Biometria
Tipo de avaliação|Teste 1
-----------------|--------
Pré-condições    |1. A TIC usa características biológicas para identificação de utilizador.
Procedimento     |1. Verificar que mais do que um meio pode ser usado para identificação de utilizador. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
Tipo de avaliação|Teste 2
Pré-condições    |1. A TIC usa características biológicas para controlo da TIC.
Procedimento     |1. Verificar que mais do que um meio pode ser usado para controlar a TIC. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.4 Preservação da informação de acessibilidade durante a conversação
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A informação não-proprietária fornecida para acessibilidade é documentada.<br>2. A TIC converte informação ou comunicação.<br>3. A informação não-proprietária fornecida para acessibilidade pode ser contida no formato de destino. <br>4. A informação não-proprietária fornecida para acessibilidade pode ser suportada pelo formato de destino. 
Procedimento     |1. Verificar que informação não-proprietária fornecida para acessibilidade é preservada quando a TIC converte informação ou comunicação. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.5 Partes operáveis
#### C.5.5.1 Modos de operação
Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. A TIC tem partes operáveis que requerem agarrar, prensar ou torcer o pulso para operar.  
Procedimento     |1. Verificar que há modos de operação alternativos acessíveis que não requerem estas ações. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.5.5.2 Perceção das partes operáveis
Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. A TIC tem partes operáveis.  
Procedimento     |1. Identificar que há um modo de discernir cada parte operável sem a visão. <br>2. Verificar que a ação associada com a parte operável não foi executada quando a usar o modo de discernir cada parte operável, no passo 1.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.6 Controlos de bloqueio ou alternância
#### C.5.6.1 Estado tátil ou auditivo
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem um controlo de bloqueio ou de alternância.<br>2. O controlo de bloqueio ou de alternância é visualmente apresentado ao utilizador.
Procedimento     |1. Verificar que pelo menos um modo de operação onde o estado de todos os controlos de bloqueio ou alternância pode ser determinado por toque sem operar o controlo. <br> 2. Verificar que há pelo menos um modo de operação onde o estado de todos os controlos de bloqueio ou alternância pode ser determinado por som sem operar o controlo.  
Resultado        |Passa: A verificação 1 ou a 2 é verdadeira.<br>Falha: As verificações 1 e 2 são falsas.

#### C.5.6.2 Estado visual
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem um controlo de bloqueio ou de alternância.<br>2. O controlo de bloqueio ou de alternância é apresentado ao utilizador.
Procedimento     |1. Verificar que há pelo menos um modo de operação onde o estado de todos os controlos de bloqueio ou alternância pode ser visualmente determinado quando o controlo é apresentado.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.7 Repetição de Tecla
Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. A TIC tem uma função de repetição de tecla. Um teclado com repetição de tecla é fornecido. <br>2. A repetição de tecla não pode ser desligada.  
Procedimento     |1. Verifique que o tempo entre repetições pode ser ajustado para, pelo menos, 2 segundos.  <br>1. Verifique que o tempo entre repetições de uma mesma tecla pode ser ajustado para, pelo menos, 2 segundos. 
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: As verificações 1 e 2 são falsas.

### C.5.8 Ativação dupla de tecla
Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. A TIC tem um teclado. Um teclado é fornecido. 
Procedimento     |1. Verifique que há um mecanismo de ajuste do tempo durante o qual, após uma tecla ser pressionada, são ignoradas pressões dessa mesma tecla.  <br>2. Ajuste o mecanismo para o seu valor máximo.<br>3. Prima qualquer tecla. <br>4. Depois de 0,5 segundos, prima a mesma tecla que foi premida no passo 3.<br>5. Verifique se a tecla premida no passo 4 foi aceite.  
Resultado        |Passa: A verificação 1 é verdadeira e a 5 é falsa.<br>Falha: A verificação 1 é falsa e a 5 é verdadeira.

### C.5.9 Ações simultâneas do utilizador
Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |Nenhuma  
Procedimento     |1. Se houver múltiplos modos de operação, selecione um modo de operação (ver notas 1 e 2 desta tabela para orientação na seleção). <br>2. Determinar todas as funções controláveis pelo utilizador.<br>3. Verificar que cada função pode ser controlada com apenas um ponto de contacto. <br>4. Se houver múltiplos modos de operação e o teste não tiver passado, repita o procedimento até que todos os modos tenham sido testados. 
Resultado        |Passa: A verificação 3 é verdadeira.<br>Falha: A verificação 3 é falsa para todos os modos de operação.

## C.6 TIC para comunicação bidirecional por voz

### C.6.1 Largura de banda de áudio para fala
Tipo de avaliação|Medida
-----------------|--------
Pré-condições    |1. A TIC que está a ser testada fornece comunicação bidirecional por voz.
Procedimento     |1. Verificar que a TIC pode codificar e descodificar áudio com uma gama de frequências com um limite superior de, pelo menos, 7000Hz.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.6.2	Funcionalidade de texto em tempo real (TTR)
#### C.6.2.1	Provisão de TTR
##### C.6.2.1.1	Comunicação de TTR
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC que está a ser testada fornece comunicação bidirecional por voz.<br>Um dispositivo de "referência" TTR compatível com o sistema está ligado ao outro extremo do sistema.
Procedimento     |1. Verificar que a TIC permite que um utilizador comunique com a TIC de "referência" através de RTT.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.6.2.1.2 Voz e texto concorrentes
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC que está a ser testada fornece comunicação bidirecional por voz.<br>A TIC permite que um utilizador comunique com outro através de TTR.
Procedimento     |1. Verificar que a TIC fornece um mecanismo para selecionar o modo de operação que permite voz e texto concorrentes.                  |2. Verificar que a TIC permite a utilização de voz e texto concorrentes quando no modo de operação identificado no passo 1.
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: As verificações 1 e 2 são falsas.

#### C.6.2.2 Exibição do texto em tempo real
##### C.6.2.2.1	Visor visualmente distinguível
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC que está a ser testada tem capacidade de envio e receção TTR.<br>A TIC suporta mecanismo(s) TTR.<br>Um terminal "referência" compatível com o sistema está ligado no outro extremo do sistema à TIC sob teste.
Procedimento     |1. A TIC sob teste está ligada a um sistema TIC terminado por um terminal "referência".<br>2. Os elementos diferentes da TIC estão num estado operacional (a ligação está ativa e os terminais estão no modo TTR relevante) e os dois terminais estão a comunicar entre si.<br>3. Uma sequência curta de texto é enviada pela TIC sob teste.<br>4. Uma sequência curta de texto é enviada pelo terminal "referência".<br>5. Verificar, na TIC sob teste, que o texto enviado é visualmente diferenciado e separado do texto recebido. 
Resultado        |Passa: A verificação 5 é verdadeira.<br>Falha: A verificação 5 é falsa.
NOTA: Um terminal "referência" é um terminal com funcionalidade de envio e receção TTR, que usa mecanismos TTR suportados no sistema TIC. Este terminal "referência" é da responsabilidade do laboratório de teste.        


##### C.6.2.2.2	Direção de envio e receção programaticamente determinável
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC que está a ser testada tem capacidade de envio e receção TTR.<br>O TTR é de funcionalidade aberta.<br>Um terminal "referência" usando mecanismos suportados pela rede TIC está ligado no outro extremo do sistema à TIC sob teste.
Procedimento     |1. A TIC sob teste está ligada a um sistema TIC terminado por um terminal "referência".<br>2. Os elementos diferentes da TIC estão num estado operacional (a ligação está ativa e os terminais estão no modo TTR relevante) e os dois terminais estão a comunicar entre si.<br>3. Uma sequência curta de texto é enviada pela TIC sob teste.<br>4. Uma sequência curta de texto é enviada pelo terminal "referência".<br>5. Verificar que a direção envio/receção do texto transmitido é programaticamente determinável. 
Resultado        |Passa: A verificação 5 é verdadeira.<br>Falha: A verificação 5 é falsa.
NOTA: Um terminal "referência" é um terminal com funcionalidade de envio e receção TTR, que usa mecanismos TTR suportados no sistema TIC. Este terminal "referência" é da responsabilidade do laboratório de teste.        

#### C.6.2.3 Interoperabilidade
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC que está a ser testada suporta comunicação bidirecional por voz.<br>A TIC sob teste suporta funcionalidade TTR.
Procedimento     |1. Verificar que a TIC opera sobre uma rede telefónica pública comutada (RTPC), com outras TIC diretamente ligadas à RTCP, conforme descrito na Recomendação ITU-T V.18 [i.23] ou qualquer um dos seus anexos para sinais de texto na interface RTP C.<br>2.Verificar que a TIC interopera com outras TIC usando VOIP com *Session Initiation Protocol (SIP) e usando o TTR que está em conformidade com IETF RFC 4103 [i.13]<br>3.Verificar que a TIC interopera com outras TIC que utilizam TTR em conformidade com o conjunto de protocolos do Subsistema Multimédia de IP (IMS) especificado na ETSI TS 126 114 [i.10], ETSI TS 122 173 [i.11] e ETSI TS 134 229 [i.12];<br>4.Verificar que a TIC interopera com outras TIC, utilizando uma especificação comum relevante e aplicável para o intercâmbio TTR, publicada e disponível. <br>5.Verificar que a especificação na verificação 4 inclui um método para indicar perda ou corrupção de caracteres. 
Resultado        |Passa: A verificação 1 ou 2 ou 3 ou 4 e 5 são verdadeiras.<br>Falha: As verificações 1, 2 e 3 são falsas ou a 4 ou a 5 é falsa.

#### C.6.2.4 Responsividade de texto em tempo real
Tipo de avaliação|Inspeção de dados medidos ou Teste
-----------------|--------
Pré-condições    |1. A TIC que está a ser testada tem capacidade de envio e receção TTR.<br>2. Um terminal "referência" usando mecanismos suportados pela rede TIC está ligado no outro extremo do sistema à TIC sob teste.<br>3. A TIC sob teste está ligada a um sistema TIC terminado por um terminal "referência". <br>4. Os elementos diferentes da TIC estão num estado operacional (a ligação está ativa e os terminais estão no modo TTR relevante) e os dois terminais estão a comunicar entre si.  
Procedimento     |1. Uma sequência curta é introduzida no terminal sob teste. 2. <br>Verificar a hora a que a sequência é introduzida no terminal.3. <br>Verificar o tempo entre a hora em que a sequência é introduzida no terminal TIC sob teste e a hora a que o texto é transmitido para a rede da TIC. 
Resultado        |Passa: A verificação 3 é menor ou igual a 3 segundos.<br>Falha: A verificação 3 é maior ou igual a 3 segundos.
NOTA: Como descrito nas notas da cláusula 6.2.4, a identificação de quando a entrada ocorreu pode variar de acordo com o tipo de sistema TTR sob teste.

### C.6.3	Identificação de Chamadas – Caller ID
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC fornece identificação de chamadas ou funções semelhantes de telecomunicações.
Procedimento     |1. Verificar que a informação entregue por cada função é disponibilizada como texto.<br>2. Verificar que a informação entregue por cada função é disponibilizada numa outra modalidade.
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: Uma das verificações 1 ou 2 é falsa.

### C.6.4	Alternativas para serviços baseados em voz
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC fornece uma comunicação em tempo real baseada em voz.<br>2. A TIC fornece recursos de correio de voz, atendimento automático ou resposta de voz interativa.
Procedimento     |1. A TIC oferece aos utilizadores um meio para aceder às informações sem o uso de audição ou fala.<br>2. A TIC oferece aos utilizadores um meio para executar as tarefas fornecidas pelo sistema sem o uso de audição ou fala.
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: Uma das verificações 1 ou 2 é falsa.


### C.6.5	Comunicação por Vídeo
#### C.6.5.1 Geral (informativo)
A cláusula 6.5.1 é apenas informativa e não contém requisitos que precisem de ser testados.

#### C.6.5.2 Resolução
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC fornece comunicação de voz bidirecional.<br>2. A TIC inclui funcionalidade de vídeo em tempo real.
Procedimento     |1. Verificar que a resolução da comunicação por vídeo é a resolução QCIF ou melhor.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.6.5.4	Sincronização entre áudio e vídeo
Tipo de avaliação|Medida
-----------------|--------
Pré-condições    |1. A TIC fornece comunicação de voz bidirecional.<br>2. A TIC inclui funcionalidade de vídeo em tempo real.
Procedimento     |1. Verificar que o atraso entre o vídeo e a fala apresentados ao utilizador é igual ou inferior a 100ms.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.6.6 Alternativas para serviços baseados em vídeo
A cláusula 6.6 é indicativa apenas e não contém requisitos que precisem de ser testados.

## C.7 **ICT with video capabilities
### C.7.1 **Caption processing technology
#### C.7.1.1 **Captioning playback
Tipo de avaliação|Teste1
-----------------|--------
Pré-condições    |1. A TIC exibe ou processa vídeo com áudio sincronizado.<br>2. A TIC fornece legendas com o vídeo.
Procedimento     |1. Verificar que há um mecanismo para exibir as legendas.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
Tipo de avaliação|Teste2
-----------------|--------
Pré-condições    |1. A TIC exibe ou processa vídeo com áudio sincronizado.<br>2. São disponibilizadas legendas fechadas como parte do conteúdo.
Procedimento     |1. Verificar que há um mecanismo para escolher a visualização de legendas.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.7.1.2	Sincronização de Legendas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem um mecanismo para exibir legendas.
Procedimento     |1. Verificar que há o mecanismo para exibir as legendas preserva a sincronização entre o áudio e as legendas correspondentes.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.7.1.3	Preservação das Legendas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem um mecanismo para exibir legendas.
Procedimento     |1. Verificar que a TIC preserva os dados de legendagem de modo a que possa ser exibida de forma consistente com as cláusulas 7.1.1 e 7.1.2.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.7.2 Tecnologia de áudio-descrição
#### C.7.2.1 Áudio-descrição
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC exibe vídeo com áudio sincronizado.
Procedimento     |1. Verificar que existe um mecanismo explícito e separado para a áudio-descrição.<br>2. Verificar que existe um mecanismo de selecionar e reproduzir a descrição de áudio disponível para o canal de áudio usado por defeito.<br>3. Verificar que a TIC permite ao utilizador selecionar e reproduzir várias faixas de áudio.
Resultado        |Passa: As verificações 1 e 2 são verdadeiras ou 1 é falsa e 3 é verdadeira.<br>Falha: A verificação 1 é verdadeira e 2 é falsa ou 1 é falsa ou 3 é falsa.

#### C.7.2.2 Áudio-descrição sincronizada
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem um mecanismo para exibir áudio-descrição.
Procedimento     |1. Verificar que a TIC preserva a sincronização entre o conteúdo áudio/visual e a descrição áudio correspondente.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.7.2.3	Preservação da áudio-descrição
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC transmite, converte ou grava vídeo com áudio sincronizado.
Procedimento     |1. Verificar que a TIC preserva os dados de áudiodescrição tal que estes possam ser transmitidos de uma forma consistente com as cláusulas 7.2.1 e 7.2.2.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.7.3	Controlos de utilizador para legendas e áudio-descrição
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC exibe primeiramente materiais contendo vídeo com conteúdo áudio associado.
Procedimento     |1. Verificar que a TIC fornece ao utilizador controlos para ativar a legendagem e áudiodescrição, ao mesmo nível de interação que os controlos de média principais.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

## C.8 Hardware
### C.8.1 Geral
#### C.8.1.1 Requisitos gerais
A cláusula 8.1.1 não contém requisitos que precisem de ser testados.

#### C.8.1.2 Ligações standard
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC fornece pontos de ligação de entrada ou saída de utilizador em dispositivos.
Procedimento     |1. Verificar que pelo menos uma ligação de entrada e/ou saída que está em conformidade com um formato industrial standard não-proprietário.<br>2. Verificar que pelo menos uma ligação de entrada e/ou saída que está em conformidade com um formato industrial standard não-proprietário, através do uso de adaptadores comercialmente disponíveis.
Resultado        |Passa: As verificações 1 ou 2 são verdadeiras.<br>Falha: As verificações 1 e 2 são falsas.

#### C.8.1.3 Cor
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC TIC contém características de hardware que usam a cor.
Procedimento     |1. Verificar que a TIC fornece ao utilizador uma alternativa de código de informação visual.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.8.2	Produtos de hardware com saída de fala
#### C.8.2.1	Volume de Fala
##### C.8.2.1.1	Amplitude de volume de fala
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A TIC tem saída de fala.
Procedimento     |1. Verificar que a TIC é certificada para ANSI/TIA-4965.<br>2. Medir o nível (em dB) da saída de fala, no nível de volume mínimo.<br>3. Medir o nível (em dB) da saída de fala, no nível de volume máximo.<br>4. Verificar que a diferença entre o nível máximo medido em 3 e o nível mínimo medido em 2 é superior a 18dB.
Resultado        |Passa: As verificações 1 ou 4 são verdadeiras.<br>Falha: As verificações 1 e 4 são falsas.

##### C.8.2.1.2 Controlo de volume incremental
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A TIC tem saída de fala.<br>2. A TIC tem controlo de volume incremental.
Procedimento     |<br>1. Medir o nível (em dB) da saída de fala, no nível de volume mínimo.<br>2. Verificar se há um passo intermédio de ganho 12 dB acima do nível mínimo, medido em 1.
Resultado        |Passa: A verificação 2 é verdadeira.<br>Falha: A verificação 2 é falsa.

#### C.8.2.2 Acoplamento magnético
##### C.8.2.2.1	Dispositivos de linha fixa
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A TIC é um dispositivo de comunicação de linha fixa com saída de fala e que é normalmente usado na orelha.<br>A TIC tem um símbolo "T".
Procedimento     |1. Verificar que a TIC é certificada para TIA-1083-A [i.24].<br>2. As medidas são feitas de acordo com o estabelecido na norma ETSI ES 200 381-1 [2], o que prova que os requisitos definidos nessa norma são cumpridos.  
Resultado        |Passa: A verificação 1 ou 2 são verdadeiras.<br>Falha: As verificações 1 e 2 são falsas.

##### C.8.2.2.2 Dispositivos de comunicação sem fios
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A TIC é um dispositivo de comunicação sem fios com saída de fala, normalmente usado na orelha.
Procedimento     |1. Verificar que a TIC é certificada para ANSI/IEEE C63.19 [i.1].<br>2. Verificar que a TIC fornece meios de acoplamento magnético para tecnologias auditivas que cumprem os requisitos em ETSI ES 200 381-2 [3].  
Resultado        |Passa: A verificação 1 ou 2 são verdadeiras.<br>Falha: As verificações 1 e 2 são falsas.

### C.8.3	Acesso físico à TIC
#### C.8.3.1	Geral (informativo)
A cláusula 8.3.1 é apenas indicativa e não contém requisitos que precisam de ser testados.
Os testes da cláusula  C.8.3 são disponibilizados para apoiar as recomendações da cláusula 8.3. Eles devem ser aplicados se as recomendações da cláusula 8.3 forem seguidas. No entanto, os testes na cláusula  C.8.3 não fazem parte dos requisitos de conformidade e não são exigidos em relatórios de conformidade.

#### C.8.3.2	Piso desimpedido ou sem desnível
##### C.8.3.2.1	Alterações de nível
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. Há uma alteração do nível de piso que seja parte integrante da TIC.
Procedimento     |1. Verificar que a mudança de nível contém uma rampa com inclinação inferior a 1:48.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. Há uma alteração do nível de piso que seja parte integrante da TIC.<br>2. A alteração do nível de piso é igual ou inferior a 6.4 mm (¼ inch)
Procedimento     |1. Verificar que a mudança de nível é um degrau vertical ou rampa.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. Há uma alteração do nível de piso que seja parte integrante da TIC.<br>2. A alteração do nível de piso é igual ou inferior a 13 mm (½ inch).
Procedimento     |1. Verificar que a rampa tem uma inclinação inferior a 1:2.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

##### C.8.3.2.2	Piso desimpedido ou sem desnível
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A área de operação é parte integrante da TIC.
Procedimento     |1. Verificar que a área de operação é um retângulo com dimensão mínima num dos lados de 760 mm (30 inches).<br>2. Verificar que a área de operação é um retângulo com dimensão mínima no outro lado de 1 220 mm (48 inches).
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

#### C.8.3.2.3 Aproximação
##### C.8.3.2.3.1 Geral
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A área de acesso é parte integrante da TIC.
Procedimento     |1. Verificar que um dos lados completo da área está desobstruído.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

###### C.8.3.2.3.2 Aproximação pela frente
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A área de operação está dentro de um nicho integrante da TIC.<br>2. O nicho tem profundidade superior a 610 mm.<br>3. É necessária uma aproximação pela frente.
Procedimento     |1. Verificar que a largura do espaço de acesso é superior a 915 mm.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

###### C.8.3.2.3.3 Aproximação paralela
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A área de operação está dentro de um nicho integrante da TIC.<br>2. O nicho tem profundidade superior a 380 mm.<br>3. É possível uma aproximação paralela.
Procedimento     |1. Verificar que a largura do espaço de acesso é superior a 1525 mm.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

##### C.8.3.2.4 Largura de folga para joelho e dedos dos pés
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. O espaço por baixo de um obstáculo que é parte integrante da TIC é parte do espaço de acesso.
Procedimento     |1. Verificar que a folga para o joelho deve ser superior a 760 mm.<br>2. Verificar que a folga para o dedo do pé deve ser superior a 760 mm.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

##### C.8.3.2.5 Folga para dedo do pé
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A TIC é suspensa.<br>2. Há um espaço debaixo de um obstáculo que é parte integrante da TIC que é inferior a 230 mm acima do chão.
Procedimento     |1. Verificar que a folga para o dedo do pé não ultrapassa mais do que 635mm sob o obstáculo.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A TIC é suspensa.<br>2. Há um espaço debaixo de um obstáculo que é parte integrante da TIC que é inferior a 230 mm acima do chão.
Procedimento     |1. Verificar que a folga para o dedo do pé se extende mais do que 430 mm sob todo o obstáculo.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A TIC é suspensa.<br>2. Há um espaço debaixo de um obstáculo que é parte integrante da TIC que é inferior a 230 mm acima do chão.
Procedimento     |1. Verificar que a folga para o dedo do pé não ultrapassa mais do que 635mm sob o obstáculo.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A TIC é suspensa.<br>2. Há um espaço debaixo de um obstáculo que é parte integrante da TIC que é inferior a 230 mm acima do chão.
Procedimento     |1. Verificar que a folga para o dedo do pé se extende a mais do que 150mm sob o obstáculo.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

##### C.8.3.2.6	Folga para o joelho
a)
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. Há um obstáculo que é parte integrante de uma TIC. <br>2. O obstáculo está entre 230 mm e 685 mm acima do chão.
Procedimento     |1. Verificar que existe uma folga inferior a 635 mm, a uma altura de 230 mm.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.
b)
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. Há um obstáculo que é parte integrante de uma TIC. <br>2. O obstáculo está entre 230 mm e 685 mm acima do chão.
Procedimento     |1. Verificar que existe uma folga superior a 285 mm, a uma altura de 230 mm.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.
c)
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. Há um obstáculo que é parte integrante de uma TIC. <br>2. O obstáculo está entre 230 mm e 685 mm acima do chão.
Procedimento     |1. Verificar que existe uma folga superior a 205 mm, a uma altura de 685 mm.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.
d)
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. Há um obstáculo que é parte integrante de uma TIC. <br>2. O obstáculo está entre 230 mm e 685 mm acima do chão.
Procedimento     |1. Verificar que a redução em profundidade da folga não é superior a 25 mm para cada 150 mm de altura.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

#### C.8.3.3 Amplitude de alcance da TIC

##### C.8.3.3.1 Alcance para a frente
###### C.8.3.3.1.1 Desobstrução do alcance para a frente elevado 
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. O espaço de acesso é parte integrante da TIC. <br>2. Há um acesso desobstruído para os controlos.
Procedimento     |1. Verificar que os controlos essenciais estão localizados a uma altura não superior a 1 220 mm acima do piso do espaço de acesso.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

###### C.8.3.3.1.2 Desobstrução do alcance para a frente baixo 
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. O espaço de acesso é parte integrante da TIC. <br>2. Há um acesso desobstruído para os controlos.
Procedimento     |1. Verificar que os controlos essenciais estão localizados a uma altura não inferior a 380 mm acima do piso do espaço de acesso.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

###### C.8.3.3.1.3 Alcance obstruído
####### C.8.3.3.1.3.1	Espaço de piso desimpedido
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. O espaço de acesso é parte integrante da TIC. <br>2. Existe uma obstrução que é parte integrante da TIC.
Procedimento     |1. Verificar que existe um espaço de piso desimpedido que se estenda além do elemento obstrutivo, por uma distância não inferior à profundidade de alcance além da obstrução.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

####### C.8.3.3.1.3.2	Obstrução (< 510 mm) do alcance para a frente 
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. O espaço de acesso é parte integrante da TIC. <br>2. Existe uma obstrução que é parte integrante da TIC.<br>3. A obstrução é inferior a 510 mm.
Procedimento     |1. Verificar que o alcance para a frente de todos os controlos essenciais não é superior a 1220 mm acima do nível de contacto de chão com a TIC.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

####### C.8.3.3.1.3.3	Obstrução (< 635 mm) do alcance para a frente 
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. O espaço de acesso é parte integrante da TIC. <br>2. Existe uma obstrução que é parte integrante da TIC.<br>3. A obstrução está entre 510 mm e 635 mm.
Procedimento     |1. Verificar que o alcance para a frente de todos os controlos essenciais não é superior a 1220 mm acima do nível de contacto de chão com a TIC.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

##### C.8.3.3.2 Alcance lateral
###### C.8.3.3.2.1 Desobstrução de alcance lateral elevado 
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. O espaço de acesso é parte integrante da TIC. <br>2. É possível uma aproximação paralela.<br>3. O alcance lateral está desobstruído ou está obstruído por uma parte inferior a 255 mm .
Procedimento     |1. Verificar que a altura do controlo essencial mais alto é inferior ou igual a 1220 mm acima do piso do espaço de acesso.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

###### C.8.3.3.2.2 Desobstrução de alcance lateral baixo
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. O espaço de acesso é parte integrante da TIC. <br>2. É possível uma aproximação paralela.<br>3. O alcance lateral está desobstruído ou está obstruído por uma parte inferior a 255 mm .
Procedimento     |1. Verificar que a altura do controlo essencial mais baixo é superior ou igual a 380 mm acima do piso do espaço de acesso.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

###### C.8.3.3.2.3 Obstrução de alcance lateral
####### C.8.3.3.2.3.1 Obstrução (≤ 255 mm) de alcance lateral
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. O espaço de acesso é parte integrante da TIC. <br>2. É possível uma aproximação paralela.<br>3. Existe uma obstrução que é parte integrante da TIC e com altura inferior a 865 mm.<br>3. O alcance lateral está desobstruído ou está obstruído por uma parte inferior a 255 mm .
Procedimento     |1. Verificar que a altura do controlo essencial mais alto não é superior a 1220 mm acima do piso do espaço de acesso.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

####### C.8.3.3.2.3.2 Obstrução (≤ 610 mm) de alcance lateral
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. O espaço de acesso é parte integrante da TIC. <br>2. É possível uma aproximação paralela.<br>3. Existe uma obstrução que é parte integrante da TIC e com altura inferior a 865 mm.<br>3. O alcance lateral está desobstruído ou está obstruído por uma parte superior a 255 mm e inferior a 610 mm.
Procedimento     |1. Verificar que a altura do controlo essencial mais alto não é superior a 1170 mm acima do piso do espaço de acesso.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

#### C.8.3.4 Visibilidade
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. A área de operação é parte integrante da TIC. <br>2. É fornecido um ecrã de visualização.
Procedimento     |1. Verificar que a informação no ecrã é legível a partir de um ponto localizado a 1015 mm acima do centro do piso da área de operação.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

#### C.8.3.5 Instruções de instalação
Tipo de avaliação|Inspeção baseada em dados medidos
-----------------|--------
Pré-condições    |1. Pretende-se que a TIC seja instalada.
Procedimento     |1. Verificar que as instruções são disponibilizadas tal que expressem um método para instalar a TIC de forma a garantir que as dimensões dos espaços integrantes da TIC estão em conformidade com as cláusulas 8.3.2 a 8.3.4.
Resultado        |Se a verificação 1 for verdadeira, então esta recomendação é seguida.

### C.8.4 Partes operáveis mecanicamente
#### C.8.4.1 Teclas numéricas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem teclas numéricas físicas, no formato de teclado numérico de 12 teclas do telefone.
Procedimento     |1. Verificar que o número 5 é distinguível das outras teclas, por indicador tátil.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.8.4.2.1 Operação de partes mecânicas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem partes operáveis que requerem agarrar, prensar ou torcer o pulso para serem operadas.
Procedimento     |1. Verificar que é fornecido um meio de operação alternativo e acessível, que não requer as referidas ações.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.8.4.2.2 Meios de operação de partes mecânicas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem partes operáveis que requerem a aplicação de uma força superior a 22,2 N para serem operadas.
Procedimento     |1. Verificar que é fornecido um meio de operação alternativo e acessível, que permita operar com uma força inferior a 22,2 N.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.8.4.2.3 Chaves, bilhetes e cartões
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC fornece chaves, bilhetes ou cartões, e a sua orientação é importante para a sua utilização.
Procedimento     |1. Verificar que as chaves, bilhetes ou cartões contêm um meio tátil de identificação da sua orientação.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.8.5 Indicação tátil em modo de fala
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é desenhada para utilização partilhada.<br> 2. É disponibilizada uma saída de fala.
Procedimento     |1. Verificar que existe uma indicação tátil que permite a iniciação do modo de fala.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

## C.9 Web		
### C.9.0 Geral (informativo)
A Cláusula 9.0 é informativa e não contém requisitos que precisem de testes.

### C.9.1 Percetível
#### C.9.1.1 Alternativas de texto
##### C.9.1.1.1 Conteúdo não textual
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em WCAG 2.1 Success Criterion 1.1.1 Non-text content.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.9.1.2 Conteúdo multimédia temporal
##### C.9.1.2.1 Conteúdo só de áudio e só de vídeo (pré-gravado)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.2.1 Audio-only and Video-only (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.2.2	Legendas (pré-gravado)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.2.2 Captions (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.2.3	Audiodescrição ou Alternativa em Multimédia (pré-gravado)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.2.3 Audio Description or Media Alternative (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.2.4	Legendas (em direto)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.2.4 Captions (Live).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.2.5	Audiodescrição (pré-gravado)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.2.5 Audio Description (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.9.1.3	Adaptável
##### C.9.1.3.1	Informações e Relações
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.3.1 Info and Relationships.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.3.2	Sequência com Significação
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.3.2 Meaningful Sequence.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.3.3	Características Sensoriais
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.3.3 Sensory Characteristics.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.3.4	Orientação
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.3.4 Orientation.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.3.5	Identificação do propósito de entrada
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.3.5 Identify Input Purpose.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.9.1.4	Distinguível

##### C.9.1.4.1	Utilização da Cor
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.4.1 Use of Color.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.4.2	Controlo de Áudio
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.4.2 Audio Control.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.4.3	Contraste (Mínimo)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.4.3 Contrast (Minimum).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.4.4	Redimensionar texto
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.4.4 Resize text.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.4.5	Imagens de Texto
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.4.5 Images of Text.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.4.6	Void
##### C.9.1.4.7	Void
##### C.9.1.4.8	Void
##### C.9.1.4.9	Void
##### C.9.1.4.10	Reflow
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.4.10 Reflow.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.4.11 Contraste não-textual
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.4.11 Non-text Contrast.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.4.12 Espaçamento do texto
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.4.12 Text spacing.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.1.4.13	Conteúdo em hover ou foco
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 1.4.13 Content on Hover or Focus.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.9.2 Operável
#### C.9.2.1 Acessível por Teclado
##### C.9.2.1.1	Teclado
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.1.1 Keyboard.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.1.2	Sem Bloqueio do Teclado
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.1.2 No Keyboard Trap.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.1.3	Void
##### C.9.2.1.4	Atalhos de teclas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.1.4 Character Key Shortcuts.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.9.2.2	Tempo Suficiente
##### C.9.2.2.1	Tempo Ajustável
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.2.1 Timing Adjustable.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.2.2	Colocar em Pausa, Parar, Ocultar
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.2.2 Pause, Stop, Hide.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.9.2.3	Convulsões e reações físicas
##### C.9.2.3.1	Três Flashes ou Abaixo do Limite
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.3.1 Three Flashes or Below Threshold.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.9.2.4	Navegável
##### C.9.2.4.1	Ignorar Blocos
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.4.1 Bypass Blocks.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.4.2	Página com Título
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.4.2 Page Titled.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.4.3	Ordem do Foco
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.4.3 Focus Order.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.4.4	Finalidade do Link (Em contexto)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.4.4 Link Purpose (In Context).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.4.5	Várias Formas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.4.5 Multiple Ways.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.4.6	Cabeçalhos e Etiquetas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.4.6 Headings and Labels.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.4.7	Foco Visível
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.4.7 Focus Visible.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.9.2.5	Modalidades de entrada
##### C.9.2.5.1	Gestos de ponteiro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.5.1 Pointer Gestures.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.5.2	Cancelamento de ponteiro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.5.2 Pointer Cancellation.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.5.3	Legenda no nome
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.5.3 Label in Name.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.2.5.4	Atuação por movimento
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 2.5.4 Motion Actuation.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.9.3	Compreensível
#### C.9.3.1	Legível
##### C.9.3.1.1	Idioma da página
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 3.1.1 Language of Page.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.3.1.2	Idioma de Partes
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 3.1.2 Language of Parts.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.9.3.2	Previsível
##### C.9.3.2.1	Ao receber o Foco
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 3.2.1 On Focus.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.3.2.2	Ao entrar num campo de edição (input)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 3.2.2 On Input.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.3.2.3	Consistência de Navegação
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 3.2.3 Consistent Navigation.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.3.2.4	Consistência de Identificação
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 3.2.4 Consistent Identification.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.9.3.3	Assistência na Inserção de Dados
##### C.9.3.3.1	Identificação de Erro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 3.3.1 Error Identification.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.3.3.2	Legendas ou Instruções
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 3.3.2 Labels or Instructions.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.3.3.3	Sugestão para eliminar o Erro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 3.3.3 Error Suggestion.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.3.3.4	Prevenção de Erros (Legais, Financeiros, Dados)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 3.3.4 Error Prevention (Legal, Financial, Data).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.9.4	Robusto
#### C.9.4.1	Compatível
##### C.9.4.1.1	Análise sintática (parsing)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 4.1.1 Parsing.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.4.1.2	Nome, Função, Valor
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 4.1.2 Name, Role, Value.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.9.4.1.3	Mensagens de estado
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web não falha em satisfazer WCAG 2.1 Success Criterion 4.1.3 Status Messages.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.9.5 Requisitos de conformidade WCAG
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma página web.
Procedimento     |1. Verificar que a página web satisfaz a conformidade com o requisito WCAG 2.1 [5] "1: Conformance level" no nível AA.<br>2. Verificar que a página web satisfaz a conformidade com o requisito WCAG 2.1 [5] "2: Full pages".<br>3. Verificar que a página web satisfaz a conformidade com o requisito WCAG 2.1 [5]  "3: Complete processes".<br>4. Verificar que a página web satisfaz a conformidade com o requisito WCAG 2.1 [5]  "4: Only Accessibility-Supported Ways of Using Technologies".<br>5. Verificar que a página web satisfaz a conformidade com o requisito WCAG 2.1 [5]  "5: Non-interference".
Resultado        |Passa: Todas as verificações são verdadeiras. <br>Falha: Todas as verificações são falsas.

### C.10 Documentos não-Web 
#### C.10.0 Geral
A Cláusula 10.0 é apenas sugestiva e não contém requisitos que precisem de testes.

### C.10.1 Percetível
#### C.10.1.1 Alternativas de Texto
##### C.10.1.1.1 Conteúdo Não-textual
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os Critérios de Sucesso WCAG 2.1   1.1.1 Conteúdo Não Textual.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.10.1.2	Conteúdo multimédia temporal
##### C.10.1.2.1	Conteúdo só de áudio e só de vídeo (pré-gravado)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.1 Audio-only and Video-only (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.10.1.2.2	Legendas (pré-gravado)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.2 Captions (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.10.1.2.3	Audiodescrição ou Alternativa em Multimédia (pré-gravado)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.3 Audio Description or Media Alternative (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.10.1.2.4	Legendas (em direto)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.4 Captions (Live).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.10.1.2.5	Áudio-descrição (pré-gravado)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.5 Audio Description (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
#### C.10.1.3	Adaptável
##### C.10.1.3.1	Informação e Relações

Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.3.1 Info and Relationships.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.3.2	Sequência com significação
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.3.2 Meaningful Sequence.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.3.3	Características sensoriais
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.3.3 Sensory Characteristics.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.3.4	Orientação
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.3.4 Orientation.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.3.5	Identificação do propósito de entrada
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.3.5 Identify Input Purpose.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
#### C.10.1.4	Distinguível
##### C.10.1.4.1	Utilização de cor
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.1 Use of Color.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.4.2	Controlo de áudio
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.1.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.4.3	Contraste (mínimo)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.3 Contrast (Minimum).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.4.4	Redimensionar o Texto
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.4 Resize Text.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.4.5	Imagens de texto
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.5 Images of Text.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.4.6	Void
##### C.10.1.4.7	Void
##### C.10.1.4.8	Void
##### C.10.1.4.9	Void
##### C.10.1.4.10	Reflow
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.2.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.4.11	Contraste não-textual
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.11 Non-text Contrast.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.4.12	Espaçamento de Texto
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os os critérios de sucesso WCAG 2.1 Success Criterion 1.4.12 Text spacing.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.1.4.13	Conteúdo hover ou de foco
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os os critérios de sucesso WCAG 2.1 Success Criterion 1.4.13 Content on Hover or Focus.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
### C.10.2	Operável
#### C.10.2.1	Acessível por Teclado
##### C.10.2.1.1	Teclado
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
Quando a TIC é um documento não-Web, este deve satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 2.1.1 Keyboard.
##### C.10.2.1.2	Sem bloqueio de teclado
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.3.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.2.1.3	Void
##### C.10.2.1.4	Atalhos de tecla de caracter
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 2.1.4 Character Key Shortcuts. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
#### C.10.2.2	Tempo suficiente
##### C.10.2.2.1	Tempo ajustável
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.4.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.10.2.2.2	Colocar em Pausa, Parar, Ocultar
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.5.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
#### C.10.2.3	Convulsões e reações físicas
##### C.10.2.3.1	Três Flashes ou Abaixo do Limite
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.6.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
#### C.10.2.4	Navegável
##### C.10.2.4.1	Void
##### C.10.2.4.2	Documento com título
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.7.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.2.4.3	Ordem do foco
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.8.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.2.4.4	Finalidade do Link (Em contexto)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 2.4.4 Link Purpose (In Context).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.2.4.5	Void
##### C.10.2.4.6	Títulos e legendas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 2.4.6 Headings and Labels.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.2.4.7	Foco visível
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 2.4.7 Focus Visible.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
#### C.10.2.5	Modos de Entrada
##### C.10.2.5.1	Gestos de ponteiro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.9.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.2.5.2	Cancelamento de ponteiro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.10.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.2.5.3	Legenda no nome
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 2.5.3 Label in Name.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.2.5.4	Atuação por movimento
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 2.5.4 Motion Actuation.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
### C.10.3	Compreensível
#### C.10.3.1	Legível
##### C.10.3.1.1	Idioma da página
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.11.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.3.1.2	Partes do idioma
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.12.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
#### C.10.3.2	Previsível
##### C.10.3.2.1	Em foco
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso the WCAG 2.1 Success Criterion 3.2.1 On Focus.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.3.2.2	Em entrada
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso the WCAG 2.1 Success Criterion 3.2.2 On Input.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.3.2.3	Void
##### C.10.3.2.4	Void

#### C.10.3.3	Assistência de Entrada
##### C.10.3.3.1	Identificação de erro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso the WCAG 2.1 Success Criterion 3.3.1 Error Identification.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.3.3.2	Legendas e instruções
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso em WCAG 2.1 Success Criterion 3.3.2 Labels or Instructions.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.3.3.3	Sugestão de erro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso em WCAG 2.1 Success Criterion 3.3.3 Error Suggestion.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.3.3.4	Prevenção de Erros (Legais, Financeiros, Dados)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.13.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
### C.10.4	Robusto
#### C.10.4.1	Compatível
##### C.10.4.1.1	Análise sintática
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.14.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.4.1.2	Nome, função, valor 
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um documento não-Web.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 10.15.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
##### C.10.4.1.3	Void
### C.10.5 Posição da Legenda
A Cláusula 10.5 não contém requisitos que precisem de testes.

### C.10.6 Tempo de audio-descrição
A Cláusula 10.6 não contém requisitos que precisem de testes.

## C.11	Software

### C.11.0	Geral
A Cláusula 11.0 é apenas sugestiva e não contém requisitos que precisem de testes.
### C.11.1	Percetível
#### C.11.1.1	Alternativas em texto
##### C.11.1.1.1	Conteúdo não textual
###### C.11.1.1.1.1	Conteúdo não textual (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software suporta o acesso a tecnologias de apoio para leitura de ecrã.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso em seguir WCAG 2.1 Success Criterion 1.1.1 Non-text Content.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.1.1.1.2	Conteúdo não textual (funcionalidade fechada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software está fechada ao acesso a tecnologias de apoio para leitura de ecrã.<br>3. Há conteúdo não-textual que é apresentado via saída de fala.
Procedimento     |1. Verificar que a saída de fala é fornecida como alternativa ao conteúdo não textual.<br>2. Verificar que o conteúdo não textual não é puramente decorativo.<br>3. Verificar que o conteúdo não textual não é usado apenas para formatação visual.<br>4. Verificar que a saída de fala segue a orientação para "texto alternativo" descrito em WCAG 2.1 Success Criterion 1.1.1 Non-text Content.
Resultado        |Passa: Todas as verificações são verdadeiras ou (1 e 2 são falsas) ou (1 e 3 são falsas).<br>Falha: Verifica (1 é verdadeira e 2 é falsa) ou (1 é verdadeira e 3 é falsa) ou (1 e 2 e 3 são verdadeiras e 4 é falsa).

#### C.11.1.2	Conteúdo multimédia temporal
##### C.11.1.2.1	Conteúdo só de áudio e só de vídeo (pré-gravado)
###### C.11.1.2.1.1	Conteúdo só de áudio e só de vídeo (pré-gravado – funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software suporta o acesso a tecnologias de apoio para leitura de ecrã.<br>3. A informação auditiva pré-gravada não é necessária para permitir a utilização de funções fechadas da TIC.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.1 Audio-only and Video-only (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.1.2.1.2	Conteúdo só de áudio e só de vídeo (pré-gravado - functionalidade fechada)
####### C.11.1.2.1.2.1 Conteúdo só de áudio (pré-gravado - functionalidade fechada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software suporta o acesso a tecnologias de apoio para leitura de ecrã.<br>3. A informação auditiva pré-gravada é necessária para permitir a utilização de funções fechadas da TIC.
Procedimento     |1. Verificar que a saída de fala apresenta informação equivalente para a saída auditiva pré-gravada.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

####### C.11.1.2.1.2.2 Conteúdo só de vídeo (pré-gravado - functionalidade fechada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software suporta o acesso a tecnologias de apoio para leitura de ecrã.<br>3. A informação de vídeo pré-gravada é necessária para permitir a utilização de funções fechadas da TIC.<br>4. É fornecida saída de fala como acesso não-visual a conteúdo textual exibido em funcionalidade fechada.
Procedimento     |1. Verificar que a saída de fala apresenta informação equivalente para o conteúdo de vídeo pré-gravado.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.2.2 Legendas (pré-gravadas)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.2 Captions (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.2.3	Áudiodescrição ou alternativa de multimédia (pré-gravado)
###### C.11.1.2.3.1	Áudiodescrição ou alternativa de multimédia (pré-gravado - funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2.O software fornece acesso a tecnologias de apoio para leitura de ecrã.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.3 Audio Description or Media Alternative (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.1.2.3.2	Áudiodescrição ou alternativa de multimédia (pré-gravado - funcionalidade fechada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. É fornecida saída de fala como acesso não-visual a conteúdo textual exibido em funcionalidade fechada.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.2 Captions (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.2.4	Legendas (Em Direto)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.4 Captions (Live).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.2.5	Áudio-descrição (pré-gravada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.2.5 Audio Description (Prerecorded).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.11.1.3	Adaptável
##### C.11.1.3.1 Informações e Relações
###### C.11.1.3.1.1	Informações e Relações (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>A TIC fornece uma interface de utilizador aberta a tecnologias de apoio para leitura de ecrã.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.3.1 Info and Relationships.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.1.3.1.2	Informações e Relações (funcionalidade fechada)
Esta cláusula é apenas informativa, não contém requisitos que precisem de testes.

##### C.11.1.3.2	Sequência com significação
###### C.11.1.3.2.1	Sequência com significação (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>A TIC fornece uma interface de utilizador aberta a tecnologias de apoio para leitura de ecrã.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.3.2 Meaningful Sequence.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.1.3.2.2	Sequência com significação (funcionalidade fechada)
Esta cláusula é apenas informativa, não contém requisitos que precisem de testes.

##### C.11.1.3.3	Características sensoriais
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.3.3 Sensory Characteristics.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.3.4	Orientação
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.3.4 Orientation.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.3.5	Identificação do propósito da entrada
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.3.5 Identify Input Purpose.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.11.1.4	Distinguível
##### C.11.1.4.1	Utilização de cor
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.1 Use of Color.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.4.2	Controlo de áudio
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 11.1.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.4.3	Contraste (mínimo)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.3 Contrast (Minimum).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.4.4	Redimensionar o texto
###### C.11.1.4.4.1	Redimensionar o texto (funcionalidade aberta)
Tipo de avaliação|Inspeção e Medida
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. A TIC suporta o acesso a características de ampliação da plataforma ou de tecnologias de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.4 Resize Text.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.1.4.4.2	Redimensionar o texto (funcionalidade fechada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. A interface de utilizador é fechada a características de ampliação da plataforma ou de tecnologias de apoio.<br>3. O fornecedor especifica uma distância de visualização.
Procedimento     |1. Medir a altura da letra maiúscula 'H'. <br>2. Verificar que subtende um ângulo de, pelo menos, 0.7 graus na distância de visualização indicada.
Resultado        |Passa: A verificação 2 é verdadeira.<br>Falha: A verificação 2 é falsa.

##### C.11.1.4.5	Imagens de Texto
###### C.11.1.4.5.1	Imagens de Texto (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. A TIC fornece uma interface de utilizador que suporta o acesso a tecnologias de apoio para leitura de ecrã.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.5 Images of Text.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.1.4.5.2	Imagens de Texto (funcionalidade fechada)
Esta cláusula é apenas informativa, não contém requisitos que precisem de testes.

##### C.11.1.4.6	Void
##### C.11.1.4.7	Void
##### C.11.1.4.8	Void
##### C.11.1.4.9	Void
##### C.11.1.4.10 Reflow

###### C.11.1.4.10.1	Reflow (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso na Tabela 11.2.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.1.4.10.2	Reflow (funcionalidade fechada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. A interface de utilizador é fechada a características de ampliação da plataforma ou de tecnologias de apoio.<br>3. O fornecedor especifica uma distância de visualização.
Procedimento     |1. Medir a altura da letra maiúscula 'H'. <br>2. Verificar que subtende um ângulo de, pelo menos, 0.7 graus na distância de visualização indicada.
Resultado        |Passa: A verificação 2 é verdadeira.<br>Falha: A verificação 2 é falsa.

##### C.11.1.4.11	Contraste não-Textual
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.11 Non- text Contrast.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.4.12	Espaçamento de Texto
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.12 Text spacing.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.1.4.13	Conteúdo em hover ou foco
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 1.4.13 Content on hover or focus.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

## C.11.2	Operável
### C.11.2.1	Acessível ao Teclado
#### C.11.2.1.1	Teclado
##### C.11.2.1.1.1	Teclado (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software suporta o acesso a teclados ou a interfaces de teclado.
Procedimento     |1. Verificar que a página web não falha em satisfazer os critérios de sucesso WCAG 2.1 Success Criterion 2.1.1 Keyboard.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.2.1.1.2	Teclado (funcionalidade fechada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software suporta o acesso a teclados ou a interfaces de teclado.
Procedimento     |1. Verificar que todas as funcionalidades da interface de utilizador são operáveis sem recurso à visão. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.11.2.1.2	Sem bloqueio de teclado
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.3.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.11.2.1.3	Void
#### C.11.2.1.4	Atalhos de tecla de caracter
##### C.11.2.1.4.1	Atalhos de tecla de caracter (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software suporta o acesso a teclados ou a interfaces de teclado.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 2.1.4 Character Key Shortcuts.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.2.1.4.2	Atalhos de tecla de caracter (funcionalidade fechada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software está fechada a teclados ou a interfaces de teclado.
Procedimento     |1. Verificar que todas as funcionalidades da interface de utilizador são operáveis sem recurso à visão. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.11.2.2	Tempo suficiente
##### C.11.2.2.1	Tempo ajustável
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.4.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.2.2.2	Colocar em Pausa, Parar, Ocultar
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.5.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.11.2.3	Convulsões e reações físicas
##### C.11.2.3.1	Três flashes ou abaixo do limite
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.6.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.11.2.4	Navegável
##### C.11.2.4.1	Void
##### C.11.2.4.2	Void
##### C.11.2.4.3	Ordem do Foco
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.7.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.2.4.4	Finalidade do Link (Em contexto)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 2.4.4 Link Purpose (In Context).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.2.4.5	Void
##### C.11.2.4.6	Títulos e legendas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 2.4.6 Headings and Labels.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.2.4.7	Foco visível
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 2.4.7 Focus Visible.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.11.2.5	Modo de Entrada
##### C.11.2.5.1	Gestos de ponteiro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.8.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.2.5.2	Cancelamento de Ponteiro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.9.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.2.5.3	Legenda no nome
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 2.5.3 Label in Name.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.2.5.4	Atuação por movimento
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 2.5.4 Motion Actuation.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.11.3	Compreensível
#### C.11.3.1	Legível
##### C.11.3.1.1	Idioma do software
###### C.11.3.1.1.1	Idioma do software (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software suporta o acesso a tecnologias de apoio para leitura de ecrã.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.10.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.3.1.1.2	Idioma do software (funcionalidade fechada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software está fechado a tecnologias de apoio para leitura de ecrã.<br>3. É fornecido o retorno auditivo como acesso não visual à funcionalidade fechada.<br>4. A saída de fala não inclui nomes próprios, termos técnicos, palavras de linguagem indeterminada e palavras ou frases que se tornaram parte de vernáculo do texto.<br>5.O conteúdo não é gerado externamente e está sob o controlo do fornecedor de TIC.<br>6. Os idiomas exibidos que podem ser selecionados usando acesso não visual.<br>7. O utilizador não selecionou explicitamente um idioma de fala diferente do idioma do conteúdo exibido.
Procedimento     |1. Verificar que a fala está no mesmo idioma do conteúdo exibido.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.3.1.2	Void

#### C.11.3.2	Previsível
##### C.11.3.2.1	No Foco
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 3.2.1 On Focus.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.3.2.2	Em entrada
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 3.2.2 On Input.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.3.2.3	Void
11.3.2.4	Void

#### C.11.3.3	Assistência na Entrada
##### C.11.3.3.1	Identificação de erro
###### C.11.3.3.1.1	Identificação de erro (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a tecnologias de apoio para leitura de ecrã.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 3.3.1 Error Identification.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.3.3.1.2	Identificação de erro (funcionalidade fechada)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software está fechado a tecnologias de apoio para leitura de ecrã.<br>3. É fornecido o retorno auditivo como acesso não visual à funcionalidade fechada.<br>4. Um erro de entrada é automaticamente detetado.
Procedimento     |1. Verificar que a saída de fala identifica o item que tem erro. <br>2.  Verificar que a saída de fala descreve o item que tem erro. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.3.3.2	Legendas ou instruções
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 3.3.2 Labels or Instructions.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.3.3.3	Sugestão de erro
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso WCAG 2.1 Success Criterion 3.3.3 Error Suggestion.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.3.3.4	Prevenção de Erros (Legais, Financeiros, Dados)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.11.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.11.4	Robusto
#### C.11.4.1	Compatível
##### C.11.4.1.1	Análise sintática
###### C.11.4.1.1.1	Análise sintática (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.12.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.4.1.1.2	Análise sintática (funcionalidade fechada)
Esta cláusula é apenas informativa, não contém requisitos que precisem de testes.


##### C.11.4.1.2 Nome, função, valor
###### C.11.4.1.2.1	Nome, função, valor (funcionalidade aberta)
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é um software não-Web que fornece uma interface de utilizador.<br>2. O software fornece suporte a, pelo menos, uma tecnologia de apoio.
Procedimento     |1. Verificar que a página web não falha em satisfazer o critério de sucesso na Tabela 11.13.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

###### C.11.4.1.2.2	Nome, Função, Valor (funcionalidade fechada)
Esta cláusula é apenas informativa, não contém requisitos que precisem de testes.

##### C.11.4.1.3	Void

### C.11.5	Interoperabilidade com Tecnologias de apoio
#### C.11.5.1	Funcionalidade fechada
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software tem funcionalidade fechada.
Procedimento     |1. Verificar que a funcionalidade fechada está em conformidade com a cláusula 5.1.
Resultado        |Se a verificação for verdadeira, o software não precisa de estar em conformidade com cláusulas de 11.5.2 a 11.5.17.<br>Se a verificação 1 for falsa o software precisa de estar em conformidade com cláusulas de 11.5.2 a 11.5.17

#### C.11.5.2	Serviços de acessibilidade
##### C.11.5.2.1	Plataforma de suporte a serviço de acessibilidade para software que fornece interface de utilizador
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação é uma plataforma.
Procedimento     |1. Verificar que a plataforma de software fornece um conjunto de serviços de plataforma documentados, que permitem ao software que fornece uma interface de utilizador ser executada na plataforma e interoperar com tecnologias de apoio.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.5.2.2	Plataforma de suporte a serviço de acessibilidade para tecnologias de apoio
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação é uma plataforma.
Procedimento     |1. Verificar que a plataforma de software fornece um conjunto de serviços de acessibilidade documentados da plataforma que permite que as tecnologias de apoio interoperem com o software que fornece uma interface utilizador, em execução na plataforma de software.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.5.2.3	Utilização de serviços de acessibilidade
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.
Procedimento     |1. Verificar que o software usa os serviços de acessibilidade documentados da plataforma.<br>2. Verificar que software cumpre os requisitos aplicáveis das cláusulas 11.5.2.5 a 11.5.2.17, enquanto utiliza os serviços de acessibilidade documentados. <br>3. Verificar que software cumpre os requisitos das cláusulas 11.5.2.5 a 11.5.2.17, enquanto utiliza os serviços de acessibilidade documentados e outros serviços documentados.
Resultado        |Passa: A verificação 1 é verdadeira e a verificação 2 ou a 3 é verdadeira.<br>Falha: A verificação 1 ou a verificação 3 é falsa.

##### C.11.5.2.4	Tecnologia de apoio
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é uma tecnologia de apoio.
Procedimento     |1. Verificar que a tecnologia de apoio usa os serviços de acessibilidade documentados.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.11.5.2.5	Informação de objeto
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.
Procedimento     |1. Verificar que a função do elemento interface de utilizador é programaticamente determinável por tecnologias de apoio.<br>2. Verificar que o(s) estado(s) do elemento interface de utilizador é programaticamente determinável por tecnologias de apoio. <br>3. Verificar que o limite do elemento interface de utilizador é programaticamente determinável por tecnologias de apoio. <br>4. Verificar que o nome do elemento interface de utilizador é programaticamente determinável por tecnologias de apoio. <br>5. Verificar que a descrição do elemento interface de utilizador é programaticamente determinável por tecnologias de apoio. 
Resultado        |Passa: As verificações 1,2,3,4 e 5 são verdadeiras.<br>Falha: A verificação 1,2,3,4 ou 5 é falsa.

##### C.11.5.2.6	Linha, coluna e cabeçalhos
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.<br>2. Há tabelas de dados na interface de utilizador.
Procedimento     |1. Selecionar a tabela de dados na qual os testes serão feitos.<br>2. Verificar que cada linha de células é programaticamente determinável por tecnologias de apoio.<br>3. Verificar que cada coluna de células é programaticamente determinável por tecnologias de apoio.<br>4. Verificar que cada cabeçalho de linha, se existir, de células é programaticamente determinável por tecnologias de apoio.<br>5. Verificar que cada cabeçalho de coluna de células, se existir, é programaticamente determinável por tecnologias de apoio.
Resultado        |Passa: As verificações 2,3,4 e 5 são verdadeiras.<br>Falha: A verificação 2,3,4 ou 5 é falsa.

##### C.11.5.2.7	Valores
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.<br>2. Há elementos na interface de utilizador que podem ter valores.
Procedimento     |1. Selecionar um elemento da interface de utilizador que pode ter um valor.<br>2. Verificar que o valor é programaticamente determinável por tecnologias de apoio.<br>3. Se a interface de utilizador disponibiliza informação sobre uma amplitude de valores, verificar que o valor mínimo é programaticamente determinável por tecnologias de apoio.<br>3. Se a interface de utilizador disponibiliza informação sobre uma amplitude de valores, verificar que o valor máximo é programaticamente determinável por tecnologias de apoio.
Resultado        |Passa: As verificações 2,3 e 4 são verdadeiras.<br>Falha: A verificação 2,3 ou 4 é falsa.

##### C.11.5.2.8	**Relação de Etiquetas
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.<br>2. Há componentes na interface de utilizador que são etiquetas de outros componentes da interface de utilizador.
Procedimento     |1. Obter a informação de cada elemento da interface de utilizador.<br>2. Verificar que a informação do componente de interface de utilizador inclui a relação com o componente de interface de utilizador que é a sua etiqueta, caso exista, e que esta relação é programaticamente determinável por tecnologias de apoio.<br>3. Verificar que a informação do componente de interface de utilizador inclui a relação com o componente de interface de utilizador do qual é etiqueta, caso exista, e que esta relação é programaticamente determinável por tecnologias de apoio.
Resultado        |Passa: As verificações 2 e 3 são verdadeiras.<br>Falha: A verificação 2 ou 3 é falsa.

##### C.11.5.2.9	**Parent-child relationships
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.<br>2. Há componentes na interface de utilizador que são legendas de outros componentes da interface de utilizador.
Procedimento     |1. Para componentes de interface de utilizador que têm um **parent, verificar que a informação do componente de interface de utilizador inclui a relação com o componente de interface de utilizador que é seu **parent.<br>2. Verificar que os componentes de interface de utilizador que são **parent do componente de interface de utilizador selecionado na verificação 1, incluem na sua informação a relação com os componentes de interface de utilizador que são **children, e que esta relação é programaticamente determinável por tecnologias de apoio.<br>3. Para componentes de interface de utilizador que são um **parent de outros componentes, verificar que a informação do componente de interface de utilizador inclui a relação com os componentes de interface de utilizador que são seus **children, e que estas relações são programaticamente determináveis por tecnologias de apoio.<br>4. Verificar que os componentes de interface de utilizador que são **child do componente de interface de utilizador selecionado na verificação 3, incluem na sua informação a relação com os componentes de interface de utilizador que são **parent, e que esta relação é programaticamente determinável por tecnologias de apoio.
Resultado        |Passa: As verificações (1 ou 2) e (3 ou 4) são verdadeiras.<br>Falha: As verificações (1 e 2) ou (3 e 4) são falsas.
NOTA: Para este requisito, é suficiente que uma das duas direções de uma relação parent-child seja programaticamente determinável. Esta é a razão para as verificações estarem em pares e o teste passar se um dos membros do par for verdadeiro.

##### C.11.5.2.10 Texto
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador. <br>2. Há texto que é sintetizado para o ecrã.
Procedimento     |1. Para instâncias de texto que são sintetizadas para o ecrã, verificar que a informação do texto inclui o conteúdo do texto e que esta informação é programaticamente determinável por tecnologias de apoio.<br>2. Para instâncias de texto que são sintetizadas para o ecrã, verificar que a informação do texto inclui os seus atributos e que esta informação é programaticamente determinável por tecnologias de apoio.<br>3. Para instâncias de texto que são sintetizadas para o ecrã, verificar que a informação do texto inclui os seus limites e que esta informação é programaticamente determinável por tecnologias de apoio.
Resultado        |Passa: As verificações 1,2 e 3 são verdadeiras.<br>Falha: A verificação 1 ou 2 ou 3 é falsa.

##### C.11.5.2.11 Lista de ações disponíveis
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.<br>2. Há componentes de interface de utilizador que têm ações que podem ser executadas pelo utilizador.
Procedimento     |1. Verificar que a informação do componente de interface de utilizador inclui a lista das ações que podem ser executadas.<br>2. Verificar que esta lista é programaticamente determinável por tecnologias de apoio.<br>2. Para instâncias de texto que são sintetizadas para o ecrã, verificar que a informação do texto inclui os seus atributos e que esta informação é programaticamente determinável por tecnologias de apoio.<br>3. Para instâncias de texto que são sintetizadas para o ecrã, verificar que a informação do texto inclui os seus limites e que esta informação é programaticamente determinável por tecnologias de apoio.
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: A verificação 1 ou 2 é falsa.

##### C.11.5.2.12	Execução de ações disponíveis
Tipo de avaliação|Inspeção e Teste
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.<br>2. Há componentes de interface de utilizador que têm ações que podem ser executadas pelo utilizador.<br>3. Os requisitos de segurança permite à tecnologia de apoio executar programaticamente as ações do utilizador.
Procedimento     |1. Verificar que a informação do componente de interface de utilizador inclui a lista das ações que podem ser executadas pela tecnologia de apoio, conforme 11.5.2.11.<br>2. Verificar que todas as ações da lista podem ser executadas com suscesso por tecnologias de apoio.
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: A verificação 1 ou 2 é falsa.

##### C.11.5.2.13	Registo do foco e dos atributos de seleção
Tipo de avaliação|Inspeção e Teste
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.<br>2. Há componentes de interface de utilizador que permitem edição de texto.
Procedimento     |1. Verificar que a informação do componente de interface de utilizador inclui mecanismos de acompanhar o foco, o ponto de inserção de texto e os atributos de seleção.<br>2. Verificar que esta informação é programaticamente determinável por tecnologias de apoio.<br>3. Ativar os mecanismos de acompanhamento. <br>4. Como utilizador, usar as funcionalidades de edição de texto do software a ser avaliado.<br>5. Verificar que o acompanhamento do foco, ponto de inserção de texto e atributos do texto funciona. 
Resultado        |Passa: As verificações 2 e 5 são verdadeiras.<br>Falha: A verificação 1 ou 5 é falsa.

##### C.11.5.2.14	Modificação do foco e atributos de seleção
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.<br>2. Há componentes de interface de utilizador que podem receber o foco ou que permitem edição de texto.<br>3. Os requisitos de segurança permitem que a plataforma de software modifique programaticamente o foco, ponto de inserção de texto e atributos de seleção de componentes de interface de utilizador.
Procedimento     |1. Para componentes de interface de utilizador que podem receber o foco e em que o foco pode ser modificado por um utilizador sem recurso a uma tecnologia de apoio, verificar que o foco pode ser programaticamente determinável por tecnologias de apoio.<br>2. Para componentes de interface de utilizador que permitem edição de texto por um utilizador sem recurso a uma tecnologia de apoio, verificar que o ponto de inserção de texto pode ser programaticamente determinável por tecnologias de apoio.<br>3. Para componentes de interface de utilizador que permitem edição de texto, verificar que os atributos de seleção podem ser programaticamente determináveis por tecnologias de apoio.
Resultado        |Passa: Todas as verificações são verdadeiras.<br>Falha: Uma das verificações é falsa.

##### C.11.5.2.15	Notificação de alterações
Tipo de avaliação|Inspeção e Teste
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.
Procedimento     |1. Ativar notificações de alterações a componentes de interface de utilizador.<br>2. Verificar que as notificações sobre alterações na informação do objeto (função, estado, limites, nome e descrição) são enviadas para tecnologias de apoio, se esta informação for alterada no software.<br>3. Verificar que as notificações sobre alterações na coluna, linha e cabeçalhos de tabelas de dados são enviadas para tecnologias de apoio, se esta informação for alterada no software.<br>4. Verificar que as notificações sobre alterações nos valores (valores atual, mínimo e máximo) são enviadas para tecnologias de apoio, se esta informação for alterada no software.<br>5. Verificar que as notificações sobre alterações nas relações de etiquetas**label são enviadas para tecnologias de apoio, se esta informação for alterada no software.<br>6. Verificar que as notificações sobre alterações nas relações **parent-child são enviadas para tecnologias de apoio, se esta informação for alterada no software.<br>7. Verificar que as notificações sobre alterações no texto (conteúdos, atributos e limites do texto no ecrã) são enviadas para tecnologias de apoio, se esta informação for alterada no software.<br>8. Verificar que as notificações sobre alterações na lista de ações disponíveis são enviadas para tecnologias de apoio, se esta informação for alterada no software.<br>9. Verificar que as notificações sobre alterações no foco, ponto de inserção de texto e atributos de seleção são enviadas para tecnologias de apoio, se esta informação for alterada no software.
Resultado        |Passa: As verificações 2,3,4,5,6,7,8 e 9 são verdadeiras.<br>Falha: Uma das verificações 2,3,4,5,6,7,8 ou 9 é falsa.

##### C.11.5.2.16	Modificações de estados e propriedades
Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.<br>2. Há componentes de interface de utilizador cujo estado ou propriedades podem ser modificados pelo utilizador sem o uso de tecnologias de apoio.<br>3. Os requisitos de segurança permitem que a plataforma de software modifique programaticamente o estado e propriedades de componentes de interface de utilizador.
Procedimento     |1. Verificar que o estado dos componentes de interface de utilizador, cujo estado pode ser modificado por um utilizador sem recurso a tecnologias de apoio, pode ser programaticamente modificados por tecnologias de apoio.<br>2. Verificar que as propriedades dos componentes de interface de utilizador, cujas propriedades podem ser modificadas por um utilizador sem recurso a tecnologias de apoio, pode ser programaticamente modificados por tecnologias de apoio.
Resultado        |Passa: Todas as verificações são verdadeiras.<br>Falha: Uma das verificações é falsa.

##### C.11.5.2.17	Modificações de valores e texto
Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. O software em avaliação fornece uma interface de utilizador.<br>2. Há componentes de interface de utilizador cujos valores ou texto podem ser modificados pelo utilizador sem o uso de tecnologias de apoio.<br>3. Os requisitos de segurança permitem que a plataforma de software modifique programaticamente o valor e texto das componentes de interface de utilizador.
Procedimento     |1. Verificar que o estado dos componentes de interface de utilizador, cujos valores podem ser modificados por um utilizador sem recurso a tecnologias de apoio, pode ser programaticamente modificados por tecnologias de apoio.<br>2. Verificar que o texto dos componentes de interface de utilizador, cujo texto pode ser modificado por um utilizador sem recurso a tecnologias de apoio, pode ser programaticamente modificados por tecnologias de apoio.
Resultado        |Passa: Todas as verificações são verdadeiras.<br>Falha: Uma das verificações é falsa.


## C.11.6	Documentação sobre utilização de acessibilidade
### C.11.6.1	Controlo do utilizador sobre as características de acessibilidade
Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. Há características da plataforma que estão definidas na documentação da plataforma como características de acessibilidade para o utilizador.
Procedimento     |1. Verificar que a plataforma fornece ao utilizador modos de operação suficientes para controlar as características da plataforma, tal que estejam definidos na documentação da plataforma como características de acessibilidade para os utilizadores, se possível.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.11.6.2 Sem disrupção nas funcionalidades de acessibilidade 
Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. Há características da plataforma que estão definidas na documentação da plataforma como características de acessibilidade.
Procedimento     |1. Verificar se o software que fornece uma interface de utilizador quebra a operação normal das características de acessibilidade da plataforma.<br>2. Verificar se a quebra foi requisitada ou confirmada pelo utilizador.
Resultado        |Passa: A verificação 1 é falsa ou ambas são verdadeiras.<br>Falha: A verificação 1 é verdadeira e a 2 é falsa.

## C.11.7 Preferências do Utilizador
Tipo de avaliação|Inspeção e Teste
-----------------|--------
Pré-condições    |1. O software fornece uma interface de utilizador.
Procedimento     |1. Verificar se o software fornece modos de operação suficientes que utilizem as configurações de utilizador na plataforma para ajuste de cor, contraste, tipo de letra, tamanho de letra, e foco do ponteiro.<br>2. Verificar que a documentação do software indica que este foi desenhado para funcionar isolado da sua plataformas subjacente.
Resultado        |Passa: A verificação 1 é verdadeira ou a 1 é falsa e 2 é verdadeira.<br>Falha: As verificações 1 e 2 são falsas.

### C.11.8 Ferramentas de Autor
#### C.11.8.1 Tecnologia de conteúdo
Tipo de avaliação|Inspeção e Teste
-----------------|--------
Pré-condições    |1. O software é uma ferramenta de autor.<br>2. O formato de saída da ferramenta de autor suporta informação necessária para acessibilidade.
Procedimento     |1. Verificar se a ferramenta de autor está em conformidade com 11.8.2 a 11.8.5 tal que a informação necessária para acessibilidade é suportada pelo formato utilizado na saída da ferramenta de autor.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
NOTA: Quando o formato de saída da ferramenta de autor não suporta determinados tipos de informação necessária para acessibilidade, a conformidade com os requisitos relacionados com esse tipo de informação não é necessária.

#### C.11.8.2 Criação de conteúdo acessível
Tipo de avaliação|Inspeção e Teste
-----------------|--------
Pré-condições    |1. O software é uma ferramenta de autor.
Procedimento     |1. Verificar se a ferramenta de autor permite a criação de conteúdos que estejam em conformidade com as cláusulas 9 (Conteúdo Web) ou 10 (Conteúdo não-Web).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.11.8.3 Preservação da informação de acessibilidade em transformações 
Tipo de avaliação|Inspeção e Teste
-----------------|--------
Pré-condições    |1. O software é uma ferramenta de autor.<br>2. A ferramenta de autor fornece transformações de re-estruturação ou de re-escrita de código.
Procedimento     |1. Para uma transformação de restruturação, verificar se a informação de acessibilidade é preservada na saída.<br>2. Para uma transformação de restruturação, verificar se o conteúdo da tecnologia suporta informação de acessibilidade para a forma restruturada da informação.<br>3. Para uma transformação de código, verificar se a informação de acessibilidade é preservada na saída.<br>4. Para uma transformação de código, verificar se o conteúdo da tecnologia suporta informação de acessibilidade da saída recodificada.
Resultado        |Passa: A verificação 1 é verdadeira ou as verificações 1 e 2 são falsas ou 3 é verdadeira ou as verificações 3 e 4 são falsas.<br>Falha: A verificação 1 é falsa e a 2 é verdadeira

#### C.11.8.4 Assistência na reparação
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software é uma ferramenta de autor.<br>2.A funcionalidade de verificação de acessibilidade da ferramenta de autor pode detetar conteúdo que não esteja em conformidade com as cláusulas 9 (Conteúdo Web) ou 10 (Conteúdo não-Web), conforme aplicável. 
Procedimento     |1. A ferramenta de autor fornece sugestões de reparação quando o conteúdo que não está em conformidade com as cláusulas 9 (Conteúdo Web) ou 10 (Conteúdo não-Web) (conforme aplicável).
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.11.8.5 Modelos
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O software é uma ferramenta de autor.<br>2. A ferramenta de autor fornece modelos.
Procedimento     |1. Verificar que a ferramenta de autor fornece pelo menos um modelo que suporta a criação de conteúdo e que esteja em conformidade com os requisitos das cláusulas 9 (Conteúdo Web) ou 10 (Conteúdo não-Web), conforme aplicável.<br>2. Verificar que pelo menos um modelo da verificação 1 está disponível e identificado como estando em conformidade com os requisitos das cláusulas 9 ou 10 (conforme aplicável).
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: A verificação 1 ou 2 é falsa.
NOTA: A identificação de conformidade com os requisitos das cláusulas 9 ou 10 (conforme aplicável) descritas na verificação 2 pode ser descrita como "Conforme WCAG 2.1". Onde a identificação não estabelece explicitamente que todos os requisitos identificados nas cláusulas 9 ou 10 (conforme aplicável) estão cobertos, pode ser necessário utilizar o modelo para criar um website ou documento e, de seguida, testar esse website ou documento de acordo com os requisitos das cláusulas 9 ou 10 para garantir totalmente que o modelo se comporta conforme necessário.

## C.12 Documentação e Serviços de apoio
### C.12.1 Documentação de Produto
#### C.12.1.1 Funcionalidades de acessibilidade e de compatibilidade
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. É fornecida documentação do produto com a TIC.
Procedimento     |1. Verificar que a documentação do produto fornecida com a TIC, lista e explica como utilizar as funcionalidades de acessibilidade e de compatibilidade das TIC.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.12.1.2 Documentação acessível
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. É fornecida documentação do produto em formato eletrónico, com a TIC.
Procedimento     |1. Verificar que a documentação do produto em formato eletrónico, fornecida com a TIC, está em conformidade com os requisitos das cláusulas 9 ou 10, conforme aplicável.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.12.2 Serviços de apoio
#### C.12.2.1 Geral (informativo)
A Cláusula 12.2.1 é apenas informativa e não contém requisitos que precisem de testes.

#### C.12.2.2 Informação sobre funcionalidades de acessibilidade e de compatibilidade
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. São fornecidos serviços de suporte, com a TIC.
Procedimento     |1. Verificar que os serviços de apoio fornecem informação sobre as funcionalidades de acessibilidade e compatibilidade incluídas na documentação do produto.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.12.2.3 Comunicação efetiva
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. São fornecidos serviços de suporte, com a TIC.
Procedimento     |1. Verificar que os serviços de apoio prevêem as necessidades de comunicação de pessoas com deficiência, quer diretamente quer através de um **referral point.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.
NOTA: O fornecimento de qualquer nível de apoio para as necessidades de comunicação de pessoas com deficiência constitui a aprovação ao teste deste requisito. Os fornecedores podem fornecer mais informação sobre o nível de suporte que é fornecido, tal que permita uma avaliação sobre a adequação e qualidade desse suporte. 
### C.12.2.4 Documentação acessível
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. Os serviços de suporte da TIC fornecem documentação.
Procedimento     |1. Verificar que a documentação do produto em formato eletrónico, fornecida pelos serviços de suporte da TIC, está em conformidade com os requisitos das cláusulas 9 ou 10, conforme aplicável.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

## C.13 ICT que fornecem serviços de intermediação ou de emergência
### C.13.1 Requisitos dos serviços de intermediação
#### C.13.1.1 Geral (informativo)
A Cláusula 13.1.1 é apenas informativa e não contém requisitos que precisem de testes.
### C.13.1.2 Serviços de intermediação de Texto
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O serviço é um serviço de intermediação de texto.
Procedimento     |1. Verificar que o serviço permite que utilizadores de texto e utilizadores de fala comuniquem, fornecendo conversão entre os dois modos de comunicação.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.13.1.3	Serviços de intermediação de gestos
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O serviço é um serviço de intermediação de gestos.
Procedimento     |1. Verificar que o serviço permite que utilizadores de língua gestual e utilizadores de fala comuniquem, fornecendo conversão entre os dois modos de comunicação.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.13.1.4 Serviços de intermediação por leitura labial
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O serviço é um serviço de intermediação de leitura labial.
Procedimento     |1. Verificar que o serviço permite que utilizadores de leitura labial e utilizadores de fala comuniquem por telefone, fornecendo conversão entre os dois modos de comunicação.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.13.1.5 Serviços de legendagem de telefone
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O serviço é um serviço de legendagem de telefone.
Procedimento     |1. Verificar que o serviço permite que utilizadores surdos ou com baixa audição estabeleçam um diálogo falado, através de legendas de texto que apresentem a tradução da fala recebida durante a conversação.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.13.1.6 Serviços de intermediação de fala-fala
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O serviço é um serviço de intermediação de fala-fala.
Procedimento     |1. Verificar que o serviço permite que utilizadores de fala ou utilizadores de telefone com deficiência cognitiva e qualquer outro utilizador comuniquem, fornecendo assistência entre os dois.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.13.2	Acesso dos serviços de intermediação
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O sistema TIC suporta comunicação bidirecional.<br>2. Um conjunto de serviços de intermediação para comunicação bidirecional é especificado.
Procedimento     |1. Verificar que o sistema não impede o acesso a serviços de intermediação para chamadas de entrada e de saída. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.13.3 Acesso a serviços de emergência
Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. O sistema TIC suporta comunicação bidirecional.<br>2. Um conjunto de serviços de emeregência para comunicação bidirecional é especificado.
Procedimento     |1. Verificar que o sistema não impede o acesso a serviços de emergência para chamadas de entrada e de saída. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.


##### Tabela D.1: Critérios de sucesso WCAG 2.1 Nível AAA
No.|Orientação|Número de critério de sucesso|Número de critério de sucesso
|--|---|---|--
1|Multimédia Baseada no Tempo|1.2.6|Língua Gestual (Pré-gravada)
2|Multimédia Baseada no Tempo|1.2.7|Áudio-Descrição Alargada (Pré-gravada)
3|Multimédia Baseada no Tempo|1.2.8|Alternativa em Multimédia (Pré-gravada)
4|Multimédia Baseada no Tempo|1.2.9|Apenas áudio (Em directo)
5|Adaptável|1.3.6|Identificação de Propósito
6|Distinguível|1.4.6|Contraste (Melhorado)
7|Distinguível|1.4.7|Som Baixo ou Sem Som de Fundo
8|Distinguível|1.4.8|Apresentação Visual
9|Distinguível|1.4.9|Imagens de Texto (Sem Excepção)
10|Acessível por Teclado|2.1.3|Teclado (Sem Excepção)
11|Tempo Suficiente|2.2.3|Sem Temporização
12|Tempo Suficiente|2.2.4|Interrupções
13|Tempo Suficiente|2.2.5|Nova autenticação
14|Tempo Suficiente|2.2.6|Timeouts
15|Ataques Epilépticos|2.3.2|Três Flashes
16|Ataques Epilépticos|2.3.3|*Animation form Interactions
17|Navegável|2.4.8|Localização
18|Navegável|2.4.9|Finalidade do Link (Apenas o Link)
19|Navegável|2.4.10|Cabeçalhos da Secção
20|Modos de Entrada|2.5.5|**Target Size
21|Modos de Entrada|2.5.6|Mecanismos de entrada concorrentes
22|Legível|3.1.3|Palavras Invulgares
23|Legível|3.1.4|Abreviaturas
24|Legível|3.1.5|Nível de Leitura
25|Legível|3.1.6|Pronúncia
26|Previsível|3.2.5|Alteração a Pedido
27|Assistência de Entrada|3.3.5|Ajuda
28|Assistência de Entrada|3.3.6|Prevenção de Erros (Todos)
