# Hanon
Este script Python realiza operações de escaneamento de rede, incluindo recuperação de IP, varredura de portas e detecção de vulnerabilidades usando o Nmap.

## Pré-requisitos

- Python 3.x
- [Nmap](https://nmap.org/) instalado e no caminho do sistema

## Como Usar

1. Clone este repositório ou baixe o script.

2. Instale a biblioteca necessária usando o pip:

   ```bash
   pip install python-nmap
   
##Uso: 
Clone este repositório:
```bash
git clone https://github.com/K1R4-H4CK3R/Hanon/
```
Navegue até o diretório do projeto:
```bash
cd Hanon 
```
Execute o script usando o comando:
```bash
python Fsec-anavuln.py
```
##Funcionalidades:
banner():Mostra um banner estilizado no início da execução.
get_ip(site): Obtém o endereço IP associado ao site alvo.
scan_ports(site): Varre as portas do site alvo e retorna as portas abertas.
scan_vulnerabilities(site): Varre o site alvo em busca de vulnerabilidades.
Exemplo de Uso# Executando a função principal
```bash
if __name__ == "__main__":
    main()
```
##Contribuição:
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
##Observações:
Este script faz uso da biblioteca socket para resolver o nome do site para um endereço IP.Utiliza a biblioteca nmap para varredura de portas e detecção de vulnerabilidades.Lembre-se de usar este script de forma ética e em conformidade com todas as leis e regulamentos aplicáveis.
