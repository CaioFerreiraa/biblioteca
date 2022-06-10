## API Reference
### Livro
#### Criar livro
API para criar um novo livro
```http
  POST http://127.0.0.1:8000/api/livros/
``` 
 Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `nome`| `string` | **Required**. |
`autor`| `string` | **Required**. nome artistico do autor |
`editora`| `string` | **Required**. editora do livro |
`status`| `boolean` | **Required**. livro esta ou não locado|
`sinopse`| `text` |**optional** sinopse do livro |

Request example:
```json
{
	"nome": "Como ser bom",
	"autor": "Prof Gui",
	"editora": "saraiva",
	"status": true,
	"sinopse": "how to be good"
}
```



arquivo extensão .MD
