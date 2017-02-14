//1
$(".profile-image").attr("src", "http://lorempixel.com/400/200/");

//1b
$("#left-image").children("img").attr("src", "http://lorempixel.com/400/200/");

//2
$( "h1.highlight" ).text("Paul Walsh");

//3
$( ".info-inner-container .info-title").text("Unemployment");

//4
$("#time-travel").remove();

//5
$("body").css({"color": "purple"});


//6
$(".highlight").css({"color": "yellow"});

//7
$("h1").css({"font-family": "monospace"});

//8
$(".action-icon-bg").css({'background-color': 'black'});


//9
$(".contact-info").attr("placeholder", "Identify yourself");


//10
$("#message").attr("placeholder", "state your buisness");


//11
$("#name").attr("placeholder", "your nemesis");


//12
$("#email").attr("placeholder", "koalathebear@gmail.com");


//13
$("#submit").attr("value", "En Garde!");


//1. That drawing of Pikachu is really cute. Let’s duplicate it using clone() and insert it at the bottom of the page using insertAfter() or appendTo().
$("#right-image").children("img").clone().appendTo("body");

//2. Wow, that was so satisfying I think we should do it 10 more times. Use a for loop to help you do this.
for (i = 1; i <= 10; i++) {$("#right-image").children("img").clone().appendTo("body");}

//3. Let’s add a message about when the page was last updated. We'll do this by appending a new <li> element to the <ul> in the sidebar (you might need to refresh the page to bring back the list items that we emptied out earlier).

echo "# Panda-the-Bear" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:ProgRockPaul/Panda-the-Bear.git
git push -u origin master
