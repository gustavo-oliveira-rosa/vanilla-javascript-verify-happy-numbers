# 🧠 Verificador de Números Felizes

![Status](https://img.shields.io/badge/Status-Funcionando-brightgreen)
![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JS%20Vanilla-blue)
![License](https://img.shields.io/badge/Licença-MIT-lightgrey)

Aplicação **100% client-side** para verificar se um número é **feliz** e listar todos os números felizes até um limite escolhido. Interface moderna, responsiva e sem dependências externas.

---

## ✨ Recursos

- ✅ **Verificação individual** com opção de exibir a **sequência de transformação**  
- 📚 **Histórico (10 últimos)** salvo no **LocalStorage**  
- 📈 **Listagem por intervalo** (encontre todos os felizes ≤ N)  
- ⚡ **Desempenho otimizado** com **memoization**  
- 🖥️ **Responsivo e acessível** (teclado/aria)  
- 🔒 **Sem backend**: tudo acontece no navegador

---

## 🧮 O que é um número feliz?

Um número é **feliz** se, ao substituir o número pela **soma dos quadrados de seus dígitos** repetidamente, a sequência **converge para 1**.  
Se a sequência entrar em **ciclo** que não contém 1, o número é **infeliz**.

Ex.: `19 → 1² + 9² = 82 → 8² + 2² = 68 → 6² + 8² = 100 → 1² + 0² + 0² = 1` ✅

---
