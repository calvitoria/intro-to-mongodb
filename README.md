# intro-to-mongodb
My first mongoDB project. The goal was to develop queries to create, update, delete and read data based on a hamburguer chain.

This are the tasks developed in this project: 

*Nome* | *Avaliação*
--- | :---:
1 - Return the quantity of `products` | :heavy_check_mark:
10 - return the `name` of the hamburguers that have `proteínas` (protein) greater or equal to `30` and less or equal than `40` | :heavy_check_mark:
11 - Return the `name` of the product, the amount of `likes` and how many items were `sold` of the products that are not equal to `Big Mac` and `McChicken` | :heavy_check_mark:
12 - Add `ketchup` to the `ingredients` for all sandwiches except `McChicken`, ensuring there is no duplicate `ingredient` | :heavy_check_mark:
13 - Include the `createdBy` field in all documents by putting `Ronald McDonald` in the value of this field | :heavy_check_mark:
14 - Create a query that returns all snacks that have *pickles* in their ingredients and show only the first `3` items contained in the `Nutritional Values` array | :heavy_check_mark:
15 - Add the `evaluation` field to all documents in the collection and make changes to this field | :heavy_check_mark:
16 - Add the `lastModification` field with the current date only in the `Big Mac` sandwich | :heavy_check_mark:
17 - Return the total amount of products in a new collection called `summaryProducts` | :heavy_check_mark:
18 - Add `bacon` to the end of the `ingredients` list of the `Big Mac` and `Quarteirão com Queijo` sandwiches | :heavy_check_mark:
19 - Remove the `onion` item from all sandwiches | :heavy_check_mark:
2 - Sort the `products` collection by the number of snacks sold in ascending order, showing only the `name` and the number of snacks `sold` | :heavy_check_mark:
20 - Remove the first `ingredient` from the `Quarteirão com Queijo` sandwich | :heavy_check_mark:
21 - Remove the last `ingredient` from the `Cheddar McMelt` sandwich | :heavy_check_mark:
22 - Add the amount of sandwich sales by day of the week | :heavy_check_mark:
23 - Insert the `combo` and `tasty` values ​​in the _array_ `tags` of all the sandwiches and take the opportunity to leave the values ​​in ascending alphabetical order (A to Z) | :heavy_check_mark:
24 - Sort in all documents the values ​​of the _array_ `valuesNutritional` by the `percentage` field in descending order | :heavy_check_mark:
25 - Add the value `too much sodium` to the end of the _array_ `tags` in products where the `percentage` of `sodium` is greater than or equal to `40` | :heavy_check_mark:
26 - Add the value `contains sodium` to the end of the _array_ `tags` in products where the `percentage` of `sodium` is greater than `20` and less than `40` | :heavy_check_mark:
27 - Count how many products contain `Mc` in the name, without considering uppercase or lowercase letters | :heavy_check_mark:
28 - Count how many products have `4` ingredients | :heavy_check_mark:
29 - Rename the `description` field to `Site description` in all documents | :heavy_check_mark:
3 - Return the best-selling snack, showing only the `name` and quantity of the best-selling snack | :heavy_check_mark:
30 - Remove the `likes` field from the `Big Mac` item | :heavy_check_mark:
31 - Return the `name` of the sandwiches where the number of `likes` is greater than the number of sandwiches `sold` | :heavy_check_mark:
32 - Return the `name` and the number of sales (`sold`) of the sandwiches where the number of sales is a multiple of `5` | :heavy_check_mark:
4 - Return the snacks that had sales greater than `50` and less than `100`, showing only the name and number of `sold` snacks in ascending order | :heavy_check_mark:
5 - Return the `name`, the `likes` and `sold` of the snacks that had a number of `likes` equal to `36` or a quantity of sales equal to `85` | :heavy_check_mark:
6 - Return the `name` and `likes` of the snacks that had likes higher than `10` and lower than `100` | :heavy_check_mark:
7 - Return the `name` and `sold` of the snacks that have been `sold` with an amount other than `50` and where the `tags` field does not exist | :heavy_check_mark:
8 - Delete the snacks with less than `50` `likes` and return the `name` of the snacks left in the bank | :heavy_check_mark:
9 - Return the `name` of all snacks that have `calories` below `500` | :heavy_check_mark:
