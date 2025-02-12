# jenkins-test-flow

Este repositorio contiene la configuración para ejecución del pipeline.

## Uso
Ejecuta el pipeline en Jenkins con la configuración deseada.

## Ejemplo configuracion

{
  "apis": [
    {
      "name": "api1",
      "baseUrl": "https://api1.example.com",
      "scenarios": [
        { "method": "GET", "path": "/endpoint1", "contentType": "application/json" },
        { "method": "POST", "path": "/endpoint2", "contentType": "application/json", "body": "{ \"key\": \"value\" }" }
      ]
    }
  ]
}
