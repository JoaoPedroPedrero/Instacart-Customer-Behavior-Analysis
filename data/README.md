# Dados necessários

Os arquivos de dados não são publicados neste repositório. Para executar o notebook, utilize o conjunto fornecido no exercício educacional e coloque os cinco arquivos abaixo nesta pasta:

```text
data/
├── instacart_orders.csv
├── products.csv
├── order_products.csv
├── aisles.csv
└── departments.csv
```

## Colunas esperadas

### `instacart_orders.csv`

- `order_id`
- `user_id`
- `order_number`
- `order_dow`
- `order_hour_of_day`
- `days_since_prior_order`

### `products.csv`

- `product_id`
- `product_name`
- `aisle_id`
- `department_id`

### `order_products.csv`

- `order_id`
- `product_id`
- `add_to_cart_order`
- `reordered`

### `aisles.csv`

- `aisle_id`
- `aisle`

### `departments.csv`

- `department_id`
- `department`

Os arquivos devem utilizar ponto e vírgula (`;`) como separador. O notebook aceita `order_products.csv` descompactado ou `order_products.csv.zip`.
