# OpenCNPJ
### WebService para consulta basica de CNPJs com dados totalmente publico!

🔗 **Acesse o projeto online:** [https://www.opencnpj.com](https://www.opencnpj.com)

Uma **API** feita para **ajudar a comunidade de desenvolvedores** a integrar dados de CNPJs de forma rápida e prática.  
Pode ser usado em **qualquer projeto ou aplicação que precise acessar dados de CNPJs**.

---

## 🔹 Ideia do projeto

- **Dados totalmente públicos de CNPJs**, acessíveis de forma simples.
- Integração fácil com **qualquer sistema** que precise desses dados.
- **Limite de 100 requisições por minuto**, para uso consistente sem sobrecarregar o serviço.
- **100% gratuito**, permitindo que a comunidade participe, melhore e reutilize.

---

## 🔹 Como usar

Exemplo de requisição com `curl`:

```bash
curl https://kitana.opencnpj.com/cnpj/07355799000188
```

```json
{
    "success": true,
    "message": null,
    "data": {
        "cnpj": "99988877000199",
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

### Os dados são públicos?

Sim! Todos os dados são totalmente públicos e podem ser consultados nos portais oficiais do governo.

### E estão sempre atualizados?

Nos esforçamos para manter tudo atualizado, com revisões mensais sempre que possível.

### Encontrou algum problema?

Abra uma **issue** no GitHub e nos avise. Vamos adorar corrigir!

### Tem sugestões ou ideias?

Mande um chamado ou crie uma issue — seu feedback ajuda muito a melhorar o OpenCNPJ!

### Quer apoiar o projeto?

Dar um ⭐ no GitHub ou contribuir ajuda a manter o OpenCNPJ ativo e disponível para a comunidade..

Obrigado pelo apoio! 🙌

### Quer apoiar ainda mais o projeto?

Se o OpenCNPJ está sendo útil para você e **quiser me pagar uma cerveja 🍺**, você pode contribuir clicando aqui:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/opencaramelo)
[![Mercado Pago PIX](https://img.shields.io/badge/Mercado%20Pago-PIX-00b1ea?style=for-the-badge&logo=mercado-pago&logoColor=white)](https://link.mercadopago.com.br/opencaramelo)

### Não é obrigatório, mas qualquer ajuda mantém o projeto ativo e disponível para a comunidade!  
### Também vale dar um ⭐ no GitHub 😉