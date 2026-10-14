# Desenvolvimento Responsivo e Debugging com WordPress + Elementor

> Estudo de caso técnico sobre construção de landing page, personalização com HTML/CSS, responsividade e resolução de problemas de renderização.

## Sobre o projeto

Este repositório documenta minha experiência prática no desenvolvimento e na adaptação responsiva de uma landing page voltada à captação de leads.

O trabalho envolveu WordPress, Elementor, HTML, CSS e Chrome DevTools, desde a organização da interface até a investigação de um problema que impedia a exibição do conteúdo na versão mobile publicada.

O objetivo deste repositório é registrar o processo técnico, os desafios encontrados, as soluções aplicadas e os aprendizados adquiridos.

## Tecnologias e ferramentas

- **WordPress:** gerenciamento e publicação da página.
- **Elementor:** estruturação de seções, contêineres e ajustes responsivos.
- **HTML5:** construção de formulário personalizado.
- **CSS3:** personalização visual, espaçamentos, alinhamento e responsividade.
- **Chrome DevTools:** inspeção do DOM, Console e CSS computado.
- **GitHub:** documentação técnica e versionamento do estudo de caso.

## Atividades desenvolvidas

- Estruturação das seções de apresentação, formulário, benefícios e confiança.
- Personalização de formulário com campos obrigatórios de nome, e-mail e telefone.
- Preparação do formulário para integração via HTTP POST.
- Estilização de campos, botão de ação e elementos informativos.
- Ajustes de alinhamento, tipografia, margens e distribuição de conteúdo.
- Adaptação visual para dispositivos móveis.
- Investigação de uma página que aparecia em branco no navegador mobile.
- Identificação e correção de configuração responsiva que ocultava o contêiner principal.

## Principal desafio técnico

A página apresentava corretamente o conteúdo na prévia do Elementor, mas ficava em branco na visualização mobile publicada.

Utilizando o Chrome DevTools, inspecionei o DOM e as propriedades CSS computadas. Identifiquei a aplicação de `display: none` em um contêiner, associada às regras de visibilidade responsiva do Elementor.

Após corrigir a configuração de ocultação, confirmei que o conteúdo voltou a ser exibido no navegador em modo de emulação mobile.

A investigação também revelou um aviso de Mixed Content relacionado ao carregamento de uma fonte, tratado como questão separada, sem evidência de que fosse a causa da página em branco.

## Resultados observados

- Estrutura visual principal implementada.
- Formulário HTML personalizado incorporado à página.
- Ajustes responsivos realizados.
- Problema de ocultação do conteúdo identificado e corrigido.
- Exibição mobile confirmada após a correção.

**Limites da validação:** o funcionamento completo da captura de leads, o redirecionamento após cadastro e os resultados de performance ainda exigem verificações específicas. Não são apresentados como resultados concluídos.

## Documentação técnica

Este repositório será organizado em documentos complementares:

- `docs/development-process.md` — estrutura e implementação.
- `docs/responsive-design.md` — ajustes para diferentes dispositivos.
- `docs/debugging-case-study.md` — investigação e correção da página em branco.
- `docs/lessons-learned.md` — aprendizados e próximos pontos de validação.

## Aprendizados

Este projeto reforçou a importância de compreender o HTML e o CSS gerados por ferramentas visuais, investigar problemas com evidências e testar o comportamento da página publicada.

Também contribuiu para minha evolução em desenvolvimento front-end, debugging e práticas de qualidade de software.

## Confidencialidade

Este é um estudo de caso educacional e profissional, sem vínculo público com a organização envolvida.

Não são divulgados nomes de empresas ou clientes, URLs internas, endpoints, credenciais, dados pessoais, capturas reais ou materiais proprietários.

Os exemplos técnicos apresentados são genéricos e têm finalidade exclusivamente demonstrativa.
