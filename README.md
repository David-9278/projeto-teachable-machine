# Projeto de Visão Computacional - Teachable Machine

## Descrição do Modelo
Modelo de classificação de imagem desenvolvido para reconhecer gestos de mão correspondentes ao jogo "Pedra, Papel e Tesoura". O modelo analisa as entradas em tempo real via webcam e classifica o gesto em três categorias distintas: Pedra (mão fechada), Papel (mão aberta) e Tesoura (dois dedos estendidos).

## Origem dos Dados
Dados coletados via gravação própria utilizando a webcam do computador (~60 fotos por classe, focando exclusivamente nos gestos das mãos).

## Link do Modelo Exportado
- [Modelo Hospedado no Teachable Machine](https://teachablemachine.withgoogle.com/models/YLVXkjjrr/)

## Evidências de Funcionamento

<img width="1288" height="863" alt="Captura de tela de 2026-08-19 22-20-44" src="https://github.com/user-attachments/assets/281db8d3-fac0-4ea1-84e2-f394b47f0607" />
<img width="1752" height="854" alt="Captura de tela de 2026-08-19 22-22-20" src="https://github.com/user-attachments/assets/1dce08e5-e5b3-47d1-af77-b7f22fef6e0e" />
<img width="1776" height="860" alt="Captura de tela de 2026-08-19 22-22-39" src="https://github.com/user-attachments/assets/6ea4d441-9487-4d67-962e-71a2a22e8a40" />
<img width="1769" height="860" alt="Captura de tela de 2026-08-19 22-23-02" src="https://github.com/user-attachments/assets/09d411a5-f413-4bd3-a606-f49f29d4b719" />

## Reflexão sobre os Resultados!

O modelo teve precisão ao identificar os três gestos de mão. Contudo, em momentos de transição rápida entre os gestos ou quando a mão ficou muito próxima da borda do enquadramento, ocorreu uma leve oscilação na porcentagem. Isso acontece porque pequenas alterações de ângulo e iluminação mudam a distribuição de pixels capturada pela webcam, mostrando como a padronização dos dados interfere na inferência da IA.
