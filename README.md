# sturdy-journey
projeto de avaliação do semestre
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body bgcolor="black">
    <div id="principal2">
        <div id="topo">
            <div id="logo">
                <h1> Furiosos e Velozes </h1>
                <h4> Compra e venda de Carros </h4>
            </div>
        </div>
        <nav id="menu">
            <ul>
                <li> <a href="index.html">Home</a></li>
                <li> <a href="tabelaCarros.html">Carros</a></li>
                <li> <a href="tabelaMarcas.html">Marcas</a></li>
                <li> <a href="cadastro.html">Cadastro</a></li>
                <li> <a href="listas.html">Contatos</a></li>
                <li> <a href="Documentacao.html">Documentação</a></li>
            </ul>
        </nav>

        <div id="topo">
            <div id="logo">
                <h1> Cadastro </h1>
            </div>
        </div>
        <center>
            <table>
                <tr>
                    <td align="center" bgcolor="#F7BE81">
                        <center>
                            <h2>Cadastre seus dados, suas preferências e fique <br> por dentro das novidades da nossa
                                loja.
                            </h2>
                        </center>


                        <form method="post" action="mailto:andre.prado@gmail.com" align="center">
                            Nome: <input type="text" name="NNome" id="nome_id" value="" size="30" maxlength="15"
                                placeholder="Dgite seu nome aqui!">
                            <br><br>
                            E-mail: <input type="text" name="NNome" id="nome_id" value="" size="30" maxlength="15"
                                placeholder="Dgite seu E-mail aqui!">
                            <br><br>
                            Fone: <input type="text" name="NNome" id="nome_id" value="" size="30" maxlength="15"
                                placeholder="Dgite seu fone aqui!">
                            <br><br>



                            <center>

                                <table border="2">
                                    <tr>
                                        <th align="center">
                                            <font face="calibri" color="black"><i>Qual marca você prefere? </i></font>
                                        </th>

                                    </tr>

                                    <tr>
                                        <td align="left">
                                            <font face="calibri" color="black">
                                                <input type="checkbox" name="audi" id="audi_id">Audi<br>
                                                <input type="checkbox" name="aston" id="aston_id">Aston Martin <br>
                                                <input type="checkbox" name="bmw" id="bmw_id">BMW<br>
                                                <input type="checkbox" name="cadillac" id="cadillac_id">Cadillac <br>
                                                <input type="checkbox" name="ferrari" id="ferrari_id">Ferrari <br>
                                                <input type="checkbox" name="jaguar" id="jaguar_id">Jaguar <br>
                                                <input type="checkbox" name="land" id="land_id">Land-Rover <br>
                                                <input type="checkbox" name="mercedes" id="mercedes_id">Mercedes-Benz
                                                <br>
                                                <input type="checkbox" name="porsche" id="porsche_id">Porsche <br>
                                                <input type="checkbox" name="volvo" id="volvo_id">Volvo <br>

                                            </font>
                                        </td>


                                    </tr>


                                </table>
                            </center>
                            <br>
                            Deixe aqui seus comentários, críticas e sugestões <br>
                            <textarea name="critica" id="critica_id" cols="60" rows="3"
                                placeholder="Digite seus comentários aqui:"></textarea>
                            <br>
                            <input type="reset" name="NReset" id="reset_id" value="Limpar Campos">
                            <input type="submit" name="NEnviar" id="enviar_id" value="Enviar Dados">
                            <br><br>
        </center>
        </form>
        </td>
        </tr>
        </table>
        </center>
    </div>
    <br>

    <footer>
        <p>Membros: André Silva (ADS) - Carlos Eduardo (ADS) - Felipe Barreto (CD) - Isaque Cardoso (ADS)</p>
    </footer>
    </div>

</body>

</html>
