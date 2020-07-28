# n8n - Workflow Automation Tool

<a href="https://n8n.io/">
<img src="https://docs.n8n.io/assets/img/n8n-logo.png" width="550" alt="n8n.io - Docs">
</a>

---

## IMPORTANTE:
- **ENV:** Copie o conteudo de [`.env.example`](.env.example) para  [`.env`](.env)!

- **Senhas:** Mude as senhas no arquivo [`.env`](.env)!

---

## Como usar

- Pode dar inicio em vários ambientes de uma vez usando um docker-compose unico ou separar exeplicitamente por comando ou por arquivo.

**Subir Todos**

```
docker-compose up
```

**Um específico por comando**

```
docker-compose up one
```

**Um específico por arquivo**

```
docker-compose -f ./docker-compose-n8n-one.yml up
```

**Build e up**
```
docker-compose -f 'docker-compose-n8n-two.yml' up --build
```

**Rodar comando**
```
docker-compose -f 'docker-compose-n8n-two.yml' run appname bash
```

**Excluir após rodar comando**
```
docker-compose -f 'docker-compose-n8n-two.yml' run --rm appname bash
```

---

## [n8n Documentation](https://docs.n8n.io/) 

## Demo

[A short demo (< 3 min)](https://www.youtube.com/watch?v=3w7xIMKLVAg) 

---

![n8n.io - Workflow Automation](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-logo.png)

n8n is a free and open [fair-code](http://faircode.io) licensed node based Workflow Automation Tool. It can be self-hosted, easily extended, and so also used with internal tools.

<a href="https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot.png"><img src="https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot.png" width="550" alt="n8n.io - Screenshot"></a>


