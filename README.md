# Phishing para captura de senhas do GITHUB❗❗

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ```Selecionamos a (1) opção || Social-Engineering Attacks ```
- Vetor de ataque: ```Selecionamos a (2) opção || Web Site Attack Vectors ```
- Método de ataque: ```Selecionamos a (3) opção || Credential Harvester Attack Method ```
- Método de ataque: ```Selecionamos a (2) opção || Site Cloner ```
- Obtendo o endereço da máquina: ``` (obs: Deixe em branco para clonar o site alvo no localhost do dispositivo) ```
- URL para clone: https://www.github.com/login

### RESULTADOS OBTIDOS

![image alt](https://github.com/AgainSantos/cibersecurity-desafio-phishing/blob/master/pagina%20falsa.PNG?raw=true)

▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱▰▱

![image alt](https://github.com/AgainSantos/cibersecurity-desafio-phishing/blob/master/resultados.PNG?raw=true)


### DESVANTAGENS DESTE METÓDO:

- Verificação de duas etapas: Hoje em dia, muitas empresas priorizam a segurança de seus clientes e usuários; Por conta disso, elas implementam medidas como a verificação de duas etapas onde mesmo que o atacante tenha o acesso ao usuário e a senha do alvo ele ainda precisa confirmar via um código SMS ou Gmail o acesso oque torna uma missão mais árdua para o invasor. Além disso, dependendo de quem estiver acessando uma conta alheia, a localização pode ser exposta ao dono original da conta, como acontece nos serviços do Google, proporcionando uma camada extra de segurança ao alertar o usuário sobre atividades suspeitas.

- Mecanismos anti-phishing: Dependendo do site que estiver sendo clonado, como é o caso do Facebook, a clonagem acaba sendo barrada devido às medidas avançadas de segurança implementadas pela plataforma. Isso inclui o uso obrigatório de HTTPS, autenticação em duas etapas e entre muitos outros obstáculos.
