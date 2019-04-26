


## Modelo Descritivo
###	 `SMTSIS`   

>									 2019 - SENAI, São Gonçalo do Amarante, RN.

	Com base nos acordos com a Secretaria Municipal de Tributação, modelaremos um banco de dados, que contenha:
## `BIC`
No cadastro deve estar as seguintes informações:

### `Contribuinte/proprietário:`
- Nome;
- Data de Nascimento;
- telefone;
- logradouro;
- CPF/CNPJ;
- RG;
  - Orgão expedidor;
- CNH;
- UF;

## `Endereço:`
- CEP;
- Logradouro;
- Complemento;
- UF;
- Bairro;
- Número;
- Cidade;
- Contato;
- E-mail;
- Comercial;
- Celular;

### `Imóvel:`
- Tipo de imóvel:
  - Apartamento;
  - Casa;
  - Motel;
  - Terreno;
  - Hospital;
  - Galpão;
  - Shopping;
  - Ginásio;
- Utilização do imóvel:
  - Mista;
  - Metálica;
  - Hospital;
- Padrão de Qualidade:
  - Alto;
  - Médio;
  - Baixo;
- Informações gerais:
  - Pedologia:
    - Normal;
    - Alagado Total;
    - Alagado +50%;
    - Alagado -50%;
  - Topografia:
    - Plano;
    - Aclive/Declive;
    - Redução de Capacidade;
  - Estado de Conservação:
    - Ótimo;
    - Regular;
    - Ruim;
  - Situação do Terreno:
    - Meio de quadra;
    - Encravado;
    - Esquina;
    - Mais de uma frente;
    - Fundo/Interno;

### `Impostos e taxas:`
- Impostos:
  - De: (date);
  - Até: (date);
- Limpeza:
  - De: (date);
  - Até: (date);
- Ajuste de valor por área:
  - Zona 01;
<<<<<<< HEAD
  - `[...]`
  - Zona 05;
### `Fiscal (Responsável pelas informações):`
=======
  - [...]
  - Zona 05;
### `Fiscal (Responsável pelas informações)`
>>>>>>> 0c34279cd82efcf66b674f4df67f3d3febce3b33
- Data (datetime);
- Nome;
- Assinatura;
- Matrícula;
- Observações;
