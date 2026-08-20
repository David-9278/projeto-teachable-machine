# Projeto de Visão Computacional - Teachable Machine

## 🎯 Descrição do Modelo
Modelo criado para classificar a postura do usuário em tempo real entre Postura Correta, Postura Errada e Cadeira Vazia.

## 📦 Origem dos Dados
Dados coletados via gravação própria utilizando a webcam do computador (~60 fotos por classe).

## 🔗 Link do Modelo Exportado
[Link do Modelo Hospedado no Teachable Machine]
https://teachablemachine.withgoogle.com/models/YLVXkjjrr/

## 📸 Evidências de Funcionamento
*(Adicione ou anexe aqui os 2 prints tirados durante os testes)*

## 🧠 Reflexão sobre os Resultados
O modelo apresentou uma boa precisão nos testes gerais. Contudo, em alguns momentos de transição de postura rápida ou quando a iluminação do ambiente mudou levemente, ocorreu uma oscilação na confiança das classes. Isso acontece porque a iluminação afeta a distribuição de pixels capturada pela webcam e o dataset inicial possui poucas variações de luz.
