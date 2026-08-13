# Diario-de-bordo sobre a segurança do banco de dados 
##### Por Ryan Amorin, Luana Taina e Pedro Bezerra.

---

<br>

## Qual a importância da segurança do banco de dados?

A principal importância da segurança do banco de dados, é garantir a confidencialidade das informações armazenadas, sem que sejam violadas e vazadas para a internet afora. Ela lida com os dados, programas associados, ferramentas utilizadas, infraestrutura do sistema ou rede e do seu gerenciamento. Tudo isso deve ser pensado antes, durante e depois do projeto para um software. <br>


<br>

## Pilares da segurança

### Confidencialidade

- É a garantia de que os dados serão armazenados de forma sigilosa e privada, dando permissão para acesso apenas para aqueles usuários que devem ser responsáveis pelo manuseio dessas informações, evitando que muitas máquinas entrem em contato com esses dados.<br>
Existem diversas maneiras de quebrar essa confidencialidade, propor medidas contra esses ataques diminuem a possibilidade de uma invasão ou acesso indevido. Métodos como a criptografia dos dados, classificação e rotulação de dados sensíveis, habilitar restrições de acesso e utilizar autenticação multifator auxilia na prevenção desses riscos.


### Integridade

- é o princípio que garante que os dados não foram modificados, apagados ou adulterados de forma indevida. Ela assegura que a informação permaneça exata, confiável e em seu estado original durante todo o seu ciclo de vida, seja armazenada ou em trânsito.

**O Papel da Integridade**

- Faz parte da base de proteção dos sistemas junto com a confidencialidade e a disponibilidade (tríade CID)

- Impede fraudes e erros causados por mudanças sem permissão

- Garante que o receptor de uma mensagem ou arquivo receba exatamente o que foi enviado pelo autor original.

**Como Proteger a Integridade**

- Funções Hash: Usam algoritmos matemáticos para gerar códigos únicos de arquivos. Qualquer mudança mínima altera o código e avisa sobre a adulteração.
- Assinaturas digitais: Vinculam a identidade de quem enviou ao conteúdo do documento, invalidando o arquivo se houver alteração.
- Controle de acesso: Limita quem pode editar ou apagar arquivos importantes.
- Cópias de segurança (backups): Permitem recuperar versões originais e corretas caso ocorra algum dano ou alteração errada.

### Disponibilidade

- 

## O que é a criptografia e como o controle de acessos afeta na modelagem do banco?
É conhecido como o processo de proteger informações ou dados 


## Links com referências

[Fortinet](https://www.fortinet.com/br/resources/cyberglossary/cia-triad) <br>
[IBM](https://www.ibm.com/br-pt/think/topics/database-security) <br>
