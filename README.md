# cmsc388-project-2--first-flask-app---poke-info-solved
**TO GET THIS SOLUTION VISIT:** [cmsc388 Project 2- First Flask App – Poke-Info Solved](https://www.ankitcodinghub.com/product/cmsc388-p2-first-flask-app-poke-info-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;132052&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;cmsc388  Project 2- First Flask App - Poke-Info Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Description

You will be creating a website allowing users to pick a Pokemon and get more info about the pokemon, as well as to see which pokemon have a certain ability.

Setup

We recommend using the same virtual environment for all projects, so you can use a common one created in CMSC388J-spring22/, the root of the class repository.

Once you have a virtual environment, activate it, use the appropriate command for your system. Then, to install the necessary packages, navigate to p2/ and run pip3 install -r requirements.txt.

Alternatively: pip3 install Flask requests python-dotenv.

More detail on virtual environments are on the slides.

For this project, we’ll be using the requests, Flask, and python-dotenv packages. If you ran the above command to install from requirements.txt, you’re all set.

Project

The project will not run in its starter form, because not all of the routes have been configured yet. To run your project after making some progress, refer to the Testing section below.

In model.py, we’ve defined a class named PokeClient. In app.py, we create an instance of the class. This is the only instance of the class that you need. You should not modify the PokeClient class. Look at the methods in the class definition; you can call these methods with dot syntax, i.e. poke_client.get_pokemon_list() or poke_client.get_pokemon_info(self, ‘bulbasaur’).

In model.py, we’ve included sample usages of the PokeClient class. If you run the model.py class directly with python model.py, you’ll see the output corresponding to each print statement in your console.

We provided a base.html file from which you should extend all of your other templates. There’s an example index.html file that just displays “Poke-Info website!” when the website is first opened.

You should create two more templates (so you will have a total of four HTML templates when the project is finished) for the Pokemon info and ability info pages. These pages are explained below.

Implement the following functions with the corresponding routes:

1. index() – Should show a list of all Pokemon, with links to pages that give more info

The list of pokemon should be seen at the route /.

Each element in the list should be a link to another page which will give more info about the chosen Pokemon with a certain name. The additional Pokemon info page should be located at /pokemon/&lt;pokemon_name&gt;.

You can get a list of Pokemon names with the get_pokemon_list() method of the PokeClient class.

2. pokemon_info(pokemon_name) – Should show all info about the specified Pokemon.

We should be able to navigate to /pokemon/&lt;pokemon_name&gt; and see info about the Pokemon identified by pokemon_name. The info includes the name, weight, and other data.

The get_pokemon_info() method of the PokeClient class returns a dictionary with all of the info that you need. The dictionary of info will have a list of names of abilities. Each of these abilities must be presented as a clickable link to another page, located at

/ability/&lt;ability_name&gt;.

There should be a clearly visible link to go back to the front-page of the website, located at /.

3. pokemon_with_ability(ability_name) – Should show a list of Pokemon who have the specified ability.

We should be able to navigate to /ability/&lt;ability_name&gt; and see a list of Pokemon names identifying Pokemon that have the ability specified by ability_name.

The get_pokemon_with_ability() method of the PokeClient class returns a list of Pokemon names with the ability. The list of

Pokemon names should be presented as a series of clickable links that will take the website user to the info page for that Pokemon, located at /pokemon/&lt;pokemon_name&gt;.

There should be a clearly visible link to go back to the front-page of the website, located at /.

Reminder: Make lists in HTML by using what we went over in class.

Testing

When your current directory is flask_app/, you can simply run the command flask run in your terminal or command line to see your website. It’s important to be in the flask_app/ directory so that you can use the values set in the .flaskenv file automatically.

The .flaskenv file makes it so that you don’t have to set the FLASK_APP environment variable manually and the environment is set to development so that errors will be shown in the browser instead of crashing your app.

Additionally, if you reload the page when in the development mode, you can see the changes made to your website without having to manually shut down the running app and restarting it.

Run your flask app, make sure you have a long list of Pokemon names that are links, and try clicking on some of them to see if the correct info page pops up. Try clicking on one of the abilities under each Pokemon to see if you get working links to the Pokemon with that ability. Check that you have a link clearly visible on the page for Pokemon info and ability info to go back to the frontpage of our website.

If you check a few pokemon and abilities throughout the entire list, you should be fine, because its fairly certain that your logic is sound at that point.

Submissions

Make sure that you’ve tested parts of your website and that links to the frontpage exist and are clearly visible, and then zip the flask_app/ directory.

The directory, along with its contents, should be zipped, not the contents of the directory. In other words, when we unzip your file, we should see the flask_app/ directory. If you have any questions on how to submit, please contact us.

Grading

After zipping, submit the zip file to the appropriate ELMS page. No test results will be shown.

Your project will be graded according to (1) correctness, and (2) robustness. Here are the correctness requirements:

Correctness:

| Requirement | Points | | ——————————————————————————————————————— | —

————– | | All Pokemon visible on front page as clickable links, with no duplicate info. | 15 | | All Pokemon info returned from the

PokeClient class is visible on the respective info page, with no duplicate info. | 20 | | All Pokemon names visible and presented as links to Pokemon info pages on the ability pages, with no duplicate info. | 15 | | Link on Pokemon and ability info pages to the front page clearly visible and works. | 10 | | Two more templates created for the Pokemon and ability info pages extending base.html | 10, (5 for each) | | Correct routes in app | 10 | | url_for used to create links and render_template used | 10 | | Jinja2 control flow statements used to dynamically create HTML in template files. | 10 |

Robustness:

An example of a small error: syntax error in a Jinja template.

An example of a large error: a view function not being configured properly.

The project will be graded out of a 100 points. You won’t be graded for style, but make sure your code is readable.
