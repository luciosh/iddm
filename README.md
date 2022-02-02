# IDDM
IoT Device Detection Model with deNATing and classification algorithms
Este repositório foi construído como base para a produção do projeto de conclusão do curso de bacharelado em Engenharia de Computação pela Universidade Federal de Mato Grosso. 
### Algorithms:  Neural Decision Forest (NDF) and Ligth Gradient Boost Machine (LGBM)

#### O objetivo do trabalho foi comparar o desempenho dos algoritmos NDF e LGBM na classificação de dispositivos através do deNating, utilizando a base de dados criada e apresentada no seguinte trabalho: https://www.sciencedirect.com/science/article/pii/S0167404820302418.

### Problemática:
A quantidade de dispositivos IoT presentes nas casas têm aumentado de maneira exponencial. Por diversos fatores, estes dispositivos são extremamente atraentes para serem utilizados como porta de entrada para invasões em redes domésticas. Fatores que contribuem pra isso, englobam desde a capacidade computacional desses dispositivos até as falhas do usuário em não substituir login e senha padrão dos mesmos. Contudo, essa brecha não põe apenas a rede doméstica em risco, sendo prejudicial também para a empresa de telecomunicação que fornece o serviço de internet para o usuário invadido. Por isso, o método de detecção desse trabalho tem como base de operacionalização a infraestrutura da telco, os dados são coletados por um equipamento de rede com capacidade  de organizá-los em fluxos, já depois de passarem pelo NAT, e a partir desses dados o desafio é gerar um modelo capaz de detectar qual dispositivo está instalado na casa do cliente, sabendo disso é possível verificar se algum dispositivo utilizado pelo cliente está em alguma lista de vulnerabilidades, informá-lo e evitar uma brecha crítica na borda dessa rede. 
