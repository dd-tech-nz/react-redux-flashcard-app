# React & Redux Flashcard App

A work-in-progress app built with React & Redux, with a toolset of Babel, Gulp, Browserify and Sass. Users can view flashcard questions, click to reveal answers, and paginate forward through cards (still working on backward pagination!).

[www.ahoef.co/photo-flashcards](http://ahoef.co/photo-flashcards/)

This is an alternate implemenation of [this vanilla JS flashcard app](https://github.com/ahoef/es2015-flashcard-app)


### Development 

Clone or fork this repo, run `npm install` from the directory, then run `gulp`, and you're all set! A local server isn't required. 

I chose to set up my flashcard content around photography, but you could easily change the questions and answers to whatever you'd like to study. Here's the schema for a card:

```javascript
{
	question: "How does aperture affect shutter speed?",
	answer: "Using a low f/stop means more light is entering the lens and therefore the shutter doesn't need to stay open as long to make a correct exposure which translates into a faster shutter speed.",
	source: "Nikon - Understanding Maximum Aperture",
	sourceUrl: "http://www.nikonusa.com/en/learn-and-explore/article/g3cu6o1r/understanding-maximum-aperture.html"
}
```


