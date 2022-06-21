

<!DOCTYPE html>
<html>
<head>
<title>GPT-3 and A.I.</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial;}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>
</head>
<body>

<h2>GPT-3 and A.I</h2>
<p>Click on the buttons inside the tabbed menu to learn more:</p>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'About')">About</button>
  <button class="tablinks" onclick="openCity(event, 'Resources')">Resources</button>
  <button class="tablinks" onclick="openCity(event, 'Projects')">Projects</button>
</div>

<div id="About" class="tabcontent">
  <h3>About A.I GPT-3</h3>
  <p>When someone mentions artificial intelligence, the first that pops up in my mind is the terminator. I see it as robots taking over the world. Usually, that’s the way sci-fi has made it. But now the sci-fi predictions are coming to play, with GPT-3.It can now be used in a college student’s dorm.</p>
<img src=" "></img>

<p> GPT-3 runs on 175 million parameters. Meaning its complexity of models is now 10 times the size of GPT-2. The hype is that now these models can produce human-like responses, requiring little training compared to GPT-2.</p>

<p> Now, where here is its fancy definition: GPT-3 makes a task-agnostic natural language processing model that requires minimal fine-tuning. Let’s break these words down, task-agnostic means only having to train the model once, allowing for a variety of tasks to be performed. Minimal fine-tuning meaning that it only needs a few examples to perform its task. It can generate an essay response out of a sentence in less than 10 seconds. Several experiments were run on humans to test GPT-3 effectiveness. By predicting which texts were A. I generated. 88 percent of people are choosing human-generated in the case of GPT-3 with the best quality. Then with low GPT-3 quality, only 39 percent of people were tricked.</p>

<p>Quantitative search is another thing about GPT-3. For instance, on Wikipedia an article might be searched on why people suffer from scoliosis, GPT-3 would generate an answer using the information in the article. You might have seen a quantitative search on google when you search something and some text appears highlighted. Another application of the model of GPT-3, is a chatbox, which has been seen implanted in many companies.</p>

<h2><strong>How does GPT-3 Work?</strong></h2>
<p>GPT-3 was trained with 500 million words and generated 175 billion parameters. A parameter is a measure of the complexity of a model and it generates how accurate the result is. The model is trained to predict the next results by providing examples. For example, if we were to ask as the input, how was your day today? The output could be What are your plans for the weekend? It provides a continuation to the answer, not an answer. To fix this problem you could provide examples of the input and output. For example, what is your favorite food, and say the answer in this case pasta. By this, the GPT-3 would follow that same logic to generate outputs.</p>

<p>GPT-3 is expensive with its training costing 12 million USD. OpenA.I have launched different models of GPT-3 for it to become more accessible. GPT-3 full code is available through an API key. Which can be accessed by going on OPenAI and filling out a form to gain access. Each is modified differently based on quality, cost, and speed. The four models are Davinci, curie, Babbage, and ADA. Davinci is the best one producing the best quality, but it has slow speed and its cost is high. Curie has a slightly faster speed than Davinci and 10 times lower cost than Davinci. Ada is known for being the fastest and very cheap, but not producing the best quality.</p>

<h3><strong>What are GPT-3 Dangers?</strong></h3>

<p>GPT-3 can be used for propaganda and misuse. In addition to bias, being built in the model with it not being politically correct. This adds to the reason why facial recognition companies are putting a moratorium on release to U.S. authorities. The authors of the paper did highlight its bias and fairness issues with GPT-3. Found that it associated occupations with males. An associated negative sentiment with black people and Islamic terms with terrorism. Due to the data sets having been historically written that is why. Fact-checking into models has not been established, which leads to the misinformation side of it.</p>

<p>Energy consumption required for GPT-3 requires two or three orders of magnitude of computing power, then the next big GPT model. Which leads enormous gap for research groups that do not have access to that amount of computing power. In addition, training models with this amount of energy usage are not great for the environment.</p>

<h4><strong>What can we do with GPT-3?</strong></h4>
<p>Even though, GPT-3 is not exactly accessible to everybody. GPT-3 does have the power to take jobs away, as it functions to perform a human task. It takes more words than a person has learned in a life-spanned to train GPT-3, with all possible inputs. But it can be trained to familiarize itself with words faster than humans, which makes it useful when presenting solutions to nuclear waste. But with restrictions, the research is geared to who has access to it.</p>

</div>


<div id="Resources" class="tabcontent">
  <h3>Resources</h3>
  <h1>This is where find resources to learn more about this subject.</h1> 
<a href="https://ai-4-all.org/summer-programs/">AI-4-ALL</a>
<hr>
<a href="https://oso.stanford.edu/news/ai-camp-summer-ages-13-18">stanford.AI</a>
<hr>
<a href="https://ai.google/education/">Google.AI</a>

</div>

<div id="Projects" class="tabcontent">
  <h3>Project you can work on :)</h3>
<li> Animal Species</li>
<li>Prediction Teachable Machine </li>
<li> Chatbots </li>
<li> Handwritten Digit Recognition</li>
</div>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>
   
</body>
</html>






















