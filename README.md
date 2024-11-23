<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meus Níveis de Conhecimento</title>
    <style>
        body {
            background-color: white;
            font-family: Arial, sans-serif;
            color: black;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }

        h1 {
            margin-bottom: 30px;
        }

        .progress-container {
            width: 80%;
            max-width: 600px;
            margin: 10px 0;
        }

        .progress-bar {
            height: 20px;
            border-radius: 10px;
            background-color: #e0e0e0;
        }

        .progress {
            height: 100%;
            border-radius: 10px;
        }

        .python {
            width: 34%;
            background-color: #306998;
        }

        .javascript {
            width: 44%;
            background-color: #f7df1e;
        }

        .database {
            width: 35%;
            background-color: #005c5c;
        }

        .label {
            margin-top: 5px;
            text-align: center;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>Meus Níveis de Conhecimento</h1>

    <div class="progress-container">
        <label for="python">Python (34%)</label>
        <div class="progress-bar">
            <div class="progress python"></div>
        </div>
        <div class="label">34%</div>
    </div>

    <div class="progress-container">
        <label for="javascript">JavaScript (44%)</label>
        <div class="progress-bar">
            <div class="progress javascript"></div>
        </div>
        <div class="label">44%</div>
    </div>

    <div class="progress-container">
        <label for="database">Banco de Dados (35%)</label>
        <div class="progress-bar">
            <div class="progress database"></div>
        </div>
        <div class="label">35%</div>
    </div>
</body>
</html>
