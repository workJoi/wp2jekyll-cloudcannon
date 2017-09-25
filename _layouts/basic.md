<!DOCTYPE html>
<html>

<head>
   <link rel="stylesheet" href="/css/cms-style-classes.css" />
    <style>
        #contentwrap {
            background: #ecebeb;
        }
        
        #contentwrap {
            box-shadow: inset 0 0 5px white, 1px 0px 5px rgba(0, 0, 0, 0.2);
        }
        
        #content {
            padding: 0 40px;
            background: #fff;
            max-width: 1170px;
            min-height: 400px;
            padding: 0 30px;
            box-shadow: 0 0 10px rgba(0, 0, 0, .1);
            margin: 0 auto;
        }
        
        .clearfix {
            clear: both;
        }
        
        #main {
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
        }

    </style>

</head>


<body>

    <div id="contentwrap">
        <div id="content" class="editable clearfix">
            <div id="main" class="clearfix">
                {{content}}
            </div>
        </div>
    </div>
</body>

</html>
