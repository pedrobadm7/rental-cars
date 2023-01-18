# Cadastro de carro

**Requisitos funcionais**
Deve ser possível cadastrar um novo carro.

**Regra de negócio**
Não deve ser possível cadastrar um carro com uma placa já existente.
O carro deve ser cadastrado, por padrão, com disponibilidade.
* O usuário responsável pelo cadastro deve ser um usuário admnistrador.

# Listagem de carros

**Requisitos funcionais**
Deve ser possível listar os carros disponiveis.
Deve ser possível listar todos os carros disponiveis pelo nome da categoria.
Deve ser possível listar todos os carros disponiveis pelo nome da marca.
Deve ser possível listar todos os carros disponiveis pelo nome do carro.

**Regra de negócio**
O usuário não precisa estar logado no sistema.

# Cadastro de especificação no carro

**Requisitos funcionais**
Deve ser possível cadastrar uma especificação para um carro.
Deve ser possível listar todas as especificações.
Deve ser possível listar todos os carros.

**Regra de negócio**
Não deve ser possível cadastrar uma especificação para um carro não cadastrado.
Não deve ser possível cadastrar uma especificação já existente para o mesmo carro.
O usuário responsável pelo cadastro deve ser um usuário admnistrador.

# Cadastro de imagens do carro

**Requisitos funcionais**
Deve ser possível cadastrar a imagem do carro.
Deve ser possível listar todos os carros.

**Requisito não funcional**
Utilizar o multer par aupload dos arquivos.

**Regra de negócio**
O usuário deve poder cadastrar mais de uma imagem para o mesmo carro.
O usuário responsável pelo cadastro deve ser um usuário admnistrador.

# Aluguel de carro

**Requisitos funcionais**
Deve ser possível cadastrar um aluguel.

**Regra de negócio**
O aluguel deve ter duração minima de 24 horas.
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo usuário.
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo carro.
