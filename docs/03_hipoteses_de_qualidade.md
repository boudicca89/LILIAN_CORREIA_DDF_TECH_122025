# Hipóteses de Qualidade dos Dados

Antes da integração e uso analítico dos dados, foram levantadas hipóteses
iniciais relacionadas à qualidade e consistência do dataset.

Estas hipóteses não representam erros confirmados, mas pontos de atenção
que deverão ser validados nas etapas seguintes do projeto.

## Hipóteses Levantadas

- Verificar a unicidade do campo `Employee_ID`
- Avaliar presença de valores nulos em campos críticos
- Validar o domínio de campos categóricos como `Gender`, `Department` e `Education_Level`
- Verificar consistência do campo `Hire_Date` (formato e fuso horário)
- Avaliar possíveis outliers no campo `Monthly_Salary`
- Confirmar se o campo `Resigned` está corretamente representado como booleano

Estas verificações serão tratadas na etapa de Qualidade de Dados
utilizando ferramentas apropriadas.
