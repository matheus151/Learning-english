# English Pro 2

App de cards para estudar inglês do dia a dia, otimizado para iPhone.
Abra em https://matheus151.github.io/Learning-english/ e, no Safari, toque em **Compartilhar → Adicionar à Tela de Início**.

## O que faz

- **Cards empilhados**: cada card tem uma frase principal e exemplos.
- **Ouvir** qualquer frase, ou o card inteiro, com as vozes nativas do iPhone.
- **Traduzir** qualquer frase em inglês, o card inteiro, ou ligar "mostrar todas as traduções".
- **Negrito ao deslizar**: passe o dedo sobre uma ou mais palavras para destacar (deslize de novo para tirar).
- **Contexto**: toque numa palavra (ou numa expressão em negrito) para ver o significado naquela frase, explicação e novas frases de exemplo, e salvar em **Termos**.
- **Novos exemplos**: gera frases do dia a dia com sentido parecido.
- **Criar cards colando frases**, uma por linha. Frases incompletas ou sem contexto são completadas pela IA, e as palavras originais ficam em negrito.
- **Revisar** com repetição espaçada (EN → PT ou PT → EN), para cards e termos.
- **Apagar** card, exemplo ou termo, sempre com "Desfazer".
- **Tema** (auto, claro, escuro, sépia), **tamanho da fonte** e cor de destaque.
- **Backup** em .json pelo menu de compartilhar do iPhone (Arquivos, iCloud…) e restauração.
  Também aceita backups da versão antiga.

## IA

Exemplos, contexto e completar frases usam o **Gemini** (chave grátis em https://aistudio.google.com/apikey)
ou o **Claude**. A chave fica salva só no aparelho (Ajustes → IA). A chave do Gemini da versão antiga é reaproveitada.
Sem chave, tradução e dicionário básico continuam funcionando.

## Versões antigas

Na primeira abertura, os cards da V38 (`englishCardsFinalV38_8`) são migrados automaticamente.
A primeira frase de cada card vira a frase principal e as demais viram exemplos.
Os dados antigos não são apagados. A V38 continua disponível em `v38.html`, e as versões anteriores continuam nos arquivos `index *.html`.
