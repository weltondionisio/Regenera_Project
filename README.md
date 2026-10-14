# Regenera_Project

O notebook aqui lê o arquivo RegeneraRS_merge_limpo(2).xlsx e produz gráficos correspondentes aos indicadores do Relatório Anual RegeneraRS, julho de 2024 a julho de 2025. As figuras do relatório foram conferidas nas páginas 13, 25–28, 48 e 51.

Os cálculos usam os dados da planilha. Os números transcritos do PDF aparecem com a indicação Relatório 2025. O Excel não informa uma data de corte para os valores operacionais; portanto, os gráficos não são apresentados como resultados de um ano específico nem como uma evolução em relação a 2025.

Como executar
Coloque o notebook e a planilha na mesma pasta.
Abra o notebook no Jupyter ou no VS Code e selecione um ambiente Python.
Confira o nome do arquivo na célula de configuração e execute todas as células, na ordem.
Se necessário, instale as dependências no ambiente escolhido:

python -m pip install jupyterlab pandas numpy matplotlib openpyxl
A execução não consulta a internet e não precisa do PDF. As referências do relatório estão documentadas no próprio notebook. Gráficos em PNG e PDF e tabelas em CSV UTF-8 tabulado e Excel são gravados em resultados_regenerars, na pasta da planilha.
