# Smart Home

![GitHub repo size](https://img.shields.io/github/repo-size/lpcoutinho/smart-home?style=for-the-badge)
![GitHub language](https://img.shields.io/github/languages/top/lpcoutinho/smart-home?style=for-the-badge)
<!-- ![GitHub language count](https://img.shields.io/github/languages/count/lpcoutinho/smart-home) -->
<!-- ![GitHub forks](https://img.shields.io/github/forks/iuricode/README-template?style=for-the-badge) -->
<!-- ![Bitbucket open issues](https://img.shields.io/bitbucket/issues/iuricode/README-template?style=for-the-badge) -->
<!-- ![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/iuricode/README-template?style=for-the-badge) -->

<!-- <img src="exemplo-image.png" alt="exemplo imagem"> -->

> Vamos construir uma API controla e  monitora dispositivos remotos via protocolo MQTT.

### Veja o desenvolvimento do projeto:

Para ver o desenvolvimento acesse o planejamento:

[![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lpcoutinho/smart-home)
[![Trello](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)](https://trello.com/b/3k8Xf7Hs/smart-home)

### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [ ] Construir API Base e conseguir realizar conexão local
- [ ] Container Docker da base
- [ ] Diagramar o Banco de Dados
- [ ] Construir Models e Schemas
- [ ] Montar Broker MQTT

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

* Python >= 3.8.10  
* Docker
* Broker MQTT
* Insomnia

## 🚀 Instalando o Projeto

Para instalar, siga estas etapas:

Linux e macOS:
```
# Instale e rode um ambiente virtual
python3 -m venv venv
. venv/bin/activate

# Instale os requerimentos
pip install -r requirements.txt
```

Windows:
```
<!-- TODO INSERIR COMANDOS DE INSTALAÇÃO E EXECUÇÃO DE VENV-->
# Instale os requerimentos
pip install -r requirements.txt
```

## ☕ Rodando em ambiente local

Para rodar o projeto em sua máquina, siga estas etapas:

```
uvicorn main:app --reload
```
Utilize o Insomnia para consultar os endpoints http://127.0.0.1:8000/

Para verificar a documentação clique [aqui](http://127.0.0.1:8000/docs)

## 📫 Contribuindo para o projeto

Para contribuir, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_branch>`
<!-- 5. Crie a solicitação de pull.

Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request). -->

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuem para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/luizpaulocoutinho/">
        <img src="https://media.licdn.com/dms/image/C4E03AQGF3-5AytW8Zw/profile-displayphoto-shrink_200_200/0/1628165102623?e=1683158400&v=beta&t=reaa7DdVw4uWROEadmzrRu30ICcu1JbUJb2XQSo-tUU" width="100px;" alt="Foto do Luiz no GitHub"/><br>
        <sub>
          <b>Luiz Paulo Coutinho</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/natalia-pedrosabarros/">
        <img src="https://media.licdn.com/dms/image/D4D03AQFAfSxlw8G_Pw/profile-displayphoto-shrink_200_200/0/1669112043525?e=1683158400&v=beta&t=-rY5CoJDaQpOH0WHirBNAYoLbXuX5SQ5kMlaqow3tTE" width="100px;" alt="Foto do Mark Zuckerberg"/><br>
        <sub>
          <b>Natália Pedrosa</b>
        </sub>
      </a>
    </td>
  </tr>
</table>


## 😄 Seja um dos contribuidores<br>

Quer fazer parte desse projeto? Procuramos pessoas que queiram mudar de carreira e estajam perdidas mas dispostas a entrar de cabeça no mundo da programação.
Juntos vamos desenvolver projetos reais com o intuito de tornar-mo-nos aptos a ingressar no mercado de trabalho.

Para saber como contribuir nos envie uma mensagem.
 <!-- Clique [AQUI](CONTRIBUTING.md) e leia como contribuir. -->

## 📝 Licença

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.

[⬆ Voltar ao topo](#smart-home)<br>