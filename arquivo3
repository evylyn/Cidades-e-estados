UPDATE `alunos` 
SET 
    `Cidade` = CASE
        WHEN `ID` = 2 THEN 'Rio de Janeiro'
        WHEN `ID` = 3 THEN 'Uberlândia'
        WHEN `ID` = 4 THEN 'Canoas'
        WHEN `ID` = 5 THEN 'Salvador'
    END,
    `estado` = CASE
        WHEN `ID` = 2 THEN 'RJ'
        WHEN `ID` = 3 THEN 'MG'
        WHEN `ID` = 4 THEN 'RS'
        WHEN `ID` = 5 THEN 'BA'
    END
WHERE `ID` IN (2, 3, 4, 5);
