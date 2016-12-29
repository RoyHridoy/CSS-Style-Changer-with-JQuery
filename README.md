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

 <pre>
    &lt;div class=<span>"style-changer"</span>&gt;
        &lt;div class=<span>"style-box-control"</span>&gt;
            &lt;button&gt; &lt;i class=<span class="change-color">"fa fa-cog fa-spin"</span>&gt;&lt;/i&gt;&lt;/button&gt;
        &lt;/div&gt;
        &lt;div class=<span class="change-color">"style-changer-box"</span>&gt;
            &lt;button data-file=<span class="change-color">"default"</span> class=<span class="change-color">"color-default disabled"</span>&gt;&lt;/button&gt;
            &lt;button data-file=<span class="change-color">"red"</span> class=<span class="change-color">"color-red"</span>&gt;&lt;/button&gt;
            &lt;button data-file=<span class="change-color">"green"</span> class=<span class="change-color">"color-green"</span>&gt;&lt;/button&gt;
            &lt;button data-file=<span class="change-color">"gold"</span> class=<span class="change-color">"color-gold"</span>&gt;&lt;/button&gt;
            &lt;button data-file=<span class="change-color">"blue"</span> class=<span class="change-color">"color-blue"</span>&gt;&lt;/button&gt;
            &lt;button data-file=<span class="change-color">"skyblue"</span> class=<span class="change-color">"color-skyblue"</span>&gt;&lt;/button&gt;
        &lt;/div&gt;
    &lt;/div&gt;
</pre>

3. create variations

Now create color folder inside css folder then give your css version

like this: css/color/(all css here)
