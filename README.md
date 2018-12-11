<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title></title>
    <style>
        .divMax {
            width: 100%;
            margin-top: 10px;
        }

        .divFifty {
            width: 50%;
            float: left;
        }

        span {
            color: #b0b0b0;
            font-weight: 600;
        }

        select {
            width: 78%;
            padding: 12px;
            display: inline-block;
        }

        #NewOrder {
            margin-top: 10px;
            padding: 12px;
            /*background-color: #e5cf34;*/
            border: none;
            width: 16%;
            font-weight: 600;
        }

        #refresh {
            margin-top: 10px;
            padding: 12px;
            /*background-color: #c5c5c5;*/
            border: none;
            width: 20%;
            font-size: 105%;
            font-weight: 600;
        }

        #Billgenerate {
            margin-top: 10px;
            padding: 12px;
            /*background-color: #a1ef5a;*/
            border: none;
            width: 20%;
            font-size: 84%;
            font-weight: 600;
        }

        #Cancel {
            margin-top: 10px;
            padding: 12px;
            /*background-color: #ef5a5a;*/
            border: none;
            width: 20%;
            font-size: 84%;
            font-weight: 600;
        }

        #Reserved {
            margin-top: 10px;
            padding: 12px;
            /*background-color:#5ab1ef;*/
            border: none;
            width: 20%;
            font-size: 84%;
            font-weight: 600;
        }

        #ReleaseTable {
            margin-top: 10px;
            padding: 12px;
            /*background-color:#5aefda;*/
            border: none;
            width: 16%;
            font-size: 84%;
            font-weight: 600;
        }

        input[type=text] {
            margin-top: 10px;
            padding: 12px;
            /*background-color: #c5c5c5;*/
            /*border: none;*/
            width: 93%;
        }

        .rightorient {
            float: right;
            text-align: right;
        }

        .clear {
            clear: both;
        }

        .veg {
            background-color: #5ebc5e;
            border: none;
            color: #fff;
            font-size: 84%;
            padding: 3px;
        }

        .nonveg {
            background-color: #801d06;
            border: none;
            color: #fff;
            font-size: 84%;
            padding: 3px;
        }
    </style>
    <style>
        .btnddMenu {
            background: green;
            color: #fff;
            border: none;
            padding: 6px;
        }

        #paremtMenudv {
            width: 96%;
            overflow-x: scroll;
            height: 72px;
            overflow-y: -webkit-paged-x;
        }

        #ParentMenu {
            list-style-type: none;
            padding: 1px 15px;
            display: inline;
        }

            #ParentMenu Li, a {
                Float: Left;
                padding: 8px 10px;
                text-decoration: none;
                border-radius: 12px;
                color: #104d7d;
                font-size: large;
                font-weight: 600;
            }

        #dvmenu {
            padding-left: 12px;
            background-color: #c5c5c533;
            min-height: 70%;
            min-width: 95%;
            max-height: 325px;
            overflow-y: scroll;
        }

        #Search {
            padding: 18px;
            width: 80%;
            border-left: transparent;
            border-right: transparent;
            border-top: transparent;
            border-bottom: 2px solid #b3b1b1;
            color: #52888a;
            font-weight: 700;
        }

        body {
            font-family: monospace;
            top: 0;
            left: 0;
            right: 0;
            /*margin: 0;*/
            overflow-x: hidden;
        }

        h3 {
            color: #040404bd;
        }

        #NavMainRight-Sm {
            display: none;
            width: 20%;
            Float: Right;
            padding: 16px 0px;
            color: #fff;
            background: transparent;
            border: navajowhite;
        }

            #NavMainRight-Sm button {
                background: transparent;
                color: #fff;
                border: none;
                font-size: 22px;
            }

        #MyNavname:hover {
            Color: #fdf729;
            cursor: pointer;
            word-spacing: 12px;
        }

        #Myname:hover {
            Color: #2269a1;
            cursor: pointer;
            word-spacing: 12px;
        }

        #nav {
            width: 100%;
            background: #040404bd;
            height: 50px;
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            box-shadow: 0px 14px 20px -4px #000;
            position: fixed;
        }

        #NavMainLeft {
            width: 20%;
            Float: Left;
            padding: 1px 0px;
            color: #fff;
        }

        #NavMainRight {
            width: 80%;
            Float: Right;
            padding: 1px 0px;
            color: #fff;
        }

            #NavMainRight Ul {
                list-style-type: none;
                Float: right;
                padding: 0px 15px;
            }

                #NavMainRight Ul Li, a {
                    Float: Left;
                    padding: 10px 10px;
                    text-decoration: none;
                    border-radius: 12px;
                }

                    #NavMainRight Ul Li:hover {
                        Float: Left;
                        padding: 10px 10px;
                        text-decoration: none;
                        color: #0e0c7d;
                        color: #25d2cc;
                    }

                    #NavMainRight Ul Li a {
                        text-decoration: none;
                        font-size: x-large;
                        color: #fff;
                    }

                        #NavMainRight Ul Li a:hover {
                            text-decoration: none;
                            font-size: x-large;
                            color: #0e0c7d;
                        }

        #NavMainRight-Sm Ul {
            list-style-type: none;
            Float: right;
            padding: 1px 15px;
            background-color: #040404bd;
            width: 491%;
            display: none;
            box-shadow: 0px 14px 20px -4px #000;
        }

            #NavMainRight-Sm Ul Li, a {
                Float: Left;
                padding: 10px 10px;
                text-decoration: none;
                width: 100%;
            }

                #NavMainRight-Sm Ul Li:hover {
                    Float: Left;
                    padding: 10px 10px;
                    text-decoration: none;
                    color: #0e0c7d;
                    background-color: #fff;
                }

                #NavMainRight-Sm Ul Li a {
                    text-decoration: none;
                    font-size: x-large;
                    color: #fff;
                }

                    #NavMainRight-Sm Ul Li a:hover {
                        text-decoration: none;
                        color: #fff;
                        color: #0e0c7d;
                    }

        #NavMainRight-Sm button :focus + #lstMenu {
            display: block;
        }

        #main {
            height: 75%;
            text-align: center;
            padding: 99px;
        }

        #Skills {
            height: 75%;
            text-align: center;
            background-color: #040404bd;
            top: 0;
            left: 0;
            right: 0;
            padding: 99px;
        }

        table {
            width: 90%;
        }

            table tr th {
                color: #a91818;
                cursor: pointer;
                word-spacing: 4px;
                font-size: x-large;
            }

            table td {
                padding: 1px 0px;
                color: #4899b1;
                cursor: pointer;
                word-spacing: 4px;
                font-size: x-large;
            }

        #projecttabl tr:hover {
            padding: 1px 0px;
            color: #fff;
            cursor: pointer;
            word-spacing: 4px;
            font-size: x-large;
        }

        #projects {
            height: 75%;
            text-align: center;
            background-color: #05213ebd;
            top: 0;
            left: 0;
            right: 0;
            padding: 99px;
        }

        #contacts {
            height: 75%;
            text-align: center;
            background-color: #20053ebd;
            top: 0;
            left: 0;
            right: 0;
            padding: 99px;
        }

        #map {
            height: 100%;
            background-color: #fff;
            min-width: 546px;
            min-height: 340px;
        }

        #footer {
            height: 5%;
            text-align: center;
            background-color: #185fa9cf;
            top: 0;
            left: 0;
            right: 0;
            padding: 5px;
        }

        @media (max-width: 707px) {
            #NavMainRight {
                display: none;
            }

            #NavMainRight-Sm {
                display: block;
            }

            body {
                overflow: none;
            }

            #map {
                height: 10%;
                background-color: #fff;
                min-width: 245px;
                min-height: 200px;
            }

            .addmenuinput {
                padding: 4px;
            }

            table td {
                padding: 1px 0px;
                color: #4899b1;
                cursor: pointer;
                word-spacing: 4px;
                font-size: 14px;
            }

            .btnddMenu {
                background: green;
                color: #fff;
                border: none;
                padding: 4px;
            }

            .ordercntipt {
                width: 19px;
                padding: 2px;
            }

            #Search {
                font-size: 60%;
            }
        }

        @media (min-width:707px) {
            #Search {
                width: 50%;
            }
        }
    </style>
