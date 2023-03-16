# PocAPIRest
API Rest em Spring Boot

Testes realizados no Insomnia (http://localhost:8080/medicos; http://localhost:8080/pacientes)

POST MEDICOS

{
"nome": "Francisco José",
"email": "frank@voll.med",
"crm": "12342",
"especialidade": "CARDIOLOGIA",
"telefone": "999999999",
"endereco": {
    "logradouro": "rua 1",
    "bairro": "bairro",
    "cep": "12345678",
    "cidade": "Fortaleza",
    "uf": "CE",
    "numero": "1",
    "complemento": "B5 793"
    }
}
