# Portfolio de Gustavo Muraoka Silva

Esse repósitório busca exibir as informações pessoais do aluno, projetos participados e principais pontos a serem destacados durante a trejetória do respectivo indivíduo.

- 💼 [LinkedIn](https://www.linkedin.com/in/gustavo-muraoka-4256721ba/)
- 📁 [Repositórios GitHub](https://github.com/gustavomuraoka)
- 📧 gustavomuraoka15@gmail.com

## Sumário
- Infomações Pessoais e Formação Acadêmica
- APIs da FATEC
- Projetos Pessoais e Profissionais

## Informações Pessoais e Formação Acadêmica
- Nascido em Janeiro de 2003, na cidade de São José dos Campos, São Paulo, Brasil.
- Formado no ano de 2019 no ensino médio integrado ao ensino técnico na ETEC Ilza Nascimento Pintus, em São José dos Campos, com graduação no técnico de informática, coletando experiência fullstack em desenvolvimento de software, além de experiência na manipulação de Hardware.
- Ingressei na UNIFESP - Universidade Federal de São Paulo no ano de 2020, permancendo matriculado até 2023, me graduando em Bacharelado de Ciência e Tecnologia. Também tive a chance de me desenvolver em campos como Bioinformática, e Bioestatística, matérias da grade de Biotecnologia.
- Atualmente estudante da FATEC - Jessen Vidal, no curso de Desenvolvimento de Software Multiplataforma, com previsão de formação em Dezembro de 2026.
- Sou desenvolvedor fullstack Jr na empresa FullTrader, também localizada em São José dos Campos.
- Sou freelancer para serviços relacionados ao desenvolvimento de software fullstack, atuando em projetos de empresas de diversas áreas.

### Resumo da formação técnica voltada ao campo de tecnologia
- Técnico de Informática (2017 - 2019, ETEC Ilza Nascimento Pintus)
- Bacharel em Ciência e Tecnologia (2020 - 2023, UNIFESP - Universidade Federal de São Paulo)
- Tecnólogo de Desenvolvimento de Software Multiplataforma (2024 - est. 2026 - FATEC Jessen Vidal)

---

## APIs da FATEC
### SmartFarm
1º Semestre - Jan/2024 - Jun/2024
SmartFarm foi a proposta encontrada pelo grupo SkyFly para solucionar problemas de monitoramento de estufas com tecnologia de controle de umidade e temperatura. Com SmartFarm, o responsável pela estufa, antes solicitado que estivesse presencialmente para coleta dos dados, teve a possibilidade de receber esses dados via Sistema Web em tempo real com uma interface amigável ao uso, fazendo com que uma tarefa antes exaustiva e que exigia mobilidade se tornar uma prática quase instantânea, permitindo o monitoramente em qualquer lugar do planeta.

#### Solução
Para coleta dos dados, foram utilizados sensores de umidade e temperatura que realizam leitura periódica dos dados dentro da estufa em intervalos espaçados de tempo, sendo que esses sensores tiveram seu script modificado pelo grupo para transmitir os dados lidos ao longo do tempo. Os dados eram enviados por um ENDPOINT de método POST que a API desenvolvida em Flask pudesse registrar essa informação no banco de dados MySQL, guardando o estado da estufa ao longo do tempo.
