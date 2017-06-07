# FinalizarConxoesPostgres
Passo a Passo de como deletar todas as conexões com um database PostgresSQL
_____________________________________________________
1° select pg_terminate_backend(PID) from pg_stat_activity where datname = 'DATA_BASE'
