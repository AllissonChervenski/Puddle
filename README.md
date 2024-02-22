# Django Marketplace

O Django Marketplace é um projeto de marketplace desenvolvido usando o framework Django. Ele fornece uma plataforma para usuários comprarem e venderem produtos online.

## Recursos Principais

- Registro de usuário e autenticação.
- Listagem de produtos com detalhes e preço.
- Contato de vendedor/interessado.
- Painel de administração para gerenciamento de produtos e pedidos.

## Configuração do Ambiente

1. **Pré-requisitos:**
   Certifique-se de ter o Python e o Django instalados em sua máquina.

2. **Clone o repositório:**
   ```bash
   git clone https://github.com/AllissonChervenski/Puddle.git
   cd Puddle
   ```

3. **Configuração do Ambiente Virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # Ou
   .\venv\Scripts\activate  # Windows
   ```

4. **Configuração do Banco de Dados:**
   ```bash
   python manage.py migrate
   ```

5. **Execute o Servidor de Desenvolvimento:**
   ```bash
   python manage.py runserver
   ```

6. **Acesse a Aplicação:**
   Abra o navegador e acesse `http://127.0.0.1:8000/`.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para obter mais detalhes.
