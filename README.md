<!doctype html>
<html>
    <head>
        <title>Contact Us</title>
    </head>
    <body>
        <div class="content">
            <form >
                <br/>
                <label style="display:inline-block;width:200px;text-align:right;">First Name:</label>
                <input type="text" name= "firstName" size="30" /><br/>
                <br/>
                <label style="display:inline-block;width:200px;text-align:right;">Last Name:</label>  
                <input type="text" name= "lastName" size="30"/><br/>
                <br/>
                <label style="display:inline-block;width:200px;text-align:right;">Email:</label>
                <input type="text" name= "emailAddress" size="30"/><br/>
                <br/>
                <label style="display:inline-block;width:200px;text-align:right;">Type of License:</label>
                <input type="radio" name="license" value="business">Business
                <input type="radio" name="license" value="personal">Personal<br/>
                <br/>
                <label style="display:inline-block;width:200px;text-align:right;">Reason:</label>    
                <select name="dropDownMenu">
                    <option value="Value1">Select a Reason</option>
                    <option value="Value2">Software Support</option>
                    <option value="Value3">Hardware Support</option>
                    <option value="Value4">Information Request</option>
                </select><br/>
                <br/>
                <label style="display:inline-block;width:200px;text-align:right;">Additional information:</label>  <textarea name="briefDescription"></textarea><br/>
                <br/>
                <input type="checkbox" name="readTerms" value="Yes" style="margin-left: 203px">I have read the terms of service.<br/>
                <br/>
                <input type="submit" value="Send Request" style="margin-left: 203px"/>
            </form>
        </div>
    </body>
</html>

