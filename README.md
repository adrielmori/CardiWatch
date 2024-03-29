# Desenvolvimento de um Sistema Integrado para Previsão de Peso com Base em Dados Multiparamétricos: Uma abordagem utilizando Gêmeo Digital e Aprendizagem de Máquina.

## Uma descrição do domínio de aplicação
O domínio da aplicação proposta está centrado na monitorização da saúde e previsão de peso corporal de usuários por meio da integração de dados multiparamétricos coletados por uma balança inteligente e um dispositivo vestível. Esse sistema visa permitir a análise temporal desses dados, apresentando informações em dashboards em diversos dispositivos. 

## Uma descrição das funcionalidades do sistema ou aplicação proposta
Este estudo propõe o desenvolvimento de uma aplicação voltada para a monitorização da saúde e previsão do peso de indivíduos, utilizando uma combinação de tecnologias, incluindo uma balança digital e um smartwatch. O objetivo principal é estabelecer uma relação ubíqua entre as variáveis multiparamétricas registradas pelo smartwatch e o peso corporal do usuário em uma relação temporal do comportamento de seus dados multiparamétricos, relacionados à variação do peso corpóreo avaliado em passos de tempo de 24 horas (um dia). As informações coletadas serão persistidas em um banco de dados para facilitar a análise retrospectiva e o treinamento de modelos de aprendizado de máquina.

A funcionalidade central do sistema proposto consiste na concepção de uma aplicação ubíqua, na qual usuários que dispõem de uma balança inteligente e um dispositivo vestível para a coleta multiparamétrica de dados de saúde podem integrar essas informações simultaneamente. Tais dados serão persistentemente armazenados em um banco de dados. Ao serem avaliados temporalmente, esses dados serão apresentados de maneira pervasiva em dashboards em diferentes dispositivos. A persistência desses dados possibilitará a aplicação de técnicas avançadas de aprendizado de máquina, particularmente na competência de previsão de séries temporais com covariáveis. Os dados multiparamétricos persistentes serão utilizados como features de aprendizado, enquanto o peso no dia seguinte será o rótulo associado a cada dia específico.

Nesse contexto, torna-se imperativo a aplicação de técnicas fundamentadas no paradigma de gêmeo digital, no qual é simulado, com base nos dados personalizados do usuário, a geração do gêmeo digital preditivo da perda de peso do usuário. Essa simulação é conduzida com consideração ao critério temporal, permitindo que o usuário antecipe virtualmente sua perda de peso após um determinado número de dias como entrada.

Esse cenário adquire relevância significativa para profissionais da área de nutrição e nutrólogos, oferecendo uma ferramenta valiosa para tomadas de decisões embasadas em informações preditivas e personalizadas sobre a evolução do peso corporal do usuário ao longo do tempo.

## Link para os códigos

### Gemeo Digital 
https://github.com/adrielmori/model_SARIMAX_cardiWatch

### Aplicativo android 
https://github.com/adrielmori/INF0306

### Aplicativo smartWatch 
https://github.com/igorpadua/cardiSmartWatch
