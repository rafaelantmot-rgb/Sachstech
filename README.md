# SachsTech v0.3

Aplicativo Android de consulta e estudo baseado no catálogo Sachs Brasil CV 06/16.

## O que mudou
- 205 aplicações estruturadas extraídas automaticamente das páginas técnicas.
- 2.646 relações de referência cruzada Montadora/Fabricante x Sachs.
- 43 substituições de códigos.
- Índice textual das páginas do catálogo preservado como fonte.
- Pesquisa por múltiplos termos (todos os termos precisam aparecer nos campos indexados).
- Ficha técnica com veículo, motor, condição, câmbio quando detectado, referências Sachs, diâmetros, estrias e página.
- Modo estudo com perguntas variadas e estatística local.
- Arquitetura preparada para catálogos independentes (Eaton, Plato Diesel etc.).
- GitHub Actions incluído para gerar o APK pelo celular, sem Android Studio.

## Gerar APK pelo celular
1. Crie um repositório vazio no GitHub.
2. Envie todos os arquivos desta pasta para o repositório.
3. Abra a aba **Actions** e execute **Build SachsTech APK**.
4. Ao terminar, abra a execução e baixe o artefato **SachsTech-debug-apk**.
5. Extraia o ZIP do artefato e abra `app-debug.apk` no Android.

A base estruturada é uma extração automática e deve ser validada antes de uso como fonte exclusiva para venda/decisão técnica. A página de origem permanece disponível no app para conferência.
