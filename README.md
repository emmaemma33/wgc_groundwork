# We Got Coders Programming Challenge

This is the application that we will be using to demonstrate our preparedness for the course. If you've already applied and are ready to get started, follow the instructions below. If you haven't yet applied, please read about We Got Coders and apply on our website, http://wegotcoders.com/trainees.

## INSTALL

Follow these steps to get going.

* Prepare a folder to put your work inside. We recommend using ```projects``` in your home folder.
```mkdir ~/projects```
* Fork this repository into your own GitHub account.
* Clone a copy to your local machine.
```
  cd ~/projects
  git clone <your-git-clone-url>
```
* Change directory to your cloned workspace in the terminal. ```cd wgc_groundwork```
* Run the ```bundle``` command. This will retreive dependencies that are required
in order for the application to work.
* Update app.rb to include your OAuth application id and application secret,
which you can find on your profile page (http://wegotcoders.com/trainees/sign_in).
* Run the application using the following command: ```ruby app.rb```. Don't forget
that every time you change app.rb, you must restart the server by entering ```CTRL+C```
in the terminal, and re-run ```ruby app.rb```.
* Cut + paste this URL into your browser: ```http://localhost:4567```. You should see the We Got Coders logo and some welcome text.
* Click the authorize link. The application will retrieve your profile data from We Got Coders. You may need to sign-in with your username and password.

## TODO

Attempt the following tasks. The list is meant to be progressively more
difficult and open-ended; the aim is to demonstrate your approach when dealing with programming issues and to test your initiative. Complete as much as you can within the time limit; you will not be penalised for not finishing the list. We are looking for self-motivated effort and to see how much of the groundwork you have grasped.

Don't forget to ```git add .``` and ```git commit``` after each step!

1. You should see a list of the profile data that you submitted to us when you
applied to We Got Coders. Use your knowledge of HTML / CSS to redesign and
layout the page in a presentable way. Show us what you can do with:

    * Headings
    * Lists
    * Backgrounds / Gradients
    * Multiple columns

2. Add an image of yourself to your profile. Add CSS where necessary to ensure that it looks presentable.

3. Observe how the about field works. What makes it bound to the data from your profile? Add more fields so that you can edit your profile.

4. Add a field to the form so that you can add your Codecademy account to
your profile. You will need an input text box, with the appropriate ```name``` attribute.

5. Update your profile with the full URL to your codeacademy. You should notice three fields in the response, js_track_completedness, web_track_completedness and ruby_track_completedness. Display each of these values as a progress bar, which displays the completed total of the Codecademy track. The shaded portion of the progress bar should be proportional to the percentage completedness of the given track.
If you have completed the groundwork, these values should be 100%!

5. Add some Javascript to the provided ```<script>``` tag in the views/index.erb file, that counts the number of words in each section. You ought to have at least twenty words for each of the questions.

6. Add code to the primes.rb file, that finds the sum of all prime numbers less than one hundred. Can you refactor the implementation so that you can pass in higher numbers to act as the limit? Find the sum of all prime numbers up to two million. Add a field to your profile named ```trainees[prime_sum]``` and enter in your answer.

7. Over to you! Make any adjustments that you see fit, and add a feature that you are interested in attempting. Perhaps you might:

    * Attempt a programming puzzle in Ruby, see http://projecteuler.net
    * Experiment with using JavaScript to respond to user events
    * Add some more pages and link them together

## FAQs / Troubleshooting

* If you see this message, then you haven't set your application id and secret correctly.

```Client authentication failed due to unknown client, no client authentication included, or unsupported authentication method.```

* If the profile fails to update, you may have failed validation on We Got Coder's servers. Read the error message and see if you can alter the input to address the issue.

* If you are having trouble updating your Codecademy, ensure that you have entered the correct URL to your profile page, including the http:// part of the URL.

* You can use any third-party frameworks that you wish: bootstrap, jQuery etc. but this is not necessary nor required.