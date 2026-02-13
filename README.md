# Condicionais-IF..else-IF..else-IF-no-JS

📌 Visão Geral

Este projeto é um protótipo de controle de acesso para a portaria da TechZone.
A aplicação valida se um colaborador pode entrar no prédio com base em dois critérios obrigatórios: identificação pelo nome e horário de chegada.

O sistema roda no navegador e mantém os dados apenas durante a execução da página.

⚙️ Regras de Negócio

O acesso só é liberado quando todas as condições abaixo são verdadeiras:

O nome informado precisa existir na lista de colaboradores autorizados.

A entrada deve ocorrer antes das 22h.

Se qualquer uma falhar, a entrada é recusada.

🧠 Como Funciona

Um array guarda os nomes permitidos.

O usuário informa nome e hora usando prompt().

O método .includes() verifica se a pessoa está cadastrada.

Estruturas condicionais determinam a resposta final.

O retorno é exibido via console.log().

✅ Possíveis Resultados

Acesso Permitido → nome válido e dentro do horário.

Acesso Negado: Usuário não cadastrado → nome fora da lista.

Acesso Negado: Fora do horário permitido → após as 22h.

🎯 Objetivos de Aprendizagem

O exercício foi construído para treinar:

manipulação de arrays

comparação de valores numéricos

uso de if/else

aplicação de operadores lógicos para combinar regras
