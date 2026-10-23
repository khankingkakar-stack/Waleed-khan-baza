# Waleed-khan-baza
Assignment no 6
SELECT
    product_id,
    product_name,
    brand_id,
    category_id,
    list_price
FROM
    products
WHERE
    list_price BETWEEN 500 AND 1500
    AND (model_year = 2019 OR model_year = 2020)
ORDER BY
    list_price ASC;
    
