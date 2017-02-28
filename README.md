# Assignment5
<!DOCTYPE html>
<html>
  <head>
    <title>
      CSS and some basic text formatting
    </title>

    <style>
      /* This is how we write comments in CSS */
      /* CSS stands for "Cascading Style Sheets". We will explore the
      "cascading" property later. For now "Style" is the key */
      /* Use
      http://www.w3schools.com/cssref/css_websafe_fonts.asp
      for reference */
      /* I will be using several different ways to reference color
      throughout this example file. Use
      http://www.w3schools.com/colors/default.asp
      for reference */
      h1{
      /* we can change default styles for specific tags */
        font-family: "Comic Sans MS", cursive, sans-serif; /* Oh, the dreaded Comic Sans!! */
        color: pink;
      }
      .all_my_headers{
      /* we can add a specific CLASS to a tag and target changes that way */
        text-decoration: underline;
      }
      p{
        font-family: "Courier New", Courier, monospace;
      }
      em{
        color:rgba(255, 0, 0, 0.9);
        font-weight: bold;
      }
      #call_to_action{
      /* we can add a specific ID to a tag and target changes that way
        the difference between CLASS and ID is in the fact that we can
        use ID only once per document and CLASS may be added to as many
        tags as you desire
      */
        background: #ff0000;
        font-size: 20px;
        color: #fff;
      }
    </style>

  </head>

  <body>
    <h1 class="all_my_headers"> Examples of Formatted Text </h1>

    <p>
      Here are some examples of text formatting using html tags.
      Later on you will see more <em>sophisticated formatting</em> with css but
      is a good start.
    </p>
    <h2 class="all_my_headers"> There are other </h2>
    <h3 class="all_my_headers"> header sizes </h3>
    <p id="call_to_action">
      You can google them :)
    </p>

  </body>
</html>
