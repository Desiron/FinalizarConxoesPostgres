# FinalizarConxoesPostgres
Passo a Passo de como deletar todas as conexões com um database PostgresSQL
_____________________________________________________
1° - select pg_terminate_backend(procpid)
2° - from pg_stat_activity
3° - where datname = ‘nome_do_database’
