# php-bk-ya

Requires PHP 7.0+

## Docs
  
    -product_cat_tree  - Создание дерева  из категорий 
  
## Install
    add in function file:
    include_once(__DIR__ . DIRECTORY_SEPARATOR . 'function_ext/_import.php');
    cheak path!!

## Examples
    -product_cat_tree
        - shotcode	
            [PRODUCT_CAT_TREE level=1]
            [PRODUCT_CAT_T  REE]    default level=1
        - function()
            product_cat_tree_print(['level'=>1]);
            
          

## Tests

     php test_product_cat_tree.php

## License
    MIT
