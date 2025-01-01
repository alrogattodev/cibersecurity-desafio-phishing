Desafio do curso de Cybersecurity da DIO 

Ferramentas Utilizadas
- Kali Linux
- terminal
- setoolkit

Passos feitos: 
1. No Kali Linux, pelo terminal executar o setoolkit com permissão de root
    `sudo setoolkit`
2. Selecionar o tipo principal de ataque: `Social-engineering Attacks`
3. Selecionar subtipo: `Web Site Attack Vectors`
4. Selecionar Método de Ataque: `Credential Harvester Attack Method`
5. Selecionar submétodo: `Site Cloner`
6. Clonar o site, no caso o http://facebook.com
6.1 Executar correções no index.html do clone feito pelo setools
7. Acessar a via http o servidor que contém o phishing
8. Obter as informações

Informações Obtidas: 
 ```bash
POSSIBLE USERNAME FIELD FOUND: email=teste@teste.com                         
POSSIBLE PASSWORD FIELD FOUND: pass=teste123                                 
POSSIBLE USERNAME FIELD FOUND: login=1
```

