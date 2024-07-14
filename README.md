# Gerador de Senha de 256 Bits

Este projeto é um exemplo de um gerador de senhas de 256 bits em Java. A senha gerada inclui letras maiúsculas, letras minúsculas, números e caracteres especiais para garantir segurança e complexidade.

## Características

- Geração de senha de 256 bits (32 bytes).
- Inclusão garantida de:
  - Letras maiúsculas
  - Letras minúsculas
  - Números
  - Caracteres especiais
- Senha completamente aleatória e embaralhada para maior segurança.

## Requisitos

- Java Development Kit (JDK) 21

## Como Usar

Clone ou baixe este repositório:

## bash
git clone https://github.com/seu-usuario/gerador-senha-256bits.git
cd gerador-senha-256bits

## Explicação do Código
Importações
O código utiliza SecureRandom para gerar números aleatórios de forma segura e classes das coleções (ArrayList e Collections) para manipulação de listas.

## Constantes de Caracteres
Define quatro conjuntos de caracteres (maiúsculas, minúsculas, dígitos e especiais).

## Geração da Senha
Adiciona um caractere aleatório de cada tipo para garantir que a senha inclua todos os tipos de caracteres.
Preenche o restante da senha com caracteres aleatórios dos conjuntos combinados.
Embaralhamento: A senha é embaralhada para garantir que os caracteres estejam distribuídos aleatoriamente.
Saída
Exibe a senha gerada no console.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.



Esse README fornece uma visão geral clara do seu projeto, instruções de uso e informações sobre como contribuir.






