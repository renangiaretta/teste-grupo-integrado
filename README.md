# :books: Desafio

É um diferencial para nossos futuros alunos a utilização de processos digitais para se matrícularem em nossa instituição. Isso trás agilidade para o processo e melhora a experiência dos nossos usuários.
Você deverá desenvolver uma solução permita que futuros alunos se matrículem em cursos de diversas modalidades e tipos.
A aplicação deverá apresentar os cursos disponíveis e permitir a realização de filtros para facilitar a escolha. Após a escolha, o futuro aluno deverá preencher um cadastro com as seguintes etapas:


Primeira etapa

- Nome
- E-mail
- Telefone


Segunda etapa

- CEP
- CPF
- Nascimento

Terceira etapa
- Envio do documento de identificação

Alguns detalhes importantes

Cursos:

Podem ser ofetados nas modalidades Presencial e EAD;
Podem ser dos tipos Graduação e Pós-graduação;
Valor do investimento e número de parcelas devem estar presentes;


Acadêmico:

Deve possuir um endereço com CEP válido;
E-mail e número de celular são indispensáveis;
Mostrar os campos de acordo com as etapas e salvá-los assim que concluídas é importante para usabilidade/captura de oportunidades de negócio.


Documentos:

Deve ser enviado um Documento de Identificação (CNH ou RG)

# :bookmark_tabs: Ferramentas utilizadas 

- Typescript;
- NextJS;
- Material UI;
- Express;
- Axios;
- React Toastify;
- React Icons;
- SASS;
- React Scroll;

# 💻 Decisões tomadas e resultados

Ao iniciar o projeto, decidi trabalhar com o framework NUXT 3, mesmo sendo minha primeira experiência com essa tecnologia. A decisão de adotar o Nuxt 3, um framework mais recente, alinhava-se à busca por profissionais capazes de se adaptar a novos desafios e linguagens, característica essencial para a vaga.

Embora tenha enfrentado dificuldades iniciais devido à relativa novidade do Nuxt 3, essa escolha reforçou minha habilidade em superar obstáculos. A falta de materiais e bibliotecas adaptadas à nova maneira de utilizar o framework demandou tempo adicional para a assimilação de conceitos e a busca por conteúdo útil. Esses desafios, embora tenham impactado o prazo para algumas funcionalidades, proporcionaram uma experiência excepcional de aprendizado e adaptação a novas tecnologias. Essa jornada, apesar de alguns contratempos, contribuiu significativamente para o desenvolvimento das minhas competências.


# 💻 Como rodar o projeto Back-end

*** O arquivo .env foi enviado a utilização da rota de upload que utiliza o serviço do cloudinary. Dentro de alguns dias esta instância de testes será desativada e você precisará configurá-la novamente. ***

### Dependências mínimas para rodar a aplicação
  - NodeJS: `Versão usada => NodeJS v18.14.0`
  - NestJS: `Versão usada => NestJS v10.0.0`
  - PostgreSQL: `Versão usada => PostgreSQL v15.2`

### Clone o projeto e entre na pasta
```
 git clone https://github.com/renangiaretta/teste-grupo-integrado.git
 cd backend-integrado
```
 npm install
<br>
 Crie um banco de dados PostgreSQL e depois configure o arquivo .env
```
npx prisma migrate dev
npm run seed
npm run start:dev
```
### O back-end estará rodando na porta 8000
```
http://localhost:8000/
```

# 💻 Como rodar o projeto Front-end

### Dependências mínimas para rodar a aplicação
  - NodeJS: `Versão usada => NodeJS v18.14.0`

### Clone o projeto e entre na pasta
```
 git clone https://github.com/renangiaretta/teste-grupo-integrado.git
 cd frontend-integrado
 npm install
```
```
npm run dev <-- Vai rodar a aplicação

```
### O front-end estará rodando na porta 3000
```
http://localhost:3000/
