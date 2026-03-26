# Aula-1

```mermaid
sequenceDiagram
participant U as usuario
participant App as aplicativo
particpant bend as backend


U->>App: clicar em endereço
APP->> APP: coordenadas(GPS)
APP->> bend: UserID
APP->>U: requisita novo endereço ou já existente
U->>App:seleciona "pesquisa"
APP->> APP:
APP->> bend:
bend->> banco:
banco-->>bend:
bend-->>app:
app-->>U:
 

sequenceDiagram
participant U as usuario
participant App as aplicativo
particpant bend as backend
