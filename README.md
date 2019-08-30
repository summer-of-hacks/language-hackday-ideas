# Language Hackday Ideas (2019)

The following is a list of ideas for possible hackery. These are mostly for those
who already have experience with both programming and natural language processing.

(some possible projects if you don't have experience with NLP are [simple-nlp-stats](https://github.com/lpmi-13/simple-NLP-stats) and [simple-nlp-pos](https://github.com/lpmi-13/simple-NLP-pos)).

### Examples of text input/output we could do stuff with:
- tweets (has API)
- reddit posts/comments (has API)
- html pages (eg, wikipedia) (no API, have to scrape)
- documents on the local file system
- SMS (eg, sent through Twilio)
- chats (eg, sent through Telegram)

### Examples of audio input/output we could do stuff with:
- audio from the internet (eg, soundcloud, youtube, TED talks)
- audio recorded on a mobile device or laptop
- hardware with audio enabled (eg, Amazon echo)

### Examples of problems/topics we could work on (from easier-ish to slightly more difficult-ish):
- Sentiment analysis (analysing how positive or negative a certain text is)
- Text-to-speech
- Part of Speech tagging (eg, singular noun, auxiliary verb, possessive pronoun, preposition)
- Predicting sentence stress based on a given sentence (BONUS: evaluating the similarity to somebody reading the same sentence)
- Generating simple sentences/poetry/song lyrics (BONUS: generating a backing audio track to be played while the computer reads the generated text...think "creating both the lyrics and melody of a rap song")
- Scoring responses to happy/sad stories ("I just told you my cat died...why did you reply, 'AWESOME!!!1'...???") based on sentiment analysis
- Deciding whether a song is more positive or negative (sentiment analysis, BONUS: base this on the prosodic features of the song instead of the lyrics)
- Create a visualisation based on the sentiment analysis of a user's tweets/comments/voice recordings (BONUS: transform this into a non-linguistic medium like colours)
- Summarising text samples (BONUS: scoring summaries)
- Artificially stretch/compress the octave range of a recording (eg, regular speech sounds very excited, or vice-versa)
- Generating/scoring paraphrases (eg, "Would this be an acceptable paraphrase of cited evidence in a research paper?")
- Generate lists of words with spoken forms that could cause confusion between two language (eg, a word that means 'to like' in Indonesian, though is one of the most vulgar expletives in Russian)
- Create a swipable timeline for a given verb, then change the form based on the touch actions from the user (eg, swipes left - change to past tense form, swipes right - change to -future tense form, draws small circles around the centre of the line - change to present progressive)
- Have users interact with a mobile device API (acceleromotors and gyroscopes) to appropriately simulate different verb meanings/functions (ie, "stop turning" = turning the device for a while and then stop, VS. "stop to turn" = shaking for a while, then stopping and turning the device)
- Generate simple texts based on templates, introduce minor errors and time the users in how quickly they can fix them (eg, generate a simple business email with one spelling error and one improper collocation, like "mourn the profits")
- Generate a list of most likely collocations (words that appear after/before a given word) for a word (BONUS: create a corpus for this and visualise differences in collocation probabilities by subject area/register)
- Predicting word stress in made up words (eg, flexomagication, brabrahsticklensboratory, yuzzis)
- Create word vectors (BONUS: create a visualisation for this)
- Create document vectors (BONUS: create a visualisation for this)
- Use Term Frequency / Inverse Document Frequency to decide what subject a particular text should be categorised as
- Pass the Turing Test
