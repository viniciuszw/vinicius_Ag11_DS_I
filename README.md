Controle de Níveis de Água
Um sistema simples de monitoramento de reservatório de água executado no terminal, desenvolvido em Python. O projeto utiliza mensagens de alerta coloridas para indicar diferentes situações de nível de água, empregando a biblioteca colorama.
🚀 Funcionalidades
Monitoramento por Níveis: Simulação de 5 níveis diferentes de água no reservatório (do muito baixo ao muito alto)
.Alertas Coloridos: Uso de cores distintas no terminal para cada nível de risco, facilitando a visualização rápida
.Estrutura Organizada: Código modular utilizando listas de dicionários e funções em Python.
Reset Automático: Restauração do estilo padrão do terminal após a exibição das mensagens.
🛠️ Tecnologias UtilizadasPython 3.x
Colorama (para estilização de cores no terminal)
📋 Tabela de Níveis e Cores
Nível do Reservatório    Situação            Cor Sugerida        
1                   Muito baixo (crítico)       Vermelho (Fore.RED)Nível 2                    Baixo                     Amarelo (Fore.YELLOW)Nível 3                    Médio                      Verde (Fore.GREEN)Nível        4                    Alto                      Ciano (Fore.CYAN)Nível 
5                   Muito alto  (alerta)       Azul (Fore.BLUE)
⚙️ Como Executar o Projeto
Pré-requisitos
Certifique-se de ter o Python instalado em sua máquina.
1. Instale a biblioteca colorama abrindo o seu terminal e executando o comando:
 pip install colorama
2. Executando o Script 
 Baixe ou salve o código do projeto em um arquivo chamado reservatorio.py e execute-o pelo terminal: python reservatorio.py
📁 Estrutura do Código
niveis_reservatorio: Lista contendo dicionários que estruturam os dados de cada nível, descrição da situação e cor correspondente
.exibir_alerta(nivel, situacao, cor): Função dedicada a formatar e imprimir a mensagem no terminal utilizando a cor apropriada
.simular_monitoramento(): Função principal que percorre a lista de níveis e aciona a exibição dos alertas.