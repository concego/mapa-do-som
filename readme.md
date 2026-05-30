# Mapa do Som 🎵

O **Mapa do Som** é um guia prático, portátil e inclusivo de digitação musical projetado para oferecer autonomia no estudo de instrumentos. Adotando a máxima de **Inclusão acima da Acessibilidade**, a ferramenta entrega uma interface minimalista e de alta eficiência tanto para músicos cegos quanto para pessoas que enxergam.

Esta primeira versão (Demo/MVP) foi construída em um **único arquivo HTML** para garantir fricção zero: não precisa de instalação, roda direto no navegador do celular ou computador e funciona perfeitamente com leitores de tela. Embora seja um MVP do ecossistema geral, ele já entrega um produto completo e pronto para uso real no instrumento proposto.

---

## 💡 O Problema e a Solução

A maioria dos métodos musicais tradicionais depende de diagramas visuais complexos que excluem músicos com deficiência visual. Embora a musicografia Braille seja um divisor de águas indispensável, o fluxo de leitura tátil simultâneo à execução de instrumentos que exigem as duas mãos gera uma barreira ergonômica severa na hora da prática rápida.

O **Mapa do Som** resolve esse gargalo ao traduzir as posições dos dedos em uma **fórmula textual curta, padronizada e de numeração contínua (de 0 a 7)**. O leitor de tela dita apenas os números dos furos a serem fechados de forma direta, otimizando o tempo de resposta, a agilidade do treino e o processo de memorização do músico.

---

## 🛠️ Recursos Atuais do Projeto

- **Interface em Duas Telas:** Fluxo limpo que separa a escolha do instrumento (Tela Inicial) do painel de treino, removendo distrações visuais e ruídos para quem está praticando.
- **Numeração Contínua Otimizada:** Unificação dos furos do instrumento (do 0 ao 7) sem divisão por mãos, gerando uma leitura fluida pelo sintetizador de voz (TTS).
- **Acessibilidade Cirúrgica (Foco Automático):** Ao selecionar uma nota, o leitor de tela é jogado imediatamente para o resultado, ditando a instrução sem exigir varreduras manuais pela tela.
- **Guia Colapsável (Accordion):** A referência de numeração dos dedos fica oculta por padrão, poupando scroll e tempo dos usuários frequentes que já decoraram a lógica.
- **Gráfico SVG Dinâmico Inteligente:** Um mapa visual real da flauta feito em SVG que muda de cor em tempo real para usuários que enxergam. O elemento possui a propriedade `aria-hidden="true"`, o que garante que **o leitor de tela ignore o desenho completamente**, eliminando legendas repetitivas e caracteres alfanuméricos confusos.
- **Escala Barroca 100% Completa:** Banco de dados calibrado com **três oitavas inteiras** da Flauta Doce Barroca (do Dó 4 ao Dó 7), incluindo todos os acidentes (sustenidos e bemóis) e a mecânica de meio furo.

---

## 📈 Próximos Passos (Versão Definitiva em PWA)

A evolução do ecossistema para o produto final incluirá:
1. **Migração para PWA (Progressive Web App):** Permitindo o uso em smartphones de forma nativa e 100% offline.
2. **Expansão de Catálogo:** Inclusão de novos instrumentos (Flauta Germânica, Violão/Guitarra e Teclado).
3. **Laboratório Sonoro:** Integração de arquivos de áudio reais para que o estudante ouça o tom correto de cada nota e calibre seu ouvido.

---

## 👥 Créditos

- **Idealização e Conceito:** [Adri Lima](https://www.instagram.com/adrilima_arte?igsh=YXJ2dHFidjhkZHNj) (Sua experiência prática e insights sobre usabilidade musical foram a faísca e a fundação de toda a lógica sem ruídos deste projeto).
- **Desenvolvimento:** [Anderson Carvalho](https://github.com/concego)
- **Canal Oficial:** Conteúdo e validação sob a chancela da marca **Euconcegojogar**.

---

## 📩 Feedback

A sua opinião é fundamental para moldar o produto final! Se você testou a demo em seu coral, escola de música, universidade ou estudo individual, envie suas impressões para:
📧 **euconcego@gmail.com**
