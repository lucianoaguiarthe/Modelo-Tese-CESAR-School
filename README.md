Tese do Doutorado Profissional CESAR School 
=================
<p align="center"><img src="images/marca_cesar_school.png"  width="350" height="276" align="middle"/></p>

Este documento criado a partir de um Modelo de [Tese da USP](https://www.overleaf.com/latex/templates/modelo-de-teses-e-dissertacoes-icmc-slash-usp/cvqdvbnxjqts), visa atender as exigências dos Programas de Pós-Graduação da CESAR School, Doutorado Profissional em Engenharia de Software. As normas principais estão baseadas na ABNT, com algumas adaptações em relação aos estilos dos capítulos, capa e folhas de rostos.

O requisito básico para utilização da classe **_icmc_** é criar um documento desta classe com o comando
`\documentclass[@parameters]{icmc}` e ter, no diretório de trabalho, o arquivo *icmc.cls* presente. Entretanto, recomenda-se fortemente manter a estrutura de diretório inicial fornecida por este modelo. 

Para que o documento esteja em conformidade com as normas exigidas pelo programa de Pós-Graduação, o **projeto deve ser compilado utilizando *XeLaTeX* ou *LuaLaTeX***. Esse processo de compilação é necessário para que as fontes externas utilizadas para gerar a capa sejam incluídas.

Os parâmetros possíveis utilizados pelo `\documentclass` são:
- **[qualificacao]** Exclusivamente para monografias de qualificação em geral;
- **[mestrado / doutorado]** Identifica o curso ao qual o aluno pertence, sendo utilizado apenas uma das duas opcões disponíveis. O valor padrão é **doutorado**;
- **[pre-defesa / pos-defesa]** Identifica a situação do documento (exceto para qualificação), sedo necessário apenas uma das duas opções. O valor padrão é **pos-defesa**;
- **[impressao]** Gera exclusivamente uma versão para impressão do documento;
- **[french, spanish, english, brazil]** Adiciona o idioma para correta hifenização correta no documento. Os idiomas bases para o modelo (português e inglês) não precisam ser declarados.
