# Sistema_De_Educação_Financeira

# 1. Planejamento Geral
  - Objetivo principal: Criar uma ferramenta de apoio à educação financeira para a comunidade
  - Publico-alvo: jovens, adultos e familias que queiram aprender a organizar melhor suas finanças.
  - Entrega: Aplicativo completo em python com banco de dados, interface e funcionalidades.

# 2. Estrutura do projeto
  - educação_financeira
  - |
  - |--main.py                # Arquivo principal  da aplicação
  - |--banco.py               # Conexão e manipulacão do banco de dados SQLite
  - |--interface.py           # Interface gráfica com Tkinter ou Kivy
  - |--funcoes.py             # Funções principais(cadastro, calculos, simulação etc.)
  - |--dados.db               # Banco de dados SQLite
  - |--relatorios/            # Exportações de relatorios (opcionais)

# 3. Funcionalidades por Etapas
  - # A. Estrutura básica
      -  Tela de Login e cadastro de usuários
      -  Menu principal com opções:entradas, Saídas, Relatórios, simulador de Metas, Dicas.

  - # B. Banco de dados
      - Tabelas:
       -  Usuarios (id, nome, email, senha)
       -  Entradas (id, user_id, valor, tipo, data)
       -  Saidas (id, user_id, valor, tipo, data)
     
 - # C. Registro de Movimentações
    - Tela para registrar entradas financeiras (ex: salário, bico, etc.).
    - Tela de adicionar saída (ex: aluguel, comida).
    
 - # D. Relatórios e gráficos
     - Relatório mensal simples (total recebido, total gasto, saldo).
     - Gráfico de barras (Matplotlib) para mostrar os dados.
  
 - # E. Dicas financeiras
   - Baseado no saldo, mostrar mensagens como
       - “Você está gastando mais do que ganha. Cuidado!”
       - “Boa! Seu saldo foi positivo este mês.”
    
 - # F. Simulador de metas
   - Campo: meta (ex: R$ 1000), meses (ex: 6)
   - Calcular: quanto guardar por mês (meta / meses)

# 4. Orientação para Relatóro Final
  
