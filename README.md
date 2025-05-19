# 🏢 Tesselas Negócios Global

Este repositório faz parte da **Rede Tesselar de Conhecimento (RTK)** e tem como objetivo armazenar tesselas colaborativas sobre estabelecimentos comerciais, serviços e empreendimentos de diferentes cidades e regiões.

> As tesselas são arquivos `.md` que contêm informações estruturadas, geolocalizadas e otimizadas para uso por assistentes pessoais inteligentes (como o RTKServer).

---

## 📘 O que é uma Tessela de Negócio?

Uma *tessela* representa um tópico específico — como padarias, oficinas, restaurantes ou qualquer outro tipo de serviço em uma cidade/estado — e pode conter:

- Nome do estabelecimento  
- Endereço e telefone  
- Especialidades ou serviços oferecidos  
- Links, horários e observações  

---

## 🗂️ Estrutura de Arquivos

Os arquivos devem seguir este padrão de nome:


### Exemplos:

- `tessela_padarias_bm_rj.md`
- `tessela_lanchonetes_santos_sp.md`
- `tessela_petshops_bh_mg.md`

---

## 💡 Exemplo de Tessela

```markdown
# Padarias em Barra Mansa - RJ

## 🍞 Padaria Doce Massa
- 📍 Endereço: Av. das Flores, 250
- ☎️ Telefone: (24) 88888-1111
- ⭐ Destaques: Pão francês, Sonho, Donuts
- 💳 Aceita Pix e cartão

## 🥐 Padaria Central
- 📍 Rua A, nº 100
- ☎️ (24) 99999-0000
- ⏰ Aberta das 6h às 20h
- 🧠 Wi-Fi disponível
Como o RTKServer usa este repositório?
Quando um usuário faz uma pergunta relacionada a estabelecimentos, o RTKServer busca por tesselas locais.

Se não encontrar localmente, sincroniza automaticamente este repositório via GitHub.

A tessela é copiada para TESSELAS_negocios_local e armazenada offline.

Caso a tessela não exista nem remotamente, o RTKServer pode criar uma nova baseada na pergunta e resposta.

🤝 Como contribuir
Faça um fork deste repositório.

Crie ou edite tesselas .md com informações úteis.

Garanta que a formatação seja clara e organizada.

Envie um Pull Request para revisão.

Sinta-se à vontade para compartilhar conhecimento útil sobre qualquer tipo de negócio de qualquer cidade.

📌 Regras de nomeação
Use letras minúsculas, sem acentuação ou espaços, separados por sublinhado. Exemplo:

Copiar
Editar
tessela_padarias_bm_rj.md
Onde:

padarias é o tipo de negócio

bm é a sigla da cidade (Barra Mansa)

rj é a sigla do estado

🛡️ Licença
Este projeto está licenciado sob a Licença MIT.
Você é livre para usar, copiar, modificar e distribuir com atribuição.

🌍 Projetos relacionados
📚 Tesselas User Global – Conhecimento geral, cultura, turismo etc.

🧠 RTKServer – Servidor pessoal de IA que utiliza estas tesselas.

