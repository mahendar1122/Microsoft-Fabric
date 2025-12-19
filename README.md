1. Create a Microsoft Fabric Lakehouse
2. Create a workspace
3. Create a lakehouse
4. Upload a file
5. Load file data into a table
6. Use SQL to query tables
SELECT Item, SUM(Quantity * UnitPrice) AS Revenue
FROM sales
GROUP BY Item
ORDER BY Revenue DESC;
7. Create a visual query
