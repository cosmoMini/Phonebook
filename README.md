<html>
    <head>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
        <script src="phoneBook.js"></script>
        <link href="phoneBook.css" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div id="nav"><p style="padding: 15px; font-size: 25px;">Phone Book</p></div>
        <div class="content">
            <div style="height: 20%">
                <input type="button" value="Add" id="butt">
            </div>
            <div class="showContent">
                <div class="showName"></div>
                <div class="showNumber"></div>
                <div class="showButt"></div>
            </div>
            <div id="formAdd">
                <form>
                    <input type="text" name="uname" id="un" placeholder="Enter name here" required><br>
                    <input type="number" name="unum" id="nu" placeholder="Enter number here" maxlength="15" min="10"  required>
                    <br>
                    <input type="button" value="Add" id="finalAdd">
                </form>
            </div>
            <div id="error" style="color: red; font-family: monospace; font-size: 15px; position: relative; margin-right: 50%; margin-left: 5%;">* Fill the fields first!</div>
        </div>
        <div id="showRuntime">
            <p id="nameHere" style="padding: 5px;">Name:</p>
            <p id="numbHere" style="padding: 5px;">Number:</p>
        </div>
    </body>
</html>
