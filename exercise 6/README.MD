# today i learn index that you can the tables of columns to be fast
# i get more concepts about this
# i tried to build products about searching 1k data
# the table contains columns includes : id, product_name, category, price, stock and created_at
# so when i am making searching it researching all row for example: i am search stock so the table filter all 1k data and it was not first so when i use index the data be immidiately and filtring the column of stock that's what i need and this way take part by index
# this way is first and if you have millions you can sort the data making like this: create index idx_stock on products(stock); then when you reading it will be : Explain select * from products where stock between 357 and 479;
# so i want to display my exercise 6