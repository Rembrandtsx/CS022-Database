# Chapter 6 homework

**Name: Zhang Yupeng**

**Student ID: 5130309468** 

	


**Solution:**

```sql
SELECT  P1.model, P2.model
```


	


**Solution:**

```sql
SELECT  L.model

				WHERE P.speed >= L.speed);
```


	


**Solution:**

```sql
SELECT  speed, AVG(price) AS Avg_Price
```


Serializable: T will never see changes to the database and keep printing the same list of PCs. This does not serve any useful purpose. Application may need to periodically stop T and then restart it to see data committed in the meantime.