# Dicionário de Dados

|Nome|Tipo|Domínio|Codificação|
|:----:|:----:|:-------:|:-----------|
|Idade|Integer|[0, 100]|Valor Numérico Inteiro|
|Localidade|String|Texto Livre|Zona de Localidade|
|Conhecimento sobre Segurança Digital na Internet|Boolean|Binário|TRUE = Sim<br>FALSE = Não|
|Quantidade de Livros Lida|Integer|[0, 50]|Valor Numérico Inteiro|
|Formato|Categorical|Nominal|Código 1: Papel<br>Código 2: Digital<br>Código 3: Ambos|
|Género Literário|Categorical|Nominal|Código 1: Criptografia e Segurança de Dados (Encriptação, Blockchain, Proteção de Ficheiros)<br>Código 2: Firewalls, Redes e Infraestrutura (Configuração de Routers, VPNs, Segurança de Rede)<br>Código 3: Hacking Ético e Testes de Intrusão (Pentesting, Ferramentas como Kali Linux)<br>Código 4: Privacidade e proteção dos dados<br>Código 5: Crime Digital e Forence (Investigação de Possíveis Malwares)<br>Código 6:Não tenho interesse literário nenhum nesta área|
|Horas Semanais|Integer|HH|Valor Númerico de Horas de Leitura Semanais|
|Proteção do dispositivo pessoal|Categorical|Nominal|Código 1: Uso apenas as proteções que vêm por defeito do sistema<br>Código 2: Tenho um software de segurança dedicado/pago<br>Código 3: Não sei se tenho ativo/Não me preocupo com isso|
|Gestão de Passwords|Categorical|Nominal|Código 1: Uso a mesma palavra-passe (ou variações simples) para quase todas as contas<br>Código 2: Uso a mesma palavra-passe para quase todas as contas<br>Código 3: Uso um gestor de palavras-passe ou crio uma única e complexa para cada serviço|
|Ação SMS|Categorical|Nominal|Código 1: Clico logo, pois pode ser um problema na minha conta<br>Código 2: Verifico sempre o remetente e o link antes de clicar<br>Código 3: Ignoro e denuncio a mensagem como spam/phishing|

---

## 1. Regra de Anonimização
Para conformidade com o **RGPD** e redução da possibilidade de identificação, foi aplicada a seguinte regra de anonimização:

### Anonimização na Origem
**Descrição:** O questionário foi concetualmente desenhado sem a inclusão de campos de identificação direta (ex.: nome, e-mail, NIF, IP) ou indireta (ex.: data exata de nascimento, morada completa).<br>
**Processamento *Post-hoc*:** Não aplicável. Dado a não ter sido recolhido qualquer tipo de dado identificativo, os dados brutos são nativamente anónimos.