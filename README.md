# DespesasControle
site de despesas
oi
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Controle de Despesas</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.3.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap/dist/css/bootstrap.min.css">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap/dist/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css">
    <style>
        /* Estilos CSS aqui... */
    </style>
</head>
<body class="body">
    <div class="header">
        <h2 class="logo">Controle de Despesas</h2>
    </div>

    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <!-- Formulário de adição de despesa aqui... -->
            </div>
        </div>

        <div class="total-despesas-por-mes">
            <!-- Tabela de orçamento por mês aqui... -->
        </div>

        <h2><center>Despesas Cadastradas</center></h2>
        <div class="mb-3" id="DespesasCadastradas" style="max-height: 400px; overflow-y: auto;">
            <div class="row">
                <div class="col-md-12"><br>
                    <table class="tabela-amarela">
                        <thead>
                            <tr>
                                <th class="fixed-header">Nome</th>
                                <th class="fixed-header">Tipo de Pagamento</th>
                                <th class="fixed-header">Tipo de Gasto</th>
                                <th class="fixed-header">Valor</th>
                                <th class="fixed-header">Data</th>
                                <th></th>
                            </tr>
                        </thead>
                        <tbody>
                            <!-- Linhas de despesas aqui... -->
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>

    <footer class="footer">
        <div class="container">
            <p>Produzido por Ltos &copy; 2023</p>
        </div>
    </footer>

    <script>
        // JavaScript para manipular interações no cliente aqui...
    </script>
</body>
</html>
