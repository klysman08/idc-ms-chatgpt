- Construir a imagem docker da aplicação chatservice
- Aplicar o manifesto do chatservice
- Aplicar o manifesto do Keycloak 
- Alterar o arquivo host da máquina para adicionar o host keycloak 
- Construir a imagem docker da aplicação webapp
- Aplicar o manifesto da aplicação webapp

``` bash
[Title](name:%2520CI-CD) [Title](on:%2520#%2520Evento%2520que%2520vai%2520disparar%2520o%2520workflow) [Title](../../../..) [Title](jobs:) [Title](<../../../../            klysman08/imersao-chatservice:v${{ github.run_number }} >) [Title](<../../../../            klysman08/imersao-chatservice:latest>) [Title](<../../../../            klysman08/imersao-gpt-webapp:v${{ github.run_number }}>) [Title](<../../../../            klysman08/imersao-gpt-webapp:latest>) [Title](<../../../../      >) [Title](<../../../../          >) [Title](<../../../../          sed -i "s/{{API_TOKEN}}/${{ secrets.OPENAI_API_KEY }}/g" ./k8s/deploy-chatservice.yaml>) [Title](<../../../../      >) [Title](<../../../../          aws eks update-kubeconfig --name aws-kubernetes-eks --region us-east-1>) [Title](<../../../../        >) [Title](<../../../../            k8s/deploy-chatservice.yaml>) [Title](<../../../../            k8s/deploy-webapp.yaml>) [Title](<../../../../            klysman08/imersao-chatservice:v${{ github.run_number }}>) [Title](<../../../../            klysman08/imersao-gpt-webapp:v${{ github.run_number }}>)
```

**Links úteis**

Link para o DBeaver:

https://dbeaver.io/download/

Link para a plataforma da OpenAI:

https://platform.openai.com/

Link para o postman:

https://www.postman.com/

