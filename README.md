# 🔢 Jogo do Número Secreto
**🎮 Jogue online:** https://jogo-do-numero-secreto-one-gamma-80.vercel.app/

Um jogo interativo onde o jogador adivinha um número aleatório, com síntese de voz e prevenção de repetição de números. Desenvolvido como projeto do curso lógica de programação.  

## 🎥 Demonstração  
![Demonstração do Jogo do Número Secreto](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExdHRkZ3ptM2U3dnZyY2piMzA4M29ocnRwdXozemtzMW9sYmRwa2NrOCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/BXCSpADXroZoQ59hXR/giphy.gif)  
*(GIF mostrando o fluxo completo: chute do jogador → tela de vitória)*  

---

## ✨ Recursos Destacados  
✅ **Sistema de voz integrado**  
- Feedback auditivo usando a biblioteca ResponsiveVoice  
- Locução em português com ajuste de velocidade  

✅ **Lógica avançada de sorteio**  
- Números nunca se repetem até que todos sejam usados  
- Reinício automático da lista ao atingir o limite (1-100)  

✅ **Interface dinâmica**  
- Mensagens personalizadas (singular/plural de "tentativa")  
- Botão de reinício inteligente  

## 🛠️ Tecnologias Usadas  
- HTML5, CSS3, JavaScript Vanilla  
- Biblioteca ResponsiveVoiceJS  
- `Math.random()` com tratamento especial  

## ⚙️ Como Funciona  
1. `gerarNumeroAleatorio()` cria um número único  
2. `verificarChute()` dá feedback por voz/texto  
3. Reinício automático ao acertar  

## 🚀 Como Executar  
```bash
# Localmente:
git clone https://github.com/seu-user/repo.git
cd repo
open index.html
```

---
Feito com 💙 por **LARISSA PANISSET** | Aluna ONE  
