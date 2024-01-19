# Parametros de uma Dag

<p><strong>1. dag_id:</strong> um identificador único para a DAG na cluster.</p>
<p><strong>2. description:</strong> descrição da DAG.</p>
<p><strong>3. schedule_interval:</strong> o intervalo de tempo no qual a será executada.</p>
<p><strong>4. start_date:</strong> a data e hora em que a DAG deve começar a ser executada.</p>
<p><strong>5. end_date:</strong> a data e hora em que a DAG não deve mais ser executada.</p>
<p><strong>6. catchup:</strong> determina se a DAG deve executar todas as tarefas que deveriam ter sido executadas desde a data de start_date até o momento atual.Padrão é true.</p>
<p><strong>7. default_view:</strong> visualização padrão da interface do Airflow para esta DAG. Por exemplo, "graph".</p>
<p><strong>8. max_active_runs:</strong> máximo de execuções ativas da DAG permitidas.</p>
