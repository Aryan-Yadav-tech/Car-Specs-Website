# Car-Specs-Website
"Explore detailed car specifications, including performance, features, pricing, and comparisons. Designed for car enthusiasts seeking insights into their favorite vehicles and informed buying decisions."


CREATE PROCEDURE factor @number INT
AS
BEGIN
   DECLARE @i INT=1 ,@result INT=1
   WHILE(@1<=@number)
   BEGIN
     SET @result=@result*@i
     SET @i +=1    
   END
   SELECT @result AS Factorial
END
EXEC Factor 5
