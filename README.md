# FORMAT PENULISAN

    title: `<p class="chapterTitle">INTRODUCTION TO JAVASCRIPT</p>`
    body: `
    <p class="chapterBody">Last year, millions of learners from our community started with JavaScript. Why? JavaScript is primarily known as the language of most modern web browsers, and its early quirks gave it a bit of a bad reputation. However, the language has continued to evolve and improve. JavaScript is a powerful, flexible, and fast programming language now being used for increasingly complex web development and beyond!</p>
    <p class="chapterBody">Since JavaScript remains at the core of web development, it’s often the first language learned by self-taught coders eager to learn and build. We’re excited for what you’ll be able to create with the JavaScript foundation you gain here. JavaScript powers the dynamic behavior on most websites, including this one.</p>
    `
    SubjectId: 1

<br>

# CLASS LIST

## chapterTitle
    Judul dari setiap chapter => <p class="chapterTitle">

## chapterBody
    Isi untuk setiap chapter => <p class="chapterBody">

## chapterUnorderedList
    Unordered list => <ul class="chapterUnorderedList">

## chapterOrderedList
    Ordered list => <ol class="chapterOrderedList">

## chapterList
    List di dalem ul maupun ol => <li class="chapterList">

## chapterCode
    Class untuk simple code tag => <code class="chapterCode">

## chapterCodeBlock
    Class untuk code tag rumit (js script misal)

## chapterCodeContainer
    Container untuk code di dalam CodeBlock


# CODE STYLING
```javascript
let messsage = 'This is a message'
if (true) {
    console.log(message); 
} 
// This is comment
```
## code-def
    message

## code-operator
    =

## code-keyword
    let, if

## code-atom
    true

## code-variable
    console

## code-property
    log

## code-string
    'This is a message'

## code-comment
    // This is comment