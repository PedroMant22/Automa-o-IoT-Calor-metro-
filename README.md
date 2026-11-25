# Automa-o-IoT-Calor-metro-
Aplicativo em Python para aquisição e processamento de dados do calorímetro SETARAM HT1000 com Arduino Uno. Registra dois canais, corrige linha de base, integra sinais, calcula energia e energia específica, exporta CSV/PDF e oferece monitoramento remoto somente leitura. Inclui rotinas de calibração com alumina; validação metrológica em andamento


Descrição para o README
Este repositório reúne o aplicativo desenvolvido para modernizar a aquisição e o processamento de dados do calorímetro SETARAM HT1000, utilizado em atividades didáticas e de pesquisa. A solução integra uma placa condicionadora existente, um Arduino Uno e uma aplicação Python com interface para Windows.

O sistema realiza aquisição independente de dois canais, preserva as tensões registradas, aplica correção linear da linha de base, integra numericamente o sinal e converte a área em energia e energia específica usando fatores de calibração associados a padrões de alumina. Também permite exportação em CSV e PDF, cadastro de parâmetros experimentais e acompanhamento remoto somente leitura por navegador e QR Code.

Principais recursos
Aquisição independente de dois canais analógicos;

Registro e armazenamento das tensões originais;

Correção da linha de base por ajuste linear;

Integração numérica com a regra composta de Simpson;

Cálculo de energia, energia específica e calor específico médio aparente;

Calibração e interpolação de fatores associados à alumina;

Exportação de dados em CSV e relatórios em PDF;

Monitoramento remoto somente leitura via navegador e QR Code;

Interface para preparação, acompanhamento e análise dos ensaios.

Status e limitações
O funcionamento integrado do software foi verificado em ensaios com cobre e alumina, incluindo aquisição contínua, exportação de dados e acesso remoto. Entretanto, a validação metrológica para diferentes materiais e temperaturas ainda está em andamento. Os resultados dependem da seleção da linha de base, das condições experimentais e da adequação dos fatores de calibração. Este repositório não substitui procedimentos formais de calibração e validação do instrumento.

Tópicos sugeridos
calorimetry · setaram-ht1000 · arduino-uno · python · data-acquisition · signal-processing · instrumentation · calorimeter · csv-export · pdf-report · remote-monitoring
