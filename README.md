<h1 align="center">
  QWERTY Learner
</h1>
<p align="center">
  Design for people want to memorize words and practice typings.
</p>

## ✨ Design Goals

QWERTY Learner is designed for people who type English in their daily work and English is not their mother tongue. It is common for them to type faster in their native language than in English. This is mainly because they have built a strong [muscle memory][mm] in their years of experience of typing in native languages. Their muscle memory of English words and phrases is relatively weak. Therefore, people tend to “forget the words” when typing in English.

In order to consolidate English typing skills, you have to keep memorizing words. QWERTY Learner combines vocabulary memorization with typing practice, so you can consolidate muscle memory while reciting words.

To avoid forming incorrect muscle memory, the software requires people to re-enter the entire word if they made any mistakes. This ensures that people form a correct muscle memory.

QWERTY Learner is very useful for people who are going to take computer-based English tests , for example, TOEFL, GRE, and so on.

QWERTY Learner is also helpful for developers. It has built-in dictionaries of words and phrases which are common in code and documentations. We believe these dictionaries will improve developers’ typing speed. Besides, It also has built-in API dictionaries of many languages, which helps developers quickly familiarize with common APIs. More and more APIs are coming soon.

## 🛠 Features

### Built-in Dictionaries

QWERTY Learner has many built-in dictionaries (word banks) for different purposes (examination, learning, and grading). Besides, it also provides dictionaries for developers learning APIs and common words and phrases used by programming languages and libraries.

Our goal is to be the best solution for word memorization and typing practice. Therefore, contribution of more dictionaries is welcome.

### IPA and Pronunciation

While typing, QWERTY Learner shows the [IPA][ipa] of current word and reads the word. This helps people memorize pronunciation and spelling together.

### Dictation Mode

After people finish a chapter, QWERTY Learner will ask if people are willing to dictate the chapter. This is intended to consolidate words learned in the chapter.

### Speed and Accuracy

QWERTY Learner counts how many strokes people have typed and shows the speed and accuracy in real time. By doing so, people can acknowledge how much they have improved.

## 📕 Dictionaries

### 🔠 English Dictionaries

- [CET][cet]-4
- [CET][cet]-6
- [GMAT](https://en.wikipedia.org/wiki/Graduate_Management_Admission_Test)
- [GRE](https://en.wikipedia.org/wiki/Graduate_Record_Examinations)
- [IELTS](https://en.wikipedia.org/wiki/International_English_Language_Testing_System)
- [SAT](https://en.wikipedia.org/wiki/SAT)
- [TOEFL](https://en.wikipedia.org/wiki/Test_of_English_as_a_Foreign_Language)
- [TEM][cet]-4
- [TEM][cet]-8
- Common words and phrases for developers
- [Chinese National College Entrance Examination](https://en.wikipedia.org/wiki/Gaokao)

There are also many other unlisted vocabularies. If you need more vocabularies, please come up with new issues according to our contribution guide.

[cet]: https://en.wikipedia.org/wiki/College_English_Test

### 📗 API Thesaurus

- JavaScript API. Thanks to [@sdu-gyf](https://github.com/sdu-gyf).
- Node.js API. Thanks to [@chrysalis1215](https://github.com/chrysalis1215).
- Java API. Thanks to [@darkSheep](https://github.com/SFAfreshman).
- Linux Command. Thanks to [@Riddler](https://github.com/vhxubo).
- C# List API. Thanks to [@nidbCN](https://github.com/nidbCN).

## 🎁 Acknowledgements

### Inspiration

This project is inspired by many other excellent works.

- **[Keybr](https://www.keybr.com/)** This is a very popular typing practice website that well-known for its algorithm-generated “pseudo-English” corpus. It geneartes based on people’s accuracy and speed of typing each letter to help the user focus on individual letters that are slow to be typed. Most importantly, it generates a detailed statistics from typing practice history data.

  Keybr is the original inspiration of this project. Because Keybr aims more at native English speakers. When I was practicing typing with Keybr, I felt that although the generated pseudo-English could practice letters and syllables, it did not improve entire words for non-native users. Hence I decide to make this project.

- **[Typing Academy](https://www.typing.academy)** This is an excellent typing practice website. Its user interface layout and the display of speed and accuracy greatly influenced this project

- **[react-code-game](https://github.com/webzhd/react-code-game)** A very cool open source project implemented in TypeScript. You can practice typing while memorizing JavaScript’s built-in API. The idea of adding dictionaries of code snippets came from this project.

### Open Source Projects

- **[React](https://github.com/facebook/react) and [create-react-app](https://github.com/facebook/create-react-app).** Their exhaustive documentation is very beginner-friendly, and the React documentation is by far the best I've read in my self-learning process, solving almost most of the problems in use. Many thanks to React for their contribution to the open source world, building a great foundation for us to build really great software for beginners.
- **[Tailwind CSS](https://tailwindcss.com/).** Tailwind CSS mitigates my fear of writing complicated stylesheets. Without Tailwind CSS, this project would unquestionably delayed longer. It helps CSS beginners (like me) getting familiar with front-end development and design user interface in a progressive manner.

### Dictionary Sources

English dictionaries are from [kajweb][kajweb]. The project collects a lot of common dictionaries. This is the project that let me see the hope of realizing this project.

Phonetic data comes from open API of [Youdao Dictionary][yd]. I’m very grateful for Youdao's contribution so that small projects like ours can make use of professional pronunciation resources. Besides, thanks to Youdao team and Kao Shen team for their important contribution to Chinese education and communications between China and foreign countries and regions.

JavaScript API is from [react-code-game][rcg]. I am really thankful to the project for crawling and compiling the JavaScript API.

### Project Icon

Thanks to [libregd][libregd] for designing the icon, contributing several lovely icon designs to the project, as well as providing design advice, future planning and many other support to the project.

[libregd]: https://github.com/libregd
