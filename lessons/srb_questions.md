### Queries

1. How to provides sources from two disimilar databases, for e.g one table from snowflake and one from bigquery.



### Commands to remember
1. dbt run-operation #macro-name --args '{"models_name": [""]}' for e.g `dbt run-operation generate_model_yaml --args '{"model_names": ["int_ecommerce__order_items_products"]}'`.
2. dbt run -s (select) model_name
3. dbt test -s model_name
4.