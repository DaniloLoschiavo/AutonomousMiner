# AutonomousMiner
# Problema:
	Normalmente as aplicações de mineração de criptomoedas é desenvolvida para usar uma quantidade determinada de processos pré definida ou até total disponível, consumindo totalmente o potencial do computador.
Em computadores domésticos pode se tornar muito incômodo manter a execução de mineradores durante sua utilização, pois causa lentidão extrema no equipamento, resultando em ter de parar a execução e se quiser diminuir o número de processos para executar novamente, para assim ter recursos disponíveis para uma utilização mais fluida.
# Justificativa:
	Durante uma utilização comum dificilmente utilizamos 100% do processamento do computador, que pode ser considerado até um desperdício de recursos, portanto esses recursos não utilizados poderiam estar sendo utilizados dinamicamente por algo que pode ser lucrativo. 
	Com a rápida evolução da tecnologia, os hardwares estão ficando cada vez mais potentes e acessíveis, onde usuários comuns podem nunca chegar a utilizar todo o potencial do equipamento.
# Objetivo: 
	A ideia consiste em desenvolver uma solução onde o minerador é controlado dinamicamente, sem intervenção do usuário, baseado-se nos recursos disponíveis do equipamento, podendo até ser aplicado “Machine Learning” para que a aplicação aprenda os horários, e o potencial  da utilização para que ajuste automaticamente o uso do processador prevendo a utilização do usuário.
	Assim os recursos que seriam desperdiçados estariam sendo utilizados dinamicamente tendo retorno lucrativo por eles sem preocupação do usuário.
# Projeto:
	Para o desenvolvimento do projeto será necessário utilizar o protocolo “stratum tcp” que consistem em um padrão utilizado pelos pools de mineração juntamente com criptografia “SHA256d” para processar as solicitações. 
	Para monitorar o processamento do computador será utilizado o módulo “psutil” para coletar o nível de uso do processado juntamente com  o “TensorFlow” que dispões de uma biblioteca de “Machine Learning”
