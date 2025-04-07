# Schema:
```
CREATE TABLE IF NOT EXISTS public.donut_haus
(
    order_id double precision,
    order_date timestamp with time zone,
    order_time double precision,
    customer_id double precision,
    store_location text COLLATE pg_catalog."default",
    product text COLLATE pg_catalog."default",
    flavor text COLLATE pg_catalog."default",
    quantity double precision,
    price_per_unit double precision,
    total_price double precision,
    payment_method text COLLATE pg_catalog."default",
    order_type text COLLATE pg_catalog."default",
    promotion text COLLATE pg_catalog."default"
)
