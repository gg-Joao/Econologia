# Casos de Uso Principais do Sistema Econologia

## **1. Localizar Pontos de Coleta Próximos**  
### **Atores Envolvidos**  
- Usuário (morador urbano)  
- Sistema de geolocalização  

### **Fluxo Principal**  
1. Usuário abre o aplicativo e seleciona "Pontos de Coleta".  
2. Sistema solicita permissão para acessar localização.  
3. Usuário autoriza e seleciona o tipo de material (ex.: vidro, eletrônicos).  
4. Sistema exibe mapa com pontos de coleta próximos (filtrados por material).  
5. Usuário escolhe um ponto e visualiza detalhes (horário, endereço).  

### **Fluxos Alternativos**  
- **Sem permissão de localização:** Usuário insere endereço manualmente.  
- **Nenhum ponto próximo:** Sistema sugere coleta domiciliar ou centros distantes.  

### **Pré-condições**  
- Aplicativo instalado e usuário logado.  

### **Pós-condições**  
- Usuário obtém informações para descarte correto.  



## **2. Agendar Coleta Domiciliar**  
### **Atores Envolvidos**  
- Usuário  
- Cooperativa de reciclagem (parceira)  

### **Fluxo Principal**  
1. Usuário acessa "Agendar Coleta".  
2. Sistema lista materiais aceitos (ex.: papel, plástico).  
3. Usuário seleciona materiais e quantidade.  
4. Sistema exibe datas disponíveis; usuário escolhe horário.  
5. Confirmação é enviada ao usuário e à cooperativa.  

### **Fluxos Alternativos**  
- **Material não reciclável:** Sistema alerta e sugere alternativas.  
- **Sem datas disponíveis:** Notifica usuário para tentar outro período.  

### **Pré-condições**  
- Usuário cadastrado e residência em área atendida.  

### **Pós-condições**  
- Coleta agendada e registrada no sistema.  


## **3. Resgatar Recompensas por Reciclagem**  
### **Atores Envolvidos**  
- Usuário  
- Sistema de recompensas (parcerias com comércios locais)  

### **Fluxo Principal**  
1. Usuário acumula pontos ao descartar materiais.  
2. Acessa "Recompensas" e visualiza opções (ex.: descontos).  
3. Seleciona recompensa e resgata com pontos.  
4. Sistema gera cupom ou código.  

### **Fluxos Alternativos**  
- **Pontos insuficientes:** Sugere ações para acumular mais (ex.: quizzes).  
- **Recompensa esgotada:** Oferece alternativas.  

### **Pré-condições**  
- Usuário com pontos acumulados.  

### **Pós-condições**  
- Recompensa resgatada e pontos deduzidos.  

