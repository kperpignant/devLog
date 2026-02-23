This week we watched a pretty long video on LLMs (https://www.youtube.com/watch?v=zjkBMFhNj_g)
It provided a beginner friendly intro to LLMs, though still a bit confusing. Talks about the technology behind systems
like CHATGPT, training, and possible future advancements. How parameters are relatively small compared to what they generate, like hundreds of billions of Parameters dispersed throughout the
neural network..
And Possible ways to jailbreak/find exploits, or getting the LLM to do things it's not supposed to. Interesting stuff.

Moving on. Continuing working on neetcodes and boy is it not getting any easier. I still find abstracting to be difficult.
Except maybe the Valid Palindrome one. Although that's probably because I've worked on palindrome like problems a number of times.

Though this one was a bit more complicated:

isPalindrome(s) 
{
*    let flipped = s.toLowerCase().replace(/ /g, "").replace(/[^a-zA-Z0-9\s]/g, '').split('').reverse('').join('')
*    let cleaned = s.toLowerCase().replace(/[^a-z0-9]/g, '')
*    return cleaned === flipped ? true : false
}

Had to use regex this time around, I could probably remove one of those replace() too.
In the end learning things like this really comes down to repetition, so I've just got to keep grinding.

El Psy Congroo