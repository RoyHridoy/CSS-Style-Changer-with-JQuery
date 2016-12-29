# CSS-Style-Changer-with-JQuery
Live Preview http://royhridoy.com/github/stylechanger/
How to use:
1. Getting Started

    <!-- Style changer css -->
    <link rel="stylesheet" href="style-changer.css">

    <!-- Set default color css -->
    <link rel="stylesheet" data-style="styles" href="css/color/default.css">

    <!-- Call style-changer.js plugin -->
    <script src="js/style-changer.js"></script>
        

2. Set up your HTML

    <div class="style-changer">
        <div class="style-box-control">
            <button> <i class="fa fa-cog fa-spin"></i></button>
        </div>
        <div class="style-changer-box">
            <button data-file="default" class="color-default disabled"></button>
            <button data-file="red" class="color-red"></button>
            <button data-file="green" class="color-green"></button>
            <button data-file="gold" class="color-gold"></button>
            <button data-file="blue" class="color-blue"></button>
            <button data-file="skyblue" class="color-skyblue"></button>
        </div>
    </div>
        

3. create variations

Now create color folder inside css folder then give your css version

like this: css/color/(all css here)
