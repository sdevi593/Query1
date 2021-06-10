# Query1
For Placement Test Purpose

SELECT id, MAX(insert_time) as "Max Insert Time", tx_amount, tx_type, status FROM transactions 
GROUP BY id;
