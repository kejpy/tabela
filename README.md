<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabela</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Palatino+Linotype&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Aptos+Narrow&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Candara&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Bank+Gothic+Lt+BT&display=swap');

        table {
            border-collapse: collapse;
            width: 100%;
            height: 400px;
            border: 2px solid red;
        }
        th, td {
            border: 1px solid red;
            padding: 8px;
        }
        caption {
            font-weight: bold;
            margin-bottom: 10px;
            font-size: 15px;
        }
        thead {
            background-color: #f2f2f2;
        }
        .merged-top {
            background-color: #d69666;
            font-weight: bold;
            font-family: 'Bank Gothic Lt BT', sans-serif;
            color: white;
            font-size: 15px;
            text-align: center;
        }
        .highlighted-42 {
            background-color: #f9cb9c;
            font-family: 'Aptos Narrow', sans-serif;
        }
        .highlighted-34 {
            background-color: #fde9d9;
            font-family: 'Aptos Narrow', sans-serif;
        }
        .white-background {
            background-color: #ffffff;
        }
        .merged-bottom {
            background-color: #d69666;
            font-weight: bold;
            font-family: 'Candara', sans-serif;
            font-size: 15px;
            text-align: center;
        }
        .last-cell {
            background-color: #ffffff;
            border-left: 1px dashed red;
            border-right: 1px dashed red;
            border-bottom: 1px dashed red;
            border-top: none;
            color: red;
            font-size: 6px;
            font-style: italic;
            text-decoration: underline;
            font-family: 'Aptos Narrow', sans-serif;
            text-align: left;
        }
        td, th {
            font-family: 'Palatino Linotype', serif;
        }
        .blue-text {
            color: blue;
        }
        .dark-blue-text {
            color: darkblue;
        }
        .dark-red-text {
            color: darkred;
        }
        .light-red-text {
            color: lightcoral;
        }
        .brown-text {
            color: brown;
        }
        .dark-purple-text {
            color: darkviolet;
        }
        .purple-text {
            color: purple;
        }
        .header-text {
            font-size: 15px;
            font-weight: bold;
        }
        .default-text {
            font-size: 10px;
        }
        .title-text {
            font-size: 15px;
            font-weight: bold;
        }
        .left-align {
            text-align: left;
        }
        .right-align {
            text-align: right;
        }
    </style>
</head>
<body>
    <h1>Tabela</h1>
    <table border="2" cellspacing="2" cellpadding="8">
        <caption class="title-text">Tabela z Połączonymi Wierszami i Stylizacją</caption>
        <thead>
            <tr>
                <th colspan="6" class="merged-top">Dane komputerowe - Kacper Wawrzyniak- Pekar 2TGIg2</th>
            </tr>
        </thead>
        <tbody>
            <tr class="highlighted-42">
                <td class="blue-text title-text left-align">Model komputera</td>
                <td class="dark-red-text title-text left-align">Procesor</td>
                <td class="light-red-text title-text left-align">Pamięć Ram</td>
                <td class="brown-text title-text right-align">Dysk SSD</td>
                <td class="dark-purple-text title-text right-align">Karta graficzna</td>
                <td class="dark-blue-text title-text right-align">Bateria</td>
            </tr>
            <tr class="highlighted-34">
                <td class="blue-text">Dell XPS 15</td>
                <td class="dark-red-text">Intel Core i7-12700H</td>
                <td rowspan="2" colspan="1" class="light-red-text white-background left-align">16 GB</td>
                <td rowspan="2" colspan="1" class="brown-text white-background right-align">512 GB</td>
                <td class="dark-purple-text right-align">NVIDIA RTX 3050</td>
                <td class="dark-blue-text right-align">86 Wh</td>
            </tr>
            <tr>
                <td class="blue-text">Apple MacBook Pro 14</td>
                <td class="dark-red-text">Apple M2 Pro</td>
                <td class="dark-purple-text right-align">Apple M2 Pro</td>
                <td class="dark-blue-text right-align">70 Wh</td>
            </tr>
            <tr>
                <td class="blue-text">Lenovo ThinkPad X1 Carbon</td>
                <td rowspan="2" colspan="1" class="dark-red-text white-background left-align">Intel Core i7-1260P</td>
                <td rowspan="2" colspan="1" class="light-red-text white-background left-align">8 GB</td>
                <td class="brown-text right-align">1 TB</td>
                <td rowspan="2" colspan="1" class="dark-purple-text white-background right-align">Intel Iris Xe</td>
                <td class="dark-blue-text right-align">57 Wh</td>
            </tr>
            <tr>
                <td class="blue-text white-background">HP Spectre x360</td>
                <td class="brown-text right-align">512 GB</td>
                <td class="dark-blue-text right-align">66 Wh</td>
            </tr>
            <tr class="highlighted-34">
                <td class="blue-text">Asus ROG Zephyrus G14</td>
                <td class="dark-red-text">AMD Ryzen 9 6900HS</td>
                <td class="light-red-text left-align">32 GB</td>
                <td rowspan="2" colspan="1" class="brown-text white-background right-align">1 TB</td>
                <td class="dark-purple-text right-align">AMD Radeon RX 6700S</td>
                <td class="dark-blue-text right-align">76 Wh</td>
            </tr>
            <tr class="highlighted-42">
                <td class="blue-text">MSI Stealth 15M</td>
                <td class="dark-red-text">Intel Core i7-1280P</td>
                <td class="light-red-text left-align">16 GB</td>
                <td class="dark-purple-text right-align">NVIDIA RTX 3060</td>
                <td class="dark-blue-text right-align">99,9 Wh</td>
            </tr>
            <tr>
                <td colspan="6" class="merged-bottom">Dane komputerowe</td>
            </tr>
            <tr>
                <td colspan="6" class="last-cell">Źródło: własne</td>
            </tr>
        </tbody>
    </table>
    <p><a href="http://www.indexhtml.pl">Powrót do strony głównej</a></p>
</body>
</html>
