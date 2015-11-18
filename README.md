# buzzumAndroid
Buzzum de Programação de dispositivos moveis
BUZZUM – Padrões de Projeto

Geral:
Chamada de Activities via Intent (pelo menos uma com parâmetros) 
- Cada botao da tela principal carrega outra activity. VICTOR
- A passaggem de parametro sera atraves do box de pesquisa usando Bandle.VICTOR


Pelo menos um Menu de cada tipo (Options, Context e Popup); RICARDO
- Options na tela principal com as mesmas opções da tela inicial.
- Context para editar ou excluir o ponto do onibus.  
- Popup confirmar delete dos pontos 
Interface Gráfica:
Pelo menos tres tipos de Layouts;
- Linear, relative dentro do outro na pagina principal
- ScrowView para lista dos pontos e horarios.
Pelo menos um Fragmento com tratamento de eventos na activity principal (inner interface);
		- Mostrar o mapa da rota do bus.  

Pelo menos 8 tipos de componentes gráficos, sendo um deles uma lista com Adapter;
- Lista horario de uma linha igual usado na prova para listar as musicas.
Botao, Edit text, Imagem Buttom, map, Imagem View, Adapter, textView, Text.
Persistência de Dados:
SQLite com pelo menos um CRUD completo; 
- Salvar rotas favoritas. 
SharedPreferences;
- Configurações gerais. 
CRUD com acesso a uma API remota (REST); (sugestão scaffold rails);
- Cadastro de pontos.
Notificações;
- Notificar quando estiver perto do seu ponto. 
Serviço em Segundo plano (pode ser utilizado em conjunto com as notificações);
- Notificar quando estiver perto do seu ponto. 
Pelo menos uma caixa de Diálogo (Dialog).
- Deseja salvar em favoritos ? 
- Pensar





Proximo ponto e achados perdidos– Ricardo
Cadastro de pontos
Cadastro de objetos

Proximo onibus e favoritos
Cadastro de horarios e linhas 
Cadastro dos favoritos
