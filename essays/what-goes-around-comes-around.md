---
layout: essay
type: essay
title: "What Goes Around, Comes Around"
# All dates must be YYYY-MM-DD format!
date: 2023-01-22
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

## The Foundation Of A Community

Nobody is a perfect software engineer, and everybody still has skills in programming that they can learn or perfect. Thus, having a community of people who are all at different levels of knowledge in different areas of the subject help to provide some kind of hive-like productivity within the programming world. If smart questions are being asked, more often than not a smart answer will be given. It is this knowledge sharing that increases the collective efficiency of the entire system and helps the entire community of software engineers progress to create new and exciting technologies.

At the very basis of this collective progression though, must be the fundamental skill of knowing how to work collectively. It means that you must be willing to think and act as if you are part of a team, even when you might be working on a project alone. One must convey an attitude of gratitude and make it as easy as possible for others to offer their help, and vis versa. Furthermore, the only way to successfully communicate that attitude is through the quality of the questions that you ask and answer, because this is really the only communication that will be received. Lastly, part of what motivates the question/answer dialog of a forum might just be that their is an inherent promise that if I can provide some knowledge of a topic in an area where I happen to know more about than the average programmer, then perhaps that benefit will be passed around and I will one day be provided with similar help.

*What goes around, comes around.*

Thus, the image being conveyed of the person asking the question in the mind of a potential answerer is almost just as important, if not more important, than the actual difficulty of the question, because it conveys that person’s future willingness to contribute to the community.

An as example of someone who is clearly on a race of their own and does not value the contribution of the community, and would almost certainly not be a future contributor, consider this question posted to Stack Overflow:

## [Stupid Question](https://stackoverflow.com/questions/44009047/change-to-defayl-map-image-dont-work)

```
My code does not work I don't know why change the inactive images replace whit a default pictures and the code dont work.

<script type="text/javascript">
        $(document).ready(function(){
            $('#map_image').error(function() {
                var $img = $(this);
                setTimeout(function(){
                    $img.attr('src', '<?=base_url('assets/images/mapnotfound.png');?>' + '?' + Math.random());
                }, 1000);
            });
        }); 
    </script>
View code is:

'.img(array('src'=>$this->settings->map_image($server->game, $server->currentmap),'id'=>'map_image','width'=>'120px','height'=>'120px')).'
Help me please to fix this plroblems.

Thanks

Top Answer: *No answer*

```

As clearly evident, this person seems to have barely put in their own full effort into searching for a solution to solve their problem. “My code does not work and I don’t know why…” is not a very motivating start to anyone looking to provide help.

Furthermore, they did not even care enough to use correct grammar or spelling in asking their question, which in the minds of an answerer may suggest that they put equally little effort into finding a potential solution on their own. This undoubtedly leads to the thought of “why should I put in my effort to help you, when you won’t even put in that effort to help yourself?”. Unsurprisingly, the question remains unanswered to this day.

Now to depart from this negative light and consider the following question posted as an example of the power that this community holds. This question clearly conveys effort on the part of the questioner, and gives a reasonable level of confidence to the answerer that this person is genuinely using the forum as a last resort and will one day be a contributor as they progress in their skillset.

## [Smart Question](https://stackoverflow.com/questions/208105/how-do-i-remove-a-property-from-a-javascript-object)

```
How do I remove a property from a JavaScript object?

Given an object:
let myObject = {
  "ircEvent": "PRIVMSG",
  "method": "newURI",
  "regex": "^http://.*"
};

How do I remove the property regex to end up with the following myObject?
let myObject = {
  "ircEvent": "PRIVMSG",
  "method": "newURI"
};


Top Answer:

To remove a property from an object (mutating the object), you can do it like this:
delete myObject.regex;
// or,
delete myObject['regex'];
// or,
var prop = "regex";
delete myObject[prop];

Demo:
var myObject = {
    "ircEvent": "PRIVMSG",
    "method": "newURI",
    "regex": "^http://.*"
};
delete myObject.regex;

console.log(myObject);
```
 
Albeit a rather basic question, it was a clear and concise question with an example of the code and a clear goal for the answerer to work towards. This makes it an extremely easy question to answer.

Although the questioner does not provide any code as to what they may have already tried (which would add more value to this question), they also do not waste the answerer’s time by claiming they found a bug, seeking urgent attention, or doing any other frowned upon practice when seeking help via such a forum. Also, there are no basic grammar or spelling errors, unlike the previous example. Again unsurprisingly, this question has a very complete and clear answer, with many different scenarios in which one may want to delete a property of an object.

## High Hopes For The Community

Generally speaking, while surveying many questions on the Stack Overflow exchange, it is clear that this community is filled with vibrant, curious, and helpful users. Over the long term, this community will undoubtedly continue to grow and provide support to new and upcoming software engineers as well as experienced ones, especially as the base of answered questions continues to grow and be reused by more and more users.

Due probably to the very nature and complexity of the subject, the majority of people searching for answers here have already put in at least a little bit of effort to find the answer on their own, which is encouraging for other users and the future of the platform. This does not mean that this community is completely rid of stupid questions, it just means that their is no obligation to answer those questions and by ‘natural selection’, if you will, only those questions paid for with enough personal effort will be given equally effortful answers.
