
<html lang="en"><head><meta name="viewport" content="width=device-width, initial-scale=1.0">



    <meta charset="UTF-8">
    <title>Secure Contact Form</title>
    <style>
        body {
            font-family: "Helvetica Neue", Arial, sans-serif;
            background: linear-gradient(135deg, #f0f0f0 0%, #ffffff 100%);
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 100%;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 20px;
            box-sizing: border-box;
        }
        h1 {
            margin-bottom: 30px;
            font-size: 2em;
            color: #333;
        }
        .form-wrapper {
            background: #fff;
            border-radius: 8px;
            padding: 30px;
            max-width: 450px;
            width: 100%;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        label {
            display: block;
            margin: 15px 0 5px;
            font-weight: bold;
            font-size: 0.9em;
            color: #555;
        }
        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 0.95em;
            box-sizing: border-box;
            transition: border-color 0.3s;
        }
        input[type="text"]:focus,
        input[type="email"]:focus,
        textarea:focus {
            border-color: #007BFF;
            outline: none;
        }
        textarea {
            resize: vertical;
            min-height: 100px;
        }
        .error {
            background: #fdd;
            color: #c00;
            padding: 10px;
            border-radius: 4px;
            margin-bottom: 15px;
            font-size: 0.9em;
        }
        .success {
            background: #dff0d8;
            color: #3c763d;
            padding: 10px;
            border-radius: 4px;
            margin-bottom: 15px;
            font-size: 0.9em;
        }
        input[type="submit"] {
            background: #007BFF;
            color: #fff;
            border: none;
            font-size: 1em;
            padding: 12px 20px;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 20px;
            transition: background 0.3s;
        }
        input[type="submit"]:hover {
            background: #0056b3;
        }
        .footer {
            margin-top: 20px;
            font-size: 0.8em;
            color: #999;
        }
    </style>
    </head>
    <body>
    
    <div class="container">
        <h1>[Your app name] Data Delete Request</h1>
        <div class="form-wrapper">
            
                        <form action="" method="post" novalidate="">
      To delete your information stored from [Your app name], you will have to send an email request to 
      <a href="mailto:DPO@unity3d.com
              ?subject=Request%20to%20Delete%20Collected%20Personal%20Information
              &amp;body=Hello%20Unity%20Team,%0D%0A%0D%0A
                     I%20am%20writing%20to%20request%20the%20permanent%20deletion%20of%20all%20personal%20data%20you%20have%20collected%20about%20me.%20
                     Please%20confirm%20once%20this%20request%20has%20been%20completed.%0D%0A%0D%0A
                     Thank%20you%20for%20your%20prompt%20attention%20to%20this%20matter.%0D%0A%0D%0A
                     Best%20regards,%0D%0A%0D%0A
                     [Your%20Full%20Name]">
        DPO@unity3d.com
      </a><br><br>For more information, see the <a href="https://unity.com/legal/privacy-policy">Unity Privacy Policy</a>
    
            </form>
                </div>
    
        <div class="footer">
            
        </div>
    </div>
    
    
    
    </body></html>
