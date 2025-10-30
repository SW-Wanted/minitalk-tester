# Minitalk Tester
---
## Como usar
### Clone o repositorio
```bash
git clone https://github.com/SW-Wanted/minitalk-tester.git
```
### Entre no directório
```bash
cd minitalk-tester
```
### Executar
Para rodar o script de teste, utilize o seguinte comando:
```
./tester <PID> [<Repeat>]
```
- `<PID>`: O ID do processo do servidor ao qual o cliente deve se conectar.
- `[<Repeat>]`: (opcional) Número de vezes que o teste será repetido. Se não especificado, o padrão será 10.
### Exemplo
Executar com o PID 12345, repetindo 2 vezes:
- `./tester 12345 2`
