# Aula-1

```mermaid
sequencaDiagram
participant U as uauario
partincipan App as aplicativo
particpant bend as backend
participant

U->>App: clicar em endereço
APP->> APP: coordenadas(GPS)
APP->> bend: UserID
APP->>U: requisita novo endereço ou existente
U->>App:seleciona "pesquisa"
APP->> APP:
APP->> bend:
bend->> banco:
banco-->>bend:
bend-->>app:
app-->>U:
