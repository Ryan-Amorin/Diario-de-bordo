# Diario-de-bordo sobre a segurança do banco de dados 
##### Por Ryan Amorin, Luana Taina e Pedro Bezerra.

---

<br>

## Qual a importância da segurança do banco de dados?

A principal importância da segurança do banco de dados, é garantir a confidencialidade das informações armazenadas, sem que sejam violadas e vazadas para a internet afora. Ela lida com os dados, programas associados, ferramentas utilizadas, infraestrutura do sistema ou rede e do seu gerenciamento. Tudo isso deve ser pensado antes, durante e depois do projeto para um software. <br>

---

## Pilares da segurança

### Confidencialidade

- É a garantia de que os dados serão armazenados de forma sigilosa e privada, dando permissão para acesso apenas para aqueles usuários que devem ser responsáveis pelo manuseio dessas informações, evitando que muitas máquinas entrem em contato com esses dados.<br>
Existem diversas maneiras de quebrar essa confidencialidade, propor medidas contra esses ataques diminuem a possibilidade de uma invasão ou acesso indevido. Métodos como a criptografia dos dados, classificação e rotulação de dados sensíveis, habilitar restrições de acesso e utilizar autenticação multifator auxilia na prevenção desses riscos.

---

### Integridade

- é o princípio que garante que os dados não foram modificados, apagados ou adulterados de forma indevida. Ela assegura que a informação permaneça exata, confiável e em seu estado original durante todo o seu ciclo de vida, seja armazenada ou em trânsito.

<br>

**O Papel da Integridade**

- Faz parte da base de proteção dos sistemas junto com a confidencialidade e a disponibilidade (tríade CID)

- Impede fraudes e erros causados por mudanças sem permissão

- Garante que o receptor de uma mensagem ou arquivo receba exatamente o que foi enviado pelo autor original.

<br>

**Como Proteger a Integridade**

- Funções Hash: Usam algoritmos matemáticos para gerar códigos únicos de arquivos. Qualquer mudança mínima altera o código e avisa sobre a adulteração.
- Assinaturas digitais: Vinculam a identidade de quem enviou ao conteúdo do documento, invalidando o arquivo se houver alteração.
- Controle de acesso: Limita quem pode editar ou apagar arquivos importantes.
- Cópias de segurança (backups): Permitem recuperar versões originais e corretas caso ocorra algum dano ou alteração errada.

---

### Disponibilidade

A Disponibilidade é o pilar da Segurança da Informação que assegura que dados, sistemas, redes e aplicações estejam operacionais e acessíveis às pessoas autorizadas exatamente quando necessário, sem atrasos excessivos. De nada adianta manter a informação confidencial e íntegra se ela não puder ser utilizada para operacionalizar o negócio ou atender aos clientes.

<br>

**Principais Ameaças à Disponibilidade**

A indisponibilidade de sistemas pode ser causada por diferentes origens:

1. **Falhas de Infraestrutura e Energia:** Quedas elétricas ou interrupções operacionais sem um plano de recuperação em vigor.
2. **Desastres Naturais e Impedimentos Físicos:** Inundações ou tempestades severas que impedem o acesso dos colaboradores às estações de trabalho e recursos essenciais.
3. **Ataques Cibernéticos e Sabotagem:** Ataques de Negação de Serviço (*DoS/DDoS*) e infecções por *Ransomware*.

<br>

**Medidas de Proteção e Mitigação**

Para garantir a disponibilidade contínua dos recursos, devem ser adotadas as seguintes práticas:

* **Redundância de Sistemas:** Manter redes, servidores e aplicações secundárias prontas para assumir a operação automaticamente em caso de falha do sistema primário (*failover*).
* **Gestão de Patches e Atualizações:** Manter softwares e sistemas de segurança atualizados para reduzir falhas técnicas e vulnerabilidades conhecidas.
* **Planos de Backup e Recuperação de Desastres (DRP):** Realizar cópias de segurança frequentes e estruturar planos claros para restauração rápida do ambiente após incidentes.

---

## O que é a criptografia e como o controle de acessos afeta na modelagem do banco?
É conhecido como o processo de proteger informações ou dados utilizando métodos matemáticos para misturar de forma que apenas o destino final tenha acesso a informação. Funciona como um cadeado e chaves, um cadeado (informação) só pode ser aberto pelas chaves (máquinas) corretas que abrem ele e vice-versa. <br>
Por isso o controle de acessos é importante ser averiguado, para que as informações não sejam compartilhadas com usuários indevidos.<br>
A criptografia é utilizada diariamente sem que percebamos, em nossas mensagens, transações, reuniões, etc. Protegendo e garantindo a integridade dos dados nos dispositivos, pois são essas informações que movem o mundo no momento.

<br>

### Exemplo no BRmodel Web

**Dados sensíveis**

Aluno: <br>
1. Matrícula
2. Sexo
3. Senhas
4. Idade

Professor: <br>
1. Sexo
2. Idade
3. Nº de registro

Disciplinas: <br>
1. Carga horária

<br>

**Tabelas para registros de presenças**

1. Professores
2. Alunos

## Links com referências

[Fortinet](https://www.fortinet.com/br/resources/cyberglossary/cia-triad) <br>
[IBM](https://www.ibm.com/br-pt/think/topics/database-security) <br>
[Cloud Google](https://cloud.google.com/learn/what-is-encryption?hl=pt-BR) <br>