</head>
<body>
    <div id="nav">
        <div id="NavMainLeft">
            <h1 style="padding-left: 19px;text-shadow:2px 2px 8px #000;padding-top: 5px;" id="MyNavname"><!--HotelMenu--></h1>
        </div>
        <div id="NavMainRight">
            <ul>
                <li><a href="#Skills">Menu</a></li>
                <li><a href="login.html">Track Order</a></li>
                <li><a href="#main">About us </a></li>
                <li><a href="#Skills">Terms and Conditions</a></li>
            </ul>
        </div>
        <div id="NavMainRight-Sm">
            <button onclick="myfucntion()">+</button>
            <ul id="lstMenu">
                <li><a href="#Skills">Menu</a></li>
                <li><a href="login.html">Track Order</a></li>
                <li><a href="#main">About us </a></li>
                <li><a href="#Skills">Terms and Conditions</a></li>
            </ul>
        </div>
    </div>
    <div class="divMax" style="margin-top:75px">
        <div class="divFifty"><span>OfflineOrder</span></div>
        <div class="divFifty rightorient">Rohit Survey (Manager)</div>
    </div>
    <div class="clear"></div>
    <div class="divMax">
        <button id="refresh">Refresh</button>
        <select>
            <option>(14 Table Remain - 7 Table Occupied)</option>
            <optgroup label="First Floor">
                <option>11</option>
                <option>12</option>
                <option label="13 Customer Seating (3.35PM) Order Not Taken">13</option>
                <option label="14 Customer Seating (2.55PM) Waiting for Bill">14</option>
                <option>15</option>
                <option label="16 Customer Seating (3.03PM) Order Food Preparing">16</option>
                <option label="17 Customer Seating (3.35PM) Order Not Taken">17</option>
                <option>18</option>
                <option>19</option>
                <option>20</option>
            </optgroup>
            <optgroup label="Ground Floor">
                <option>1</option>
                <option label="2 Customer Seating (3.09PM) Food Preparing">2</option>
                <option>3</option>
                <option label="4 Customer Seating (3.03PM) Order in Process">4</option>
                <option>5</option>
                <option>6</option>
                <option>7</option>
                <option>8</option>
                <option disabled label="9 Reserved for (5.00 PM)">9</option>
                <option>10</option>
            </optgroup>
        </select>

        <br />
        <button id="NewOrder">New Order</button>
        <button id="Billgenerate">Bill Generate</button>
        <button id="Cancel">Cancel Order</button>
        <button id="Reserved">Reserve Table</button>
        <button id="ReleaseTable">Release Table</button>
    </div>
    <div class="clear"></div>
    <div class="divMax">
        <div class="divFifty"><span>Menu</span></div>
        <div class="divFifty rightorient"><button class="veg">Veg </button><button class="nonveg">Non Veg</button></div>
    </div>
    <div class="clear"></div>

    <div style="clear:both"></div>
    <div>
        <center>
            <input id="Search" type="text" placeholder="Search : Veg Paneer Makhni,Cuisine,Dish Name,etc...">
        </center>
    </div>

    <div style="clear:both"></div>
    <br>
    <div id="dvmenu">
        <div id="paremtMenudv">
            <ul id="ParentMenu">
                <li><a href="#Starters">Starters</a></li>
                <li><a href="#Salad">Salad</a></li>
                <li><a href="#Appetizer">Appetizer</a></li>
                <li><a href="#Skills">Tandoor se</a></li>
                <li><a href="#main">Main Course</a></li>
                <li><a href="#Skills">Sweet Tooth</a></li>
                <li><a href="#main">Cold Drink</a></li>
                <li><a href="#Skills">Mocktails</a></li>


                <li><a href="#Starters">Starters</a></li>
                <li><a href="#Salad">Salad</a></li>
                <li><a href="#Appetizer">Appetizer</a></li>
                <li><a href="#Skills">Tandoor se</a></li>
                <li><a href="#main">Main Course</a></li>
                <li><a href="#Skills">Sweet Tooth</a></li>
                <li><a href="#main">Cold Drink</a></li>
                <li><a href="#Skills">Mocktails</a></li>
            </ul>
        </div>
        <table border="0">
            <tr>
                Panner
                <th style="text-align: left;">Item</td>
                <th nowrap style="color:#727070;;text-align: right;">Price</td>
                <th style="text-align: right;width: 24%;"></td>
            </tr>
        </table>
        <div style="overflow-y:scroll;overflow-x:hidden;    height: 54%;">


            <div id="Starters">
                <table border="0">
                    <tr>
                        <td><label style="color:#000">Starters</label></td>
                    </tr>
                    <tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="ordercntipt" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                </table>
            </div>

            <div id="Salad">
                <table border="0">
                    <tr>
                        <td><label style="color:#000">Salad</label></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Veg Salad</span></td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="addmenuinput" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Veg Cheese Salad</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                </table>
            </div>

            <div id="Appetizer">
                <table border="0">
                    <tr>
                        <td><label style="color:#000">Appetizer</label></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Veg Salad</span></td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input class="addmenuinput" type="text" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Veg Cheese Salad</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>

                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div> <span style="padding-left:12px">Panner Tikka</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                    <tr>
                        <td><div style="width: 7%;display: inline;border: 1px solid green;"><span style="font-size:  40px;color: green;">.</span></div><span style="padding-left:12px">Harabhara Kabab</span> </td>
                        <td nowrap style="color:#727070;;text-align: right;">Rs 260</td>
                        <td style="text-align: center;width: 24%;"><button class="btnddMenu" style="">+</button><input type="text" class="addmenuinput" value="0" min="0" style="width:22px;    padding: 4px;" /><button class="btnddMenu">-</button></td>
                    </tr>
                </table>
            </div>




        </div>

    </div>

    <div id="footer">
        <center>
            <h3 style="color:#fff;text-shadow: 2px 2px 8px #000">Handcrafted by Kaustubh Bagwe @ 2018</h3>
        </center>
    </div>
</body>
</html>
