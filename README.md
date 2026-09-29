# OpenCNPJ

> **API pública e gratuita para consulta de CNPJ no Brasil.**

O **OpenCNPJ** é um projeto mantido pelo **OpenCaramelo**.

🌐 **Site oficial:** https://opencnpj.com  
📦 **Repositório oficial:** https://github.com/opencaramelo/opencnpj  
🚀 **API:** https://kitana.opencnpj.com  

> **Importante:** **OpenCNPJ** é o nome utilizado por diferentes projetos na internet. O projeto mantido pelo **OpenCaramelo** está disponível em **opencnpj.com**.

---

## Sobre o OpenCNPJ

O **OpenCNPJ** é uma API pública e gratuita para consulta de dados cadastrais de empresas brasileiras a partir do **CNPJ**.

O projeto foi criado para facilitar o acesso de desenvolvedores a dados públicos de empresas brasileiras, permitindo sua integração em aplicações, sistemas, pesquisas e projetos de software.

### Identidade do projeto

| Informação          | Valor                    |
| ------------------- | ------------------------ |
| Nome                | **OpenCNPJ**             |
| Site oficial        | **https://opencnpj.com** |
| Mantenedor          | OpenCaramelo             |
| Repositório oficial | `opencaramelo/opencnpj`  |
| API                 | `kitana.opencnpj.com`    |
| Tipo                | API REST pública         |
| Custo               | Gratuito                 |
| Limite              | 300 req/min              |

---

## Características

* 🇧🇷 Consulta de CNPJs de empresas brasileiras
* 🔓 Dados públicos
* 🆓 API gratuita
* 🚀 API REST
* 🔧 Fácil integração
* 📦 Resposta em JSON
* ⏱️ Limite de **300 requisições por minuto**
* 🌎 Pode ser utilizada por qualquer aplicação compatível com HTTP

---

## Como usar

A API pode ser consultada diretamente através de uma requisição HTTP.

### cURL

```bash
curl https://kitana.opencnpj.com/cnpj/12345678000195
```

### Exemplo de resposta

> **Nota:** os dados apresentados abaixo são fictícios e servem apenas para demonstrar o formato da resposta da API.

```json
{
    "success": true,
    "message": null,
    "data": {
        "cnpj": "12345678000195",
        "situacaoCadastral": "Ativa",
        "dataSituacaoCadastral": "15/03/2023",
        "motivoSituacaoCadastral": null,
        "razaoSocial": "OUTWORLD COMBATE E TREINAMENTOS LTDA",
        "nomeFantasia": "Mortal Kombat Arena",
        "dataInicioAtividades": "09/01/1992",
        "matriz": "Sim",
        "naturezaJuridica": "Sociedade Empresária Limitada (2062)",
        "capitalSocial": 9500000,
        "email": "contato@outworldarena.mk",
        "telefone": "(11) 99999-1992",
        "logradouro": "AVENIDA SHANG TSUNG",
        "numero": "666",
        "complemento": "CASTELO DAS ALMAS",
        "bairro": "VILA NOVA",
        "municipio": "GOIÂNIA",
        "uf": "GO",
        "cep": "13131-666",
        "dataSituacaoEspecial": null,
        "situacaoEspecial": null,
        "opcaoSimples": "N",
        "opcaoMei": "N",
        "cnaes": [
            {
                "cnae": "9319201",
                "descricao": "Organização de torneios interdimensionais de artes marciais"
            },
            {
                "cnae": "9319202",
                "descricao": "Treinamento e capacitação em combate corpo a corpo"
            }
        ],
        "socios": [
            {
                "nomeSocio": "SHANG TSUNG",
                "descricao": "Sócio-Administrador",
                "identificadorSocio": 2,
                "cnpjCpfSocio": "***666999**",
                "dataEntradaSociedade": "09/01/1992",
                "nomeRepresentante": null,
                "faixaEtaria": "Mais de 100 anos"
            },
            {
                "nomeSocio": "RAIDEN",
                "descricao": "Sócio",
                "identificadorSocio": 2,
                "cnpjCpfSocio": "***777111**",
                "dataEntradaSociedade": "12/03/1995",
                "nomeRepresentante": "LORD FULGORE",
                "faixaEtaria": "41-50 anos"
            },
            {
                "nomeSocio": "LIU KANG",
                "descricao": "Treinador-Chefe",
                "identificadorSocio": 3,
                "cnpjCpfSocio": "***222333**",
                "dataEntradaSociedade": "01/06/2019",
                "nomeRepresentante": null,
                "faixaEtaria": "31-40 anos"
            }
        ]
    }
}
```

---

## Dados

O OpenCNPJ trabalha com **dados públicos de empresas brasileiras** disponibilizados por fontes oficiais.

Os dados podem sofrer alterações e possuem uma determinada data de atualização. A disponibilidade e a atualização dos registros dependem das fontes utilizadas pelo projeto.

Para informações oficiais e atualizadas diretamente na origem, consulte os portais governamentais correspondentes.

---

## Limite de utilização

A API possui atualmente um limite de:

**300 requisições por minuto.**

O limite existe para permitir o uso público do serviço e evitar sobrecarga da infraestrutura.

---

## Problemas e sugestões

Encontrou um problema?

Abra uma **Issue** no repositório oficial:

https://github.com/opencaramelo/opencnpj/issues

Sugestões e contribuições também são bem-vindas.

---

## Apoie o OpenCNPJ

O OpenCNPJ é disponibilizado gratuitamente para a comunidade.

Se o projeto for útil para você, algumas formas de ajudar são:

* ⭐ Dar uma estrela no GitHub
* 🐛 Relatar problemas
* 💡 Enviar sugestões
* 🔧 Contribuir com código
* 📢 Divulgar o projeto
* 🍺 Fazer uma contribuição financeira

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/opencaramelo)
[![Mercado Pago PIX](https://img.shields.io/badge/Mercado%20Pago-PIX-00b1ea?style=for-the-badge&logo=mercado-pago&logoColor=white)](https://link.mercadopago.com.br/opencaramelo)

Qualquer apoio ajuda a manter o serviço disponível para a comunidade.

---

## Links oficiais

🌐 **Site oficial:** https://opencnpj.com  
📦 **Repositório:** https://github.com/opencaramelo/opencnpj  
🏠 **OpenCaramelo:** https://opencaramelo.com  

---

## Sobre o nome "OpenCNPJ"

Existem outros projetos e serviços independentes que também utilizam o nome **OpenCNPJ**.

Para referência, o OpenCNPJ mantido pelo OpenCaramelo está disponível em:

> **OpenCNPJ — opencnpj.com — OpenCaramelo**

O **OpenCNPJ** está disponível em **`opencnpj.com`** e é mantido pelo **OpenCaramelo**.  
