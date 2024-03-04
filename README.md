# Telegram
Criação de processo de ETL de mensagens no Telegram para obtençao de Insights. O processo pode ser sintetizado na seguinte forma:
![Profissao Analista de dados M42 Material de apoio arch](https://github.com/Wuisley/Telegram/assets/115996465/b48d647b-888a-4385-bfae-339354d1e7f1)

No coração do processo é utilizado como principais ferramentas:

- Telagram como ferramenta de criação de dados:
![image](https://github.com/Wuisley/Telegram/assets/115996465/ce1f25b8-f16b-4334-9674-ed350dc15fc4)


- AWS s3 como opção de armazenamento das mensagens:
![image](https://github.com/Wuisley/Telegram/assets/115996465/2c3b6f2b-5138-411c-b8f8-881185cceed4)





- AWS lambda para fazer a integração:
![image](https://github.com/Wuisley/Telegram/assets/115996465/a3076cf0-896d-45e7-a728-b33f2709d1c5)





Ao final é gerado uma tabela no no seguinte formato:
![tabela athena](https://github.com/Wuisley/Telegram/assets/115996465/1dd25ceb-fcc2-421d-a465-ce9181571ca6)


Com a finalização do projeto podemos ver a aplição com os seguintes benefícios:

- Utilização da ferramenta como meio de evitar problemas em períodos com maior demanda, provisionando previamente recursos equivalentes;
- Verificação de quais são os pontos com maior demanda e modelar os recursos disponíveis;
- Automatizaçao de processo, reduzindo o risco operacional;
- Desenvolver um referencial com indicadores de alerta;
- Melhor transparência interna de como está a situação dos atendimentos de forma sempre atualizada diariamente;
