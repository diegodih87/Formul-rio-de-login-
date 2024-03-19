

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="utf-8">
    <title>Formulário de Login</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {
            background-color: #f8f9fa;
            font-family: Arial, sans-serif;
        }
        .container {
            max-width: 400px;
            margin: 100px auto;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            background-color: #fff;
        }
        .form-group label {
            font-weight: bold;
        }
        .form-group input[type="email"],
        .form-group input[type="password"],
        .form-group input[type="file"] {
            border: 1px solid #ced4da;
            border-radius: 5px;
            padding: 10px;
        }
        .form-group input[type="email"]:focus,
        .form-group input[type="password"]:focus,
        .form-group input[type="file"]:focus {
            outline: none;
            border-color: #007bff;
        }
        .checkbox label {
            font-weight: normal;
        }
        .btn {
            background-color: #007bff;
            color: #fff;
            border-radius: 5px;
            padding: 10px 20px;
            border: none;
        }
        .btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2 class="mb-4">Login</h2>
        <form>
            <div class="form-group">
                <label for="exampleInputEmail1">E-mail:</label>
                <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Digite seu e-mail">
            </div>
            <div class="form-group">
                <label for="exampleInputPassword1">Senha:</label>
                <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Digite sua senha">
            </div>
            <div class="form-group">
                <label for="exampleInputFile">Selecione um arquivo:</label>
                <input type="file" id="exampleInputFile">
                <p class="help-block">Exemplo de texto de ajuda.</p>
            </div>
            <div class="form-group form-check">
                <input type="checkbox" class="form-check-input" id="exampleCheck1">
                <label class="form-check-label" for="exampleCheck1">Eu li e aceito os termos de uso.</label>
            </div>
            <button type="submit" class="btn btn-primary">Enviar</button>
        </form>
    </div>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
