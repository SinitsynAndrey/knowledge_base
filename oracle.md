### Строка в дату
TO_DATE('04.07.2024 05:20', 'DD.MM.YYYY HH24:MI')

### Остановить JOB
begin
DBMS_SCHEDULER.STOP_JOB(job_name => 'J_U_AGR_FUNNEL_CC_TM',force => TRUE);
end;
