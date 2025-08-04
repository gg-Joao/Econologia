# 📋 Descrição das Classes - Sistema Econologia

## 👤 **Usuario**
Classe principal que representa todos os usuários do sistema. Armazena dados pessoais como nome, email, senha, telefone e endereço. Mantém controle da pontuação acumulada através das atividades de reciclagem e define o tipo de usuário (cidadão, cooperativa ou administrador) através do atributo tipoUsuario.

## 🏢 **Cooperativa**
Representa as empresas e organizações parceiras responsáveis pela coleta de materiais recicláveis. Contém informações institucionais como razão social, CNPJ e dados de contato. Gerencia múltiplos pontos de coleta e executa os agendamentos solicitados pelos usuários.

## 🗑️ **Residuo**
Cataloga os diferentes tipos de materiais recicláveis aceitos pelo sistema. Define características específicas de cada resíduo, incluindo seu status, categoria de classificação, nível de perigo para manuseio e instruções detalhadas para descarte correto.

## 📍 **PontoColeta**
Representa locais físicos onde os usuários podem descartar seus materiais recicláveis. Armazena informações de localização (endereço, telefone), horários de funcionamento e tipo de ponto, permitindo que usuários encontrem locais próximos para descarte.

## 📅 **Agendamento**
Gerencia as solicitações de coleta domiciliar feitas pelos usuários. Controla datas de agendamento e coleta efetiva, observações especiais e status atual da solicitação, servindo como ponte entre usuário e cooperativa.

## 🚛 **Coleta**
Registra a execução concreta das coletas de materiais recicláveis. Documenta informações operacionais como data da coleta, peso dos materiais coletados, pontos atribuídos ao usuário e observações sobre o processo, além do status da operação.

## 🎁 **Recompensa**
Define os prêmios e benefícios disponíveis no sistema de gamificação. Especifica título, descrição, quantidade de pontos necessários para resgate, tipo de recompensa oferecida, prazo de validade e disponibilidade atual no sistema.

## 🧠 **Quiz**
Implementa a funcionalidade educativa do sistema através de questionários interativos sobre práticas de reciclagem. Contém título, descrição, pontuação de recompensa oferecida e limite de tempo para conclusão, promovendo conscientização ambiental.

## 📊 **HistoricoColeta**
Mantém registro histórico completo das atividades de reciclagem de cada usuário. Armazena dados consolidados como data, peso total coletado e pontos ganhos, permitindo acompanhamento de desempenho e geração de relatórios de progresso.

## 🏷️ **Enumerações**

### **TipoUsuario**
Define os perfis de acesso ao sistema: cidadão (usuários comuns), cooperativa (organizações parceiras) e administrador (gestores do sistema).

### **TipoStatus** 
Controla os estados dos agendamentos: pendente (aguardando confirmação), confirmado (aceito pela cooperativa), coletado (finalizado com sucesso) e cancelado (interrompido).

### **TipoStatus (Coleta)**
Gerencia as fases operacionais da coleta: agendada (programada), em andamento (sendo executada), finalizada (concluída com sucesso) e cancelada (interrompida).

### **TipoRecompensa**
Categoriza os tipos de prêmios oferecidos: desconto (reduções em produtos/serviços) e produto (itens físicos para resgate).

### **TipoCategoria**
Classifica os materiais recicláveis aceitos: orgânico, papel, plástico, vidro, metal, eletrônico, perigoso e óleo, facilitando identificação e separação adequada.
