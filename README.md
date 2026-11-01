# English Pro 2

App de cards para estudar inglês do dia a dia, otimizado para iPhone.
Abra em https://matheus151.github.io/Learning-english/ e, no Safari, toque em **Compartilhar → Adicionar à Tela de Início**.

## O que faz

- **Cards empilhados**: cada card tem uma frase principal e exemplos.
- **Ouvir** qualquer frase, ou o card inteiro, com as vozes nativas do iPhone.
- **Traduzir** qualquer frase em inglês, o card inteiro, ou ligar "mostrar todas as traduções".
- **Negrito ao deslizar**: passe o dedo sobre uma ou mais palavras para destacar (deslize de novo para tirar).
- **Contexto**: toque numa palavra (ou numa expressão em negrito) para ver o significado naquela frase, explicação e novas frases de exemplo, e salvar em **Termos**.
- **Novos exemplos**: 1 frase nova com o mesmo termo e 3 com os substitutos indicados na tela de contexto.
- **Vocabulário**: dicas por campo (família, casa, comida… e campos seus), cada uma aplicada a uma frase, com "Mais exemplos".
- **Criar cards colando frases**, uma por linha. Frases incompletas ou sem contexto são completadas pela IA, e as palavras originais ficam em negrito.
- **Revisar** com repetição espaçada (EN → PT ou PT → EN), para cards e termos.
- **Apagar** card, exemplo ou termo, sempre com "Desfazer".
- **Tema** (auto, claro, escuro, sépia), **tamanho da fonte** e cor de destaque.
- **Backup** em .json pelo menu de compartilhar do iPhone (Arquivos, iCloud…) e restauração.
  Também aceita backups da versão antiga.

## IA

Exemplos, contexto e completar frases usam, nesta ordem, as IAs disponíveis: Gemini, Groq, OpenRouter, Claude e uma IA grátis sem chave (pollinations.ai, 1 resposta a cada 30 segundos).
Se uma atingir o limite ou falhar, o app passa sozinho para a próxima. As chaves ficam só no aparelho (Ajustes → IA) e não vão no backup.
Sem nenhuma IA disponível, tradução e dicionário básico continuam funcionando.

## Versões antigas

Na primeira abertura, os cards da V38 (`englishCardsFinalV38_8`) são migrados automaticamente.
A primeira frase de cada card vira a frase principal e as demais viram exemplos.
Os dados antigos não são apagados. A V38 continua disponível em `v38.html`, e as versões anteriores continuam nos arquivos `index *.html`.
