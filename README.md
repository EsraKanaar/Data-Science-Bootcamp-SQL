# Data-Science-Bootcamp-SQL
//a)
SELECT FirstName,LastName,Salary
FROM employees;
/*select komutundan sonra görmek istediğim kolonları yazarak sadece belli kolonları seçtim ve gösterdim.From komutuyla  bunu hangi tablodan alacağımı belirttim.*/
//b)
SELECT distinct *
FROM departments;
/*select komutu kullanarak kolonu seçtim,Distinct komutu ile sadece farklı sonuçları göstermesini sağladım.'*' işareti ile de departments tablosunun hepsini getirmesini sağladım.*/
//c)
SELECT EmployeeID, FirstName, LastName, Age, Department, Salary, JoinDate
FROM Employees
WHERE Department = 'IT';
//d)
SELECT *
FROM employees
ORDER BY 6 desc;
/*select komutu kullanarak kolonu seçtim,'*' işareti ile de employees tablosunun hepsini getirmesini sağladım.Order by 6 desc ifadesini kullanarak getirdiğim verileri 6.kolondakiler büyükten küçüğe olacak şekide sıralama yaptım.*/

//e)

SELECT FirstName , LastName,
	FirstName ||  LastName as FullName
FROM employees;
/*Select komutundan sonra getirmesini istediğim kolonları yazdım.Daha sonra bunları bitiş bir kolond görmek istediğim için '||' işaretini kullandım.Bu kolonaisim vermek istediğim için as ifadesini kullandım.Bunların hepsini employees tablosundan alacak o yüzden from kullandım. 

















