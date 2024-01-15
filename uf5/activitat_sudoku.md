# Activitat Sudoku

Utilitzant taules i CSS intenta fer una web que simuli aquest sudoku.

![image](https://github.com/XaSaFa/MP08-23-24/assets/110727546/dc023932-440b-48c9-a915-6b0dabd3af8a)

```


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sudoku</title>
    <style>
        body{
            font-size: 60px;
            text-align: center;
        }
        td{
            border: 1px black solid;
        }
        table{
            border: 3px black solid;
            border-collapse: collapse;
        }
        .cella_vermella{
            background-color: red;
        }
        .cella_verda{
            background-color: rgb(22, 168, 22);
        }
        .cella_blava{
            background-color: aqua;
        }
        .cella_buida{
            padding: 50px;
        }
        .cella_plena{
            padding: 20px;
        }

    </style>
</head>
<body>
    <table>
        <tr>
            <td>
                <table>
                    <tr>
                        <td class="cella_vermella cella_plena">
                            5    
                        </td>
                        <td class="cella_verda cella_plena">
                            3    
                        </td>
                        <td class="cella_verda cella_buida">
            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_plena">
                            6
                        </td>
                        <td class="cella_buida">
            
                        </td>
                        <td class="cella_buida">
                            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_buida">
            
                        </td>
                        <td class="cella_plena">
                            9    
                        </td>
                        <td class="cella_plena">
                            8
                        </td>
                    </tr>
                </table>
            </td>
            <!--segona taula-->
            <td>
                <table>
                    <tr>
                        <td class="cella_verda cella_buida">
                                
                        </td>
                        <td class="cella_verda cella_plena">
                            3    
                        </td>
                        <td class="cella_verda cella_buida">
            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_plena">
                            6
                        </td>
                        <td class="cella_buida">
            
                        </td>
                        <td class="cella_buida">
                            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_buida">
            
                        </td>
                        <td class="cella_plena">
                            9    
                        </td>
                        <td class="cella_plena">
                            8
                        </td>
                    </tr>
                </table>
            </td>
            <td>
                <table>
                    <tr>
                        <td class="cella_vermella cella_plena">
                            5    
                        </td>
                        <td class="cella_verda cella_plena">
                            3    
                        </td>
                        <td class="cella_verda cella_buida">
            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_plena">
                            6
                        </td>
                        <td class="cella_buida">
            
                        </td>
                        <td class="cella_buida">
                            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_buida">
            
                        </td>
                        <td class="cella_plena">
                            9    
                        </td>
                        <td class="cella_plena">
                            8
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
        <tr>
            <td>
                <table>
                    <tr>
                        <td class="cella_vermella cella_plena">
                            5    
                        </td>
                        <td class="cella_verda cella_plena">
                            3    
                        </td>
                        <td class="cella_verda cella_buida">
            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_plena">
                            6
                        </td>
                        <td class="cella_buida">
            
                        </td>
                        <td class="cella_buida">
                            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_buida">
            
                        </td>
                        <td class="cella_plena">
                            9    
                        </td>
                        <td class="cella_plena">
                            8
                        </td>
                    </tr>
                </table>
            </td>
            <td>
                <table>
                    <tr>
                        <td class="cella_vermella cella_plena">
                            5    
                        </td>
                        <td class="cella_verda cella_plena">
                            3    
                        </td>
                        <td class="cella_verda cella_buida">
            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_plena">
                            6
                        </td>
                        <td class="cella_buida">
            
                        </td>
                        <td class="cella_buida">
                            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_buida">
            
                        </td>
                        <td class="cella_plena">
                            9    
                        </td>
                        <td class="cella_plena">
                            8
                        </td>
                    </tr>
                </table>
            </td>
            <td>
                <table>
                    <tr>
                        <td class="cella_vermella cella_plena">
                            5    
                        </td>
                        <td class="cella_verda cella_plena">
                            3    
                        </td>
                        <td class="cella_verda cella_buida">
            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_plena">
                            6
                        </td>
                        <td class="cella_buida">
            
                        </td>
                        <td class="cella_buida">
                            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_buida">
            
                        </td>
                        <td class="cella_plena">
                            9    
                        </td>
                        <td class="cella_plena">
                            8
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
        <tr>
            <td>
                <table>
                    <tr>
                        <td class="cella_vermella cella_plena">
                            5    
                        </td>
                        <td class="cella_verda cella_plena">
                            3    
                        </td>
                        <td class="cella_verda cella_buida">
            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_plena">
                            6
                        </td>
                        <td class="cella_buida">
            
                        </td>
                        <td class="cella_buida">
                            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_buida">
            
                        </td>
                        <td class="cella_plena">
                            9    
                        </td>
                        <td class="cella_plena">
                            8
                        </td>
                    </tr>
                </table>
            </td>
            <td>
                <table>
                    <tr>
                        <td class="cella_vermella cella_plena">
                            5    
                        </td>
                        <td class="cella_verda cella_plena">
                            3    
                        </td>
                        <td class="cella_verda cella_buida">
            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_plena">
                            6
                        </td>
                        <td class="cella_buida">
            
                        </td>
                        <td class="cella_buida">
                            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_buida">
            
                        </td>
                        <td class="cella_plena">
                            9    
                        </td>
                        <td class="cella_plena">
                            8
                        </td>
                    </tr>
                </table>
            </td>
            <td>
                <table>
                    <tr>
                        <td class="cella_vermella cella_plena">
                            5    
                        </td>
                        <td class="cella_verda cella_plena">
                            3    
                        </td>
                        <td class="cella_verda cella_buida">
            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_plena">
                            6
                        </td>
                        <td class="cella_buida">
            
                        </td>
                        <td class="cella_buida">
                            
                        </td>
                    </tr>
                    <tr>
                        <td class="cella_blava cella_buida">
            
                        </td>
                        <td class="cella_plena">
                            9    
                        </td>
                        <td class="cella_plena">
                            8
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>  
</body>
</html>
```
