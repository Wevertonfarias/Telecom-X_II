#### Dicionário de dados

*   **`ID_cliente`**: Número de identificação único de cada cliente.
*   **`Cancelamento`**: Indicador se o cliente cancelou o serviço.
    *   `1`: Sim
    *   `0`: Não
*   **`Genero`**: Gênero do cliente.
    *   `Male`: Masculino
    *   `Female`: Feminino
*   **`Idoso`**: Indicador se o cliente é idoso (idade igual ou superior a 65 anos).
    *   `1`: Sim
    *   `0`: Não
*   **`Tem_parceiro`**: Indicador se o cliente possui um parceiro ou parceira.
    *   `1`: Sim
    *   `0`: Não
*   **`Tem_dependentes`**: Indicador se o cliente possui dependentes.
    *   `1`: Sim
    *   `0`: Não
*   **`Meses_com_empresa`**: Quantidade de meses que o cliente permaneceu com a empresa.
*   **`Servico_telefonico`**: Indicador se o cliente assina o serviço telefônico básico.
    *   `1`: Sim
    *   `0`: Não (nesse caso, muitas outras colunas de serviço são ignoradas)
*   **`Multiplas_linhas`**: Indicador se o cliente assina múltiplas linhas telefônicas.
    *   `1`: Sim
    *   `0`: Não
    *   `No phone service`: Não possui serviço telefônico
*   **`Tipo_internet`**: Tipo de provedor de internet contratado.
    *   `DSL`: Linha Digital de Assinante
    *   `Fiber optic`: Fibra óptica
    *   `No internet service`: Não possui serviço de internet (nesse caso, muitas outras colunas de serviço são ignoradas)
*   **`Seguranca_online`**: Indicador se o cliente assina o serviço adicional de segurança online.
    *   `1`: Sim
    *   `0`: Não
    *   `No internet service`: Não possui serviço de internet
*   **`Backup_online`**: Indicador se o cliente assina o serviço adicional de backup online.
    *   `1`: Sim
    *   `0`: Não
    *   `No internet service`: Não possui serviço de internet
*   **`Protecao_aparelho`**: Indicador se o cliente assina o serviço adicional de proteção de dispositivo.
    *   `1`: Sim
    *   `0`: Não
    *   `No internet service`: Não possui serviço de internet
*   **`Suporte_tecnico`**: Indicador se o cliente assina o serviço adicional de suporte técnico.
    *   `1`: Sim
    *   `0`: Não
    *   `No internet service`: Não possui serviço de internet
*   **`Streaming_TV`**: Indicador se o cliente assina o serviço de streaming de TV.
    *   `1`: Sim
    *   `0`: Não
    *   `No internet service`: Não possui serviço de internet
*   **`Streaming_filmes`**: Indicador se o cliente assina o serviço de streaming de filmes.
    *   `1`: Sim
    *   `0`: Não
    *   `No internet service`: Não possui serviço de internet
*   **`Tipo_contrato`**: Tipo de contrato de vigência.
    *   `Month-to-month`: Contrato mensal
    *   `One year`: Contrato anual
    *   `Two year`: Contrato bienal
*   **`Fatura_digital`**: Indicador se o cliente optou por fatura digital (paperless billing).
    *   `1`: Sim
    *   `0`: Não
*   **`Forma_pagamento`**: Método de pagamento utilizado pelo cliente.
    *   `Mailed check`: Cheque por correio
    *   `Electronic check`: Cheque eletrônico
    *   `Credit card (automatic)`: Cartão de crédito (débito automático)
    *   `Bank transfer (automatic)`: Transferência bancária (débito automático)
*   **`Valor_mensal`**: Valor total cobrado mensalmente do cliente por todos os serviços.
*   **`Valor_total`**: Valor total gasto pelo cliente durante todo o período de contrato.
*   **`Contas_Diarias`**: Valor médio diário gasto pelo cliente (calculado a partir do `Valor_mensal`).