# FydelisTech-Whois

Uma ferramenta simples e eficiente para consulta de dados WHOIS de domínios e endereços IP

📋 Descrição
O FydelisTech-Whois é um projeto desenvolvido para facilitar a obtenção de informações detalhadas sobre domínios da internet e endereços IP. Ele consulta bancos de dados públicos de registro (como a ICANN, LACNIC, RIPE, entre outros) e retorna dados como:

Titular do domínio ou responsável pelo IP
Data de registro e vencimento
Servidores DNS configurados
Informações de contato e registro
Status do domínio (ativo, suspenso, expirado)

É ideal para desenvolvedores, administradores de redes, analistas de segurança e qualquer pessoa que precise verificar detalhes sobre recursos na internet.

🚀 Funcionalidades

✅ Consulta de dados WHOIS para domínios (ex: .com, .br, .net, .org e outras extensões)

✅ Consulta de dados WHOIS para endereços IPv4 e IPv6

✅ Saída formatada e fácil de ler

✅ Compatível com os principais registradores e entidades de registro globais

✅ Código leve, de fácil compreensão e personalizável

✅ Sem dependências complexas para instalação

💻 Tecnologias Utilizadas
Linguagem: [Você pode adicionar aqui, ex: Python, JavaScript, PHP]
Bibliotecas/APIs: [Ex: python-whois, APIs públicas de registro, ou implementação própria de consulta]
Compatibilidade: Windows, Linux, macOS

📦 Instalação

Clone o repositório:
bash
Run
git clone https://github.com/fydelis2025/FydelisTech-Whois.git

Acesse a pasta do projeto:
bash
Run
cd FydelisTech-Whois
[Se houver dependências, adicione aqui o comando, ex: pip install -r requirements.txt]

▶️ Como Usar
Exemplo básico:
bash
Run
# Exemplo para consulta de domínio
nome_do_comando consultar exemplo.com.br

# Exemplo para consulta de IP
nome_do_comando consultar 8.8.8.8

Saída esperada:
plaintext
=== Dados WHOIS para exemplo.com.br ===
Registrante: Empresa Exemplo LTDA
Data de registro: 2020-05-12
Data de vencimento: 2027-05-12
Servidores DNS:
  - ns1.exemplo.com
  - ns2.exemplo.com
Status: Ativo
Contato: registro@exemplo.com.br

💡 Você pode personalizar a saída ou adicionar filtros diretamente no código-fonte

🤝 Como Contribuir

Contribuições são sempre bem-vindas! Para colaborar:

Faça um fork do projeto
Crie uma branch para sua funcionalidade ou correção: git checkout -b minha-nova-funcionalidade
Faça suas alterações e commit: git commit -m 'Adiciona nova funcionalidade X'
Envie para a branch original: git push origin minha-nova-funcionalidade
Abra um Pull Request
Regras de contribuição:
Siga o padrão de código do projeto
Atualize a documentação sempre que necessário
Descreva claramente o que foi alterado no Pull Request

📞 Contato

Desenvolvedor: fydelis2025GitHub: 
https://github.com/fydelis2025
Projeto: https://github.com/fydelis2025/FydelisTech-Whois

⭐ Se este projeto foi útil para você, deixe uma estrela no repositório!
