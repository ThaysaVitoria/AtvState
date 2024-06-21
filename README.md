# Gerenciamento de Estados de Tarefas

 <hr/>
 
 ## Requisitos do Sistema

### 🫐 Padrão State
- Utilização do padrão de projeto State aplicado em um caso de status de tarefas.
- Status: Created, In Progress, Completed, Cancel.
- Classe Task com id, name, description.

### 🫐 Endpoints RESTful
- POST /tasks 
- PUT /tasks/{id}/start 
- PUT /tasks/{id}/complete 
- PUT /tasks/{id}/cancel 
- GET /tasks/{id} 

<br/>

### 🔼 Atenção 

O projeto já possui uma migration para o Banco de Dados. 
Caso não tenha, utilize os seguintes comandos:
  ```
  add-migration teste
--
  update-database
  ```

<hr/>
