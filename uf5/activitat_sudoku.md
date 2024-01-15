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
        tr, td, table{
            border: 1px black solid;
            border-collapse: collapse;
        }
        td{
            text-align: center;
        }

        .cella_blava{
            background-color: rgb(89, 154, 188);
        }
        .cella_verda{
            background-color: greenyellow;
        }
        .cella_vermella{
            background-color: indianred;
        }
        .cella_buida{
            padding: 20px;
        }
        .taula_gran{
            border-collapse: collapse;
            border: 5px black solid;
        }
    </style>
</head>
<body>
<table class="taula_gran">
    <tr>
        <td>
            <table>
                <tr>
                    <td class="cella_vermella">
                        5
                    </td>
                    <td class="cella_verda">
                        3    
                    </td>
                    <td class="cella_verda cella_buida">
                        
                    </td>
                </tr>
                <tr>
                    <td class="cella_blava">
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
                    <td>
                        9    
                    </td>
                    <td>
                        8
                    </td>
                </tr>
            </table>
        </td>
        <td>
            <table>
                <tr>
                    <td class="cella_vermella">
                        5
                    </td>
                    <td class="cella_verda">
                        3    
                    </td>
                    <td class="cella_verda cella_buida">
                        
                    </td>
                </tr>
                <tr>
                    <td class="cella_blava">
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
                    <td>
                        9    
                    </td>
                    <td>
                        8
                    </td>
                </tr>
            </table>
        </td>
        <td>
            <table>
                <tr>
                    <td class="cella_vermella">
                        5
                    </td>
                    <td class="cella_verda">
                        3    
                    </td>
                    <td class="cella_verda cella_buida">
                        
                    </td>
                </tr>
                <tr>
                    <td class="cella_blava">
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
                    <td>
                        9    
                    </td>
                    <td>
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
                    <td class="cella_vermella">
                        5
                    </td>
                    <td class="cella_verda">
                        3    
                    </td>
                    <td class="cella_verda cella_buida">
                        
                    </td>
                </tr>
                <tr>
                    <td class="cella_blava">
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
                    <td>
                        9    
                    </td>
                    <td>
                        8
                    </td>
                </tr>
            </table>
        </td>
        <td>
            <table>
                <tr>
                    <td class="cella_vermella">
                        5
                    </td>
                    <td class="cella_verda">
                        3    
                    </td>
                    <td class="cella_verda cella_buida">
                        
                    </td>
                </tr>
                <tr>
                    <td class="cella_blava">
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
                    <td>
                        9    
                    </td>
                    <td>
                        8
                    </td>
                </tr>
            </table>
        </td>
        <td>
            <table>
                <tr>
                    <td class="cella_vermella">
                        5
                    </td>
                    <td class="cella_verda">
                        3    
                    </td>
                    <td class="cella_verda cella_buida">
                        
                    </td>
                </tr>
                <tr>
                    <td class="cella_blava">
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
                    <td>
                        9    
                    </td>
                    <td>
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
                    <td class="cella_vermella">
                        5
                    </td>
                    <td class="cella_verda">
                        3    
                    </td>
                    <td class="cella_verda cella_buida">
                        
                    </td>
                </tr>
                <tr>
                    <td class="cella_blava">
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
                    <td>
                        9    
                    </td>
                    <td>
                        8
                    </td>
                </tr>
            </table>
        </td>
        <td>
            <table>
                <tr>
                    <td class="cella_vermella">
                        5
                    </td>
                    <td class="cella_verda">
                        3    
                    </td>
                    <td class="cella_verda cella_buida">
                        
                    </td>
                </tr>
                <tr>
                    <td class="cella_blava">
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
                    <td>
                        9    
                    </td>
                    <td>
                        8
                    </td>
                </tr>
            </table>
        </td>
        <td>
            <table>
                <tr>
                    <td class="cella_vermella">
                        5
                    </td>
                    <td class="cella_verda">
                        3    
                    </td>
                    <td class="cella_verda cella_buida">
                        
                    </td>
                </tr>
                <tr>
                    <td class="cella_blava">
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
                    <td>
                        9    
                    </td>
                    <td>
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
