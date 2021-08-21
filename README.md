<h1 align="center">
<br>
  <a href="https://github.com/leonardomso/33"><img src="https://i.imgur.com/dsHmk6H.jpg" alt="৩৩ টি কনসেপ্ট যা প্রত্যেক জাভাস্ক্রিপ্ট ডেভেলপারের জানা উচিত" width=200"></a>
  <br>
    <br>
  ৩৩ টি কনসেপ্ট যা প্রত্যেক জাভাস্ক্রিপ্ট ডেভেলপারের জানা উচিত
  <br><br>
</h1>

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![Follow me](https://img.shields.io/twitter/follow/leonardomso.svg?style=for-the-badge)](https://twitter.com/leonardomso)

## ভূমিকা

ডেভেলপারগণ যাতে জাভাস্ক্রিপ্টের ধারণাগুলো ভালোভাবে রপ্ত করতে পারে সেই উদ্দেশ্যে এই রিপোজিটরিটি তৈরি করা হয়েছে। এটি যে একেবারেই খুব প্রয়োজন তা না, তবে ভবিষ্যতে এই সংক্রান্ত পড়াশোনার কাজে গাইড হিসেবে কাজ করবে। এটি মূলত [স্টিফেন কার্টিজ](https://twitter.com/stephenthecurt) -এর একটি আর্টিকেলের উপর ভিত্তি করে বানানো। আপনি এটি [এখানে](https://medium.com/@stephenthecurt/33-fundamentals-every-javascript-developer-should-know-13dd720a90d1) গিয়ে পড়তে পারেন।

**🚀 এটি গিটহাব কর্তৃক [২০১৮ সালে নির্বাচিত শীর্ষ প্রজেক্টগুলোর মধ্যে একটি!](https://blog.github.com/2018-12-13-new-open-source-projects/)**

## কমিউনিটি

আপনি বিনা দ্বিধায় আপনার কোনো রিক্যাপ কিংবা রিভিউ একটি পুল রিকোয়েস্টের লিঙ্কের মাধ্যমে সাবমিট করতে পারেন।

এই রিপোজিটরির সকল অনুবাদ নিম্ন লিখিত তালিকায় যোগ হবেঃ

- [আলবেনিয়ান](https://github.com/eldrinf/33-js-concepts-albanian.git) — অ্যালড্রিন অ্যারেক্বী
- [আরবী](https://github.com/amrsekilly/33-js-concepts) — আমর ইলসেকিলি
- [চীনা](https://github.com/stephentian/33-js-concepts) — রি তিয়ান
- [ব্রাজিলীয় পর্তুগিজ](https://github.com/tiagoboeing/33-js-concepts) — তিয়াগো বোয়েইং
- [কোরিয়ান](https://github.com/yjs03057/33-js-concepts.git) — সুইন লি
- [স্প্যানিশ](https://github.com/adonismendozaperez/33-js-conceptos) — আদোনিস মেন্দোযা
- [তুর্কী](https://github.com/ilker0/33-js-concepts) — আইকার দামির
- [রুশ](https://github.com/gumennii/33-js-concepts) — মিহাইল গামেনি
- [ভিয়েতনামিজ](https://github.com/nguyentranchung/33-js-concepts) — য়ুয়েন ত্রান চুং
- [পোলিশ](https://github.com/lip3k/33-js-concepts) — দাভিদ লিপিনস্কি
- [পারসিক](https://github.com/majidalavizadeh/33-js-concepts) — মজিদ আলাভিযাদেহ
- [ইন্দোনেশিয়ান](https://github.com/rijdz/33-js-concepts) — রিজযুয়ান সাম্পোয়েরনা
- [ফরাসি](https://github.com/robinmetral/33-concepts-js) — রবিন মিত্রাল
- [হিন্দি](https://github.com/vikaschauhan/33-js-concepts) — বিকাশ চৌহান
- [গ্রীক](https://github.com/DimitrisZx/33-js-concepts) — দিমিত্রিস যারাখানিস
- [জাপানি](https://github.com/oimo23/33-js-concepts) — oimo23
- [জার্মান](https://github.com/burhannn/33-js-concepts) — বুরহান
- [ইউক্রেনিয়ান](https://github.com/AndrewSavetchuk/33-js-concepts-ukrainian-translation) — অ্যান্ড্রু সাভেতচুক
- [সিংহল](https://github.com/ududsha/33-js-concepts) — উদয় শামেন্দ্র
- [ইতালিয়ান](https://github.com/Donearm/33-js-concepts) — জিয়ানলুকা ফিয়োরে

---

## সুচীপত্র

1. **[Call Stack](#1-call-stack)**
2. **[Primitive Types](#2-primitive-types)**
3. **[Value Types and Reference Types](#3-value-types-and-reference-types)**
4. **[Implicit, Explicit, Nominal, Structuring and Duck Typing](#4-implicit-explicit-nominal-structuring-and-duck-typing)**
5. **[== vs === vs typeof](#5--vs--vs-typeof)**
6. **[Function Scope, Block Scope and Lexical Scope](#6-function-scope-block-scope-and-lexical-scope)**
7. **[Expression vs Statement](#7-expression-vs-statement)**
8. **[IIFE, Modules and Namespaces](#8-iife-modules-and-namespaces)**
9. **[Message Queue and Event Loop](#9-message-queue-and-event-loop)**
10. **[setTimeout, setInterval and requestAnimationFrame](#10-settimeout-setinterval-and-requestanimationframe)**
11. **[JavaScript Engines](#11-javascript-engines)**
12. **[Bitwise Operators, Type Arrays and Array Buffers](#12-bitwise-operators-type-arrays-and-array-buffers)**
13. **[DOM and Layout Trees](#13-dom-and-layout-trees)**
14. **[Factories and Classes](#14-factories-and-classes)**
15. **[this, call, apply and bind](#15-this-call-apply-and-bind)**
16. **[new, Constructor, instanceof and Instances](#16-new-constructor-instanceof-and-instances)**
17. **[Prototype Inheritance and Prototype Chain](#17-prototype-inheritance-and-prototype-chain)**
18. **[Object.create and Object.assign](#18-objectcreate-and-objectassign)**
19. **[map, reduce, filter](#19-map-reduce-filter)**
20. **[Pure Functions, Side Effects and State Mutation](#20-pure-functions-side-effects-and-state-mutation)**
21. **[Closures](#21-closures)**
22. **[High Order Functions](#22-high-order-functions)**
23. **[Recursion](#23-recursion)**
24. **[Collections and Generators](#24-collections-and-generators)**
25. **[Promises](#25-promises)**
26. **[async/await](#26-asyncawait)**
27. **[Data Structures](#27-data-structures)**
28. **[Expensive Operation and Big O Notation](#28-expensive-operation-and-big-o-notation)**
29. **[Algorithms](#29-algorithms)**
30. **[Inheritance, Polymorphism and Code Reuse](#30-inheritance-polymorphism-and-code-reuse)**
31. **[Design Patterns](#31-design-patterns)**
32. **[Partial Applications, Currying, Compose and Pipe](#32-partial-applications-currying-compose-and-pipe)**
33. **[Clean Code](#33-clean-code)**

---

## 1. Call Stack

### রেফারেন্স

- 📜 [কল স্ট্যাক (Call Stack) - এমডিএন](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack)

### আর্টিকেলসমূহ

- 📜 [সহজভাবে জাভাস্ক্রিপ্টের কল স্ট্যাক (Call Stack) এবং ইভেন্ট লুপ (Event Loop) - গৌরভ পান্ডিয়া](https://medium.com/@gaurav.pandvia/understanding-javascript-function-executions-tasks-event-loop-call-stack-more-part-1-5683dea1f5ec)
- 📜 [সহজভাবে জাভাস্ক্রিপ্টের কল স্ট্যাক (Call Stack) - চার্লস ফ্রিবর্ন](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)
- 📜 [জাভাস্ক্রিপ্টঃ এক্সেকিউশন কনটেক্সট (Execution Context) কী? কল স্ট্যাক (Call Stack) কাকে বলে? - ভ্যালেন্টিনো জাগলিয়ার্দি](https://web.archive.org/web/20180701233338/https://www.valentinog.com/blog/js-execution-context-call-stack/)
- 📜 [জাভাস্ক্রিপ্টের ইভেন্ট লুপ (Event Loop) এবং কল স্ট্যাক (Call Stack) কী? - জেস টেলফোর্ড](https://gist.github.com/jesstelford/9a35d20a2aa044df8bf241e00d7bc2d0)
- 📜 [সহজভাবে জাভাস্ক্রিপ্টের এক্সেকিউশন কন্টেক্সট (Execution Context) এবং এক্সেকিউশন স্ট্যাক (Execution Stack) - সুখজিন্দর অরোরা](https://blog.bitsrc.io/understanding-execution-context-and-execution-stack-in-javascript-1c9ea8642dd0)
- 📜 [জাভাস্ক্রিপ্ট কীভাবে কাজ করেঃ ইঞ্জিন, রানটাইম এবং কল স্ট্যাকের একটি ওভারভিউ - আলেক্সান্ডার যলাতকভ](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)
- 📜 [জাভাস্ক্রিপ্টের এক্সেকিউশন কন্টেক্সটস (Execution Constext), হোয়িস্টিং (Hoisting), স্কোপস (Scopes) এবং ক্লজিউরস (Closures) এর আল্টিমেট গাইড - টাইলার ম্যাকগিনিস](https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/)
- 📜 [ভেতরে জাভাস্ক্রিপ্ট কীভাবে কাজ করেঃ জাভাস্ক্রিপ্টের ইঞ্জিন (Engine), হিপ (Heap) এবং, কল স্ট্যাক (Call Stack) এর একটি ওভারভিউ - বিপিন রাজভার](https://dev.to/bipinrajbhar/how-javascript-works-under-the-hood-an-overview-of-javascript-engine-heap-and-call-stack-1j5o)

### ভিডিওগুলো

- 🎥 [জাভাস্ক্রিপ্টঃ কল স্ট্যাকের (Call Stack) বিবৃতি - কোডিং ব্লকস ইন্ডিয়া](https://www.youtube.com/watch?v=w6QGEiQceOM)
- 🎥 [৯ মিনিটে জাভাস্ক্রিপ্ট কল স্ট্যাক (Call Stack) এর ব্যাখ্যা - কল্ট স্টিলি](https://www.youtube.com/watch?v=W8AeMrVtFLY)
- 🎥 [জাভাস্ক্রিপ্টের এক্সেকিউশন স্ট্যাক (Execution Stack) - কোড অ্যাকাডেমি](https://www.youtube.com/watch?v=jT0USJeNFEA)
- 🎥 [কল স্ট্যাক (Call Stack) কাকে বলে? - এরিক ট্রব](https://www.youtube.com/watch?v=w7QWQlkLY_s)
- 🎥 [কল স্ট্যাক (The Call Stack) - কেভিন ড্রুম](https://www.youtube.com/watch?v=Q2sFmqvpBe0)
- 🎥 [সহজভাবে জাভাস্ক্রিপ্টের এক্সেকিউশন (Execution) - কোডস্মিথ](https://www.youtube.com/watch?v=Z6a1cLyq7Ac&list=PLWrQZnG8l0E4kd1T_nyuVoxQUaYEWFgcD)
- 🎥 [জাভাস্ক্রিপ্টের এক্সেকিউশন কন্টেক্সটস (Execution Constext), হোয়িস্টিং (Hoisting), স্কোপস (Scopes) এবং ক্লজিউরস (Closures) এর আল্টিমেট গাইড - টাইলার ম্যাকগিনিস](https://www.youtube.com/watch?v=Nt-qa_LlUH0)
- 🎥 [ইভেন্ট লুপ (Event Loop) জিনিসটা আসলে কী!? - ফিলিপ রবার্টস](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
- 🎥 [জাভাস্ক্রিপ্টের কল স্ট্যাক (Call Stack) - দ্য কিচেন অফ কোড](https://www.youtube.com/watch?v=ygA5U7Wgsg8)
- 🎥 [কীভাবে জাভাস্ক্রিপ্টের কোড কাজ করে? ❤️& কল স্ট্যাক (Call Stack)](https://www.youtube.com/watch?v=iLWTnMzWtj4&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP)

**[⬆ উপরে ফিরে যান](table-of-contents)**

---

## 2. Primitive Types

### রেফারেন্স

- 📜 [জাভাস্ক্রিপ্টের ড্যাটা টাইপস এবং ড্যাটা স্ট্রাকচার - এমডিএন](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Primitive_values)

### আর্টিকেলসমূহ

- 📜 [কীভাবে সংখ্যাগুলো জাভাস্ক্রিপ্টের এনকোডেড হয়ে থাকে - ড. অ্যাক্সেল রশ্চম্যায়ার](http://2ality.com/2012/04/number-encoding.html)
- 📜 [জাভাস্ক্রিপ্টের নাম্বার টাইপস প্রসঙ্গে যা জানা উচিত - ম্যাক্স উইজার্ড কে](https://medium.com/dailyjs/javascripts-number-type-8d59199db1b6)
- 📜 [দশমিক সংখ্যা প্রসঙ্কে প্রত্যেক জাভাস্ক্রিপ্ট ডেভেলপারের যা জানা উচিত - Chewxy](https://blog.chewxy.com/2014/02/24/what-every-javascript-developer-should-know-about-floating-point-numbers/)
- 📜 [জাভাস্ক্রিপ্টের প্রিমিটিভস টাইপসের লুকোনো তথ্য - অ্যাগনাস ক্রল](https://javascriptweblog.wordpress.com/2010/09/27/the-secret-life-of-javascript-primitives/)
- 📜 [প্রিমিটিভস টাইপ - ফ্লো](https://flow.org/en/docs/types/primitives/)
- 📜 [জাভাস্ক্রিপ্টের সকল কিছুই অবজেক্ট (নয়) - ড্যানিয়েল লি](https://dev.to/d4nyll/not-everything-in-javascript-is-an-object)
- 📜 [জাভাস্ক্রিপ্টের ড্যাটা টাইপস এবং ড্যাটা স্ট্রাকচার - এমডিএন](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Primitive_values)
- 📜 [জাভাস্ক্রিপ্টের অবজেক্ট প্রসঙ্গে বিশদ আলোচনা — আরফাত সালমান](https://blog.bitsrc.io/diving-deeper-in-javascripts-objects-318b1e13dc12)
- 📜 [জাভাস্ক্রিপ্টের Object.freeze() বনাম Const এর মধ্যে পার্থক্যসমূহ - বোলাজি আয়োদেজি](https://medium.com/@bolajiayodeji/the-differences-between-object-freeze-vs-const-in-javascript-4eacea534d7c)

### ভিডিওগুলো

- 🎥 [জাভাস্ক্রিপ্টের রেফারেন্স বনাম প্রিমিটিভ টাইপস - অ্যাকাডেমাইন্ড](https://www.youtube.com/watch?v=9ooYYRLdg_g)
- 🎥 [জাভাস্ক্রিপ্টের প্রিমিটিভ টাইপ - সাইমন সেজ আইটি](https://www.youtube.com/watch?v=HsbWQsSCE5Y)
- 🎥 [জাভাস্ক্রিপ্টের ভ্যালু টাইপস এবং রেফারেন্স টাইপস - প্রোগ্রামিং উইথ মশ](https://www.youtube.com/watch?v=e-_mDyqm2oU)
- 🎥 [জাভাস্ক্রিপ্টের প্রিমিটিভ ড্যাটা টাইপস - Avelx](https://www.youtube.com/watch?v=qw3j0A3DIzQ)
- 🎥 [জাভাস্ক্রিপ্টের সংখ্যা সমন্ধ্যে যা কখনই জানতে চাওয়া হয় নি - বারটেক যুপকা](https://www.youtube.com/watch?v=MqHDDtVYJRI)
- 🎥 [জাভাস্ক্রিপ্টে ভ্যারিয়েবল কাকে বলে? - জেএস ফর এভরিওয়ান](https://www.youtube.com/watch?v=B4Bbmei_thw)
- 🎥 [জাভাস্ক্রিপ্টের প্রিমিটিভ ড্যাটা টাইপস - দ্য কিচেন কোড](https://www.youtube.com/watch?v=cC65D2q5f8I)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 3. Value Types and Reference Types

### আর্টিকেলসমূহ

- 📜 [জাভাস্ক্রিপ্টের ভাল্যু (Value) বনাম রেফারেন্সের (Reference) ব্যাখ্যা - অর্ণব আগারওয়াল](https://codeburst.io/explaining-value-vs-reference-in-javascript-647a975e12a0)
- 📜 [জাভাস্ক্রিপ্টের প্রিমিটিভ (Primitive) টাইপস এবং রেফারেন্স (Reference) টাইপস - ব্র্যান ভন ডার মিয়ার](https://gist.github.com/branneman/7fb06d8a74d7e6d4cbcf75c50fec599c)
- 📜 [জাভাস্ক্রিপ্টের ভ্যালু (Value) টাইপস, রেফারেন্স (Reference) টাইপস এবং স্কোপ (Scope) - বেন অ্যাস্টন](https://medium.com/@benastontweet/lesson-1b-javascript-fundamentals-380f601ba851)
- 📜 [সমূলে ফেরতঃ জাভাস্ক্রিপ্টের ভ্যালু (Value) বনাম রেফারেন্স (Reference) - মিরো কযকা](https://medium.com/dailyjs/back-to-roots-javascript-value-vs-reference-8fb69d587a18)
- 📜 [জাভাস্ক্রিপ্টের "By Value" এবং "By Reference" সম্পর্কে আরোও একবার উপলব্ধি - লিনা ফওরে](https://hackernoon.com/grasp-by-value-and-by-reference-in-javascript-7ed75efa1293)
- 📜 [জাভাস্ক্রিপ্টের রেফারেন্স (Reference) এবং কপি ভ্যারিয়েবলস (Copy Variables) - ভিটর কাপ্রেতয](https://hackernoon.com/javascript-reference-and-copy-variables-b0103074fdf0)
- 📜 [জাভাস্ক্রিপ্টের প্রিমিটিভ (Primitive) বনাম রেফারেন্স (Reference) ভ্যাল্যুস](http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/)
- 📜 [জাভাস্ক্রিপ্টের বাই রেফারেন্স (By Reference) বনাম বাই ভ্যাল্যু (By Value) - nrabinowitz](https://stackoverflow.com/questions/6605640/javascript-by-reference-vs-by-value)
- 📜 [জাভাস্ক্রিপ্ট ইন্টারভিউর প্রস্তুতিঃ প্রিমিটিভ (Primitive) বনাম রেফারেন্স (Reference) টাইপস - মাইক ক্রোনিন](https://dev.to/mostlyfocusedmike/javascript-interview-prep-primitive-vs-reference-types-3o4f)

### ভিডিওগুলো

- 🎥 [জাভাস্ক্রিপ্টের পাস বাই ভ্যালু (Pass by Value) বনাম পাস বাই রেফারেন্স (Pass by Reference) - techsith](https://www.youtube.com/watch?v=E-dAnFdq8k8)
- 🎥 [জাভাস্ক্রিপ্টের ভ্যালু (Value) বনাম রেফারেন্স (Reference) টাইপস - প্রোগ্রামিং উইথ মশ](https://www.youtube.com/watch?v=fD0t_DKREbE)
- 🎥 [জাভাস্ক্রিপ্টের ভাল্যু (Values) এবং রেফারেন্স (Reference) - দ্য কিচেন অফ কোড](https://www.youtube.com/watch?v=AvkyOrWkuQc)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 4. Implicit, Explicit, Nominal, Structuring and Duck Typing

### আর্টিকেলসমূহ

- 📜 [জাভাস্ক্রিপ্টের ইমপ্লিসিট কোরশন (Implicit Coercion) সম্পর্কে আপনার যা জানা প্রয়োজন - প্রমিজ টোশি](https://dev.to/promhize/what-you-need-to-know-about-javascripts-implicit-coercion-e23)
- 📜 [জাভাস্ক্রিপ্টের টাইপ কোরশন (Type Coercion) এর ব্যাখ্যা - আলেক্সেই সামোশকিন](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839)
- 📜 [জাভাস্ক্রিপ্টের কোরশন (Coercion) এর বিবৃতি - বেন গ্যারিসন](https://hackernoon.com/javascript-coercion-explained-545c895213d3)
- 📜 [জাভাস্ক্রিপ্টে টাইপ কোরশন (Type Coercion) মূলত কী? - স্ট্যাক ওভারফ্লো](https://stackoverflow.com/questions/19915688/what-exactly-is-type-coercion-in-javascript)
- 📜 [জাভাস্ক্রিপ্টের টাইপ কোরশন (Type Coercion), এবং কেনো সবাই এটিতে ভুল করে বসে।](https://thedevs.network/blog/type-coercion-in-javascript-and-why-everyone-gets-it-wrong)

### ভিডিওগুলো

- 🎥 [== ? === ??? ...#@^% - শিরমাং বিলফেল্ড](https://www.youtube.com/watch?v=qGyqzN0bjhc&t)
- 🎥 [জাভাস্ক্রিপ্টের কোরশন - হিতেশ চৌধুরী](https://www.youtube.com/watch?v=b04Q_vyqEG8)
- 🎥 [জাভাস্ক্রিপ্ট সম্পর্কে প্রশ্নঃ কোরশন (Coercion) কাকে বলে? - স্টিভেন হ্যানকক](https://www.youtube.com/watch?v=z4-8wMSPJyI)
- 🎥 [টাইপিং (Typing) ঃ স্ট্যাটিক (Static) বনাম ডাইনামিক (Dynamic), উইক (Weak) vs স্ট্রং (Strong)](https://www.youtube.com/watch?v=C5fr0LZLMAs)
- 🎥 [জাভাস্ক্রিপ্টের টাইপ সিস্টেম (Type System) - দ্য কিচেন অফ কোড](https://www.youtube.com/watch?v=0ei4nb49GKo)

### বইগুলো

- [ইউ ডোন্ট নো জাভাস্ক্রিপ্ট ইয়েট, প্রথম প্রকাশনঃ টাইপস (Types) এবং গ্রামার (Grammar) - কাইল সিম্পসন](https://github.com/getify/You-Dont-Know-JS/tree/1st-ed)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 5. == vs === vs typeof

### আর্টিকেলসমূহ

- 📜 [জাভাস্ক্রিপ্টের ডাবল ইক্যুয়ালস (Double Equals) বনাম ট্রিপল ইক্যুয়ালস (Triple Equals) - ব্র্যান্ডন মোরেল্লি](https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a)
- 📜 [জাভাস্ক্রিপ্টের ইক্যুয়ালিটি অপারেটর (Equality Operator) এর ক্ষেত্রে === অথবা == কোনটি ব্যবহার করা উচিত? - পান্যু পিতকামাকি](https://bytearcher.com/articles/equality-comparison-operator-javascript/)
- 📜 [জাভাস্ক্রিপ্টের == বনাম === ঃ ডাবল ইক্যুয়ালস (Double Equals) এবং কোরশন (Coercion) - এ.জে মিয়াঘ্যানি](https://www.codementor.io/javascript/tutorial/double-equals-and-coercion-in-javascript)
- 📜 [জাভাস্ক্রিপ্টের কেনো ট্রিপল ইক্যুয়ালস (Triple-Equals) ব্যবহার করা উচিত? - লুই ল্যাযারিস](https://www.impressivewebs.com/why-use-triple-equals-javascipt/)
- 📜 [জাভাস্ক্রিপ্টে == এবং === এর মধ্যে পার্থক্য কী? - ক্রেইগ বাকলার](https://www.oreilly.com/learning/what-is-the-difference-between-and-in-javascript)
- 📜 [জাভাস্ক্রিপ্টের টাইপঅফ (Typeof) অপারেটর কেনো সবসময় অবজেক্ট (Object) রিটার্ন করে? - স্ট্যাক ওভারফ্লো](https://stackoverflow.com/questions/3787901/why-javascripts-typeof-always-return-object)
- 📜 [জাভাস্ক্রিপ্টের টাইপস চেক করা - টবি হো](http://tobyho.com/2011/01/28/checking-types-in-javascript/)
- 📜 [জাভাস্ক্রিপ্টের ড্যাটা টাইপস (Data Types) কীভাবে আরোও ভালো করে চেক করা যায় - Webbjocke](https://webbjocke.com/javascript-check-data-types/)
- 📜 [জাভাস্ক্রিপ্টে ভ্যালুর অনুপস্থিতি চেক করণ - টোমার এইবারব্যাক](https://tomeraberba.ch/html/post/checking-for-the-absence-of-a-value-in-javascript.html)

### ভিডিওগুলো

- 🎥 [জাভাস্ক্রিপ্টঃ টাইপঅফ (Typeof) অপারেটর - জাভা ব্রেইনস](https://www.youtube.com/watch?v=ol_su88I3kw)
- 🎥 [জাভাস্ক্রিপ্টের টাইপঅফ অপারেটর - ডেভডিলাইট](https://www.youtube.com/watch?v=qPYhTPt_SbQ)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 6. Function Scope, Block Scope and Lexical Scope

### বইগুলো

- [ইউ ডোন্ট নো জাভাস্ক্রিপ্ট ইয়েট, দ্বিতীয় প্রকাশনঃ স্কোপ (Scope) এবং ক্লোজারস (Closures) - কাইল সিম্পসন](https://github.com/getify/You-Dont-Know-JS/tree/2nd-ed/scope-closures)

### আর্টিকেলসমূহ

- 📜 [জাভাস্ক্রিপ্টের ফাংশন (Functions) - বেসিক সম্পর্কিত জ্ঞান - ব্র্যান্ডন মোরেলি](https://codeburst.io/javascript-functions-understanding-the-basics-207dbf42ed99)
- 📜 [ফাংশন স্কোপ (Function Scope) এবং ব্লক স্কোপ (Block Scope) এর ভেতরের দ্বন্দ - ম্যারিয়াস হেরিং](http://www.deadcoderising.com/2017-04-11-es6-var-let-and-const-the-battle-between-function-scope-and-block-scope/)
- 📜 [জাভাস্ক্রিপ্ট ব্লক স্কোপের (Block Scope) এর প্রতিদ্বন্দিতা - জশ ক্ল্যান্টন](http://adripofjavascript.com/blog/drips/emulating-block-scope-in-javascript.html)
- 📜 [জাভাস্ক্রিপ্টের ফাংশন স্কোপ (Function Scope) এবং ব্লক স্কোপ (Block Scope) এর মধ্যকার পার্থক্য - জোসেফ কার্দিলো](https://medium.com/@josephcardillo/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe)
- 📜 [জাভাস্ক্রিপ্টের ফাংশন স্কোপ (Function Scope) এবং ব্লক স্কোপ (Block Scope) - সামির বিউনা](https://edgecoders.com/function-scopes-and-block-scopes-in-javascript-25bbd7f293d7)
- 📜 [সহজভাবে জাভাস্ক্রিপ্টের স্কোপ (Scope) এবং কন্টেক্সট (Context) | রায়ান মুর](http://ryanmorr.com/understanding-scope-and-context-in-javascript/)
- 📜 [জাভাস্ক্রিপ্টের স্কোপ (Scope) এবং ক্লোজারস (Closures) - যিল লিউ](https://css-tricks.com/javascript-scope-closures/)
- 📜 [সহজভাবে জাভাস্ক্রিপ্টের স্কোপ (Scope) - উইশাম অ্যাবিরাচড](https://developer.telerik.com/topics/web-development/understanding-scope-in-javascript/)
- 📜 [জাভাস্ক্রিপ্ট বচন - ভ্যারিয়েবলস (Variables) ঃ স্কোপ (Scope), এনভায়রনমেন্ট (Environment) এবং ক্লোজারস (Closures) - ড. অ্যাক্সেল রশম্যায়ার](http://speakingjs.com/es5/ch16.html)
- 📜 [সহজভাবে জাভাস্ক্রিপ্টের স্কোপ (Scope) - হাম্মাদ আহমেদ](https://scotch.io/tutorials/understanding-scope-in-javascript)
- 📜 [কখন একটি ফাংশন ডিক্লারেশন (Function Declaration) বনাম একটি ফাংশন এক্সপ্রেশন (Function Expression) ব্যবহার করতে হয় - অ্যাম্বার উইকি](https://medium.freecodecamp.org/when-to-use-a-function-declarations-vs-a-function-expression-70f15152a0a0)
- 📜 [জাভাস্ক্রিপ্ট ফান্ডামেন্টালের একটি চিট শিটঃ স্কোপ (Scope), কনটেক্সট (Context), এবং "দিস" (this) - আলেক্সান্ডার ফ্রেন](https://dev.to/alexandrafren/a-javascript-fundamentals-cheat-sheet-scope-context-and-this-28ai)

### ভিডিওগুলো

- 🎥 [জাভাস্ক্রিপ্ট কেনো অদ্ভুত... এবং অসাধারণ পার্টঃ ৪ - Learncode.academy ](https://www.youtube.com/watch?v=SBwoFkRjZvE)
- 🎥 [জাভাস্ক্রিপ্টের ভ্যারিয়েবল স্কোপ (Variable Scope) - কিরুপা চিন্নথাম্বি](https://www.youtube.com/watch?v=dhp57T3p760)
- 🎥 [জাভাস্ক্রিপ্টের ব্লক স্কোপ (Block Scope) এবং ফাংশন স্কোপ (Function Scope) — mmtuts](https://www.youtube.com/watch?v=aK_nuUAdr8E)
- 🎥 [লেক্সিক্যাল স্কোপ (Lexical Scope) টা আসলে কী? - NWCalvank](https://www.youtube.com/watch?v=GhNA0r10MmA)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 7. Expression vs Statement

### আর্টিকেলসমূহ

- 📜 [জাভাস্ক্রিপ্টের এক্সপ্রেশন (Expression), স্টেটমেন্ট (Statements) এবং এক্সপ্রেশন স্টেটমেন্ট (Expression Statements) সম্পর্কে যা যা জানা প্রয়োজন — প্রমিজ টোশি](https://dev.to/promhize/javascript-in-depth-all-you-need-to-know-about-expressions-statements-and-expression-statements-5k2)
- 📜 [ফাংশন এক্সপ্রেশন (Function Expression) বনাম ফাংশন ডিক্লারেশন (Function Declaration) - পল উইকিন্স](https://www.sitepoint.com/function-expressions-vs-declarations/)
- 📜 [জাভাস্ক্রিপ্টের ফাংশন - ডিক্লারেশন (Declaration) বনাম এক্সপ্রেশন (Expression) - রবি রোশান](https://medium.com/@raviroshan.talk/javascript-function-declaration-vs-expression-f5873b8c7b38)
- 📜 [ফাংশন ডিক্লারেশন (Function Declarations) বনাম এক্সপ্রেশন (Function Expressions) - মান্দিপ সিং](https://medium.com/@mandeep1012/function-declarations-vs-function-expressions-b43646042052)
- 📜 [ফাংশন ডিক্লারেশন (Function Declarations) বনাম এক্সপ্রেশন (Function Expressions) - অ্যাগনাস ক্রল](https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/)

### ভিডিওগুলো

- 🎥 [এক্সপ্রেশন (Expressions) বনাম স্টেটমেন্ট (Statements) — Hexlet](https://www.youtube.com/watch?v=WVyCrI1cHi8)
- 🎥 [জাভাস্ক্রিপ্ট - এক্সপ্রেশন (Expression) বনাম স্টেটমেন্ট (Statement) — WebTunings](https://www.youtube.com/watch?v=3jDpNGJkupA)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 8. IIFE, Modules and Namespaces

### আর্টিকেলসমূহ

- 📜 [ইমিডিয়েটলি-ইনভোকড ফাংশন এক্সপ্রেশন (Immediately-Invoked Function Expressions) আয়ত্বকরণ - চন্দ্র গুন্দমারাজু](https://medium.com/@vvkchandra/essential-javascript-mastering-immediately-invoked-function-expressions-67791338ddc6)
- 📜 [ইএস সিক্স (ES6) এর মডিউলগুলো কি আইআইএফই (IIFE) কে অচল করে ফেলে?](https://hashnode.com/post/do-es6-modules-make-the-case-of-iifes-obsolete-civ96wet80scqgc538un20es0)
- 📜 [জাভাস্ক্রিপ্টের মডিউলস (modules), মডিউল ফরম্যাটস (Module Formats), মডিউল লোডার (Module Loaders) এবং মডিউল বান্ডলার (Module Bundlers) সম্পর্কিত ১০ মিনিটের একটি পাঠ - ইউর্গেন ভন ডি মোয়েরে](https://www.jvandemo.com/a-10-minute-primer-to-javascript-modules-module-formats-module-loaders-and-module-bundlers/)
- 📜 [মডিউলস - এক্সপ্লোরিং জাভাস্ক্রিপ্ট](http://exploringjs.com/es6/ch_modules.html)
- 📜 [ইএস সিক্স মডিউলসঃ কার্টুন দিয়ে বিশদ ব্যাখ্যা - লিন ক্লার্ক](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/)
- 📜 [সহজভাবে ইএস সিক্স মডিউলস - ক্রেইগ বাকলার](https://www.sitepoint.com/understanding-es6-modules/)
- 📜 [জাভাস্ক্রিপ্টের ইএস সিক্স মডিউলের একটি ওভারভিউ - ব্রেন গ্রাহাম](https://blog.cloud66.com/an-overview-of-es6-modules-in-javascript/)
- 📜 [বিশদভাবে ইএস সিক্স মডিউল - নিকোলাস বিভাকুয়া](https://ponyfoo.com/articles/es6-modules-in-depth)
- 📜 [ইএস সিক্স মডিউল, নোড (Node.js) এবং মাইকেল জ্যাকসন সলিউশন - আলবার্তো গিমিনো](https://medium.com/dailyjs/es6-modules-node-js-and-the-michael-jackson-solution-828dc244b8b)
- 📜 [জাভাস্ক্রিপ্ট মডিউলসঃ একটি বিগিনার গাইড - প্রিথী কাসিরেদ্দি](https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc)
- 📜 [ওয়েবে জাভাস্ক্রিপ্ট মডিউলের ব্যবহার](https://developers.google.com/web/fundamentals/primers/modules)
- 📜 [আইআইএফই (IIFE): ইমিডিয়েটলি ইনভোকড ফাংশন এক্সপ্রেশন (IIFE: Immediately Invoked Function Expressions) — Parwinder](https://dev.to/bhagatparwinder/iife-immediately-invoked-function-expressions-49c5)

### ভিডিওগুলো

- 🎥 [ইমিডিয়েটলি ইনভোকড ফাংশন এক্সপ্রেশন (Immediately Invoked Function Expression) - Beau teaches JavaScript — freeCodeCamp](https://www.youtube.com/watch?v=3cbiZV4H22c)
- 🎥 [সহজভাবে জাভাস্ক্রিপ্টের IIFE](https://www.youtube.com/watch?v=I5EntfMeIIQ)
- 🎥 [জাভাস্ক্রিপ্টের মডিউলসঃ ইএস সিক্স ইম্পোর্ট এবং এক্সপোর্ট - কাইল রবিনসন](https://www.youtube.com/watch?v=_3oSWwapPKQ)
- 🎥 [ইএস সিক্স মডিউলস - রায়ান ক্রিস্টিয়ানি](https://www.youtube.com/watch?v=aQr2bV1BPyE)
- 🎥 [বাস্তবিক ইএস সিক্স মডিউলস - স্যাম থরোগুড](https://www.youtube.com/watch?v=fIP4pjAqCtQ)
- 🎥 [ইএস সিক্স মডিউলস — TempleCoding](https://www.youtube.com/watch?v=5P04OK6KlXA)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 9. Message Queue and Event Loop

### আর্টিকেলসমূহ

- 📜 [জাভাস্ক্রিপ্টের ইভেন্ট লুপের (Event Loop) ব্যাখ্যা - অনুপ রবিন্দ্রন](https://medium.com/front-end-hacking/javascript-event-loop-explained-4cd26af121d4)
- 📜 [জাভাস্ক্রিপ্টের ইভেন্ট লুপ (Event Loop): ব্যাখ্যা - এরিন শোয়েসন-হিলি](https://blog.carbonfive.com/2013/10/27/the-javascript-event-loop-explained/)
- 📜 [সহজভাবে জাভাস্ক্রিপ্টঃ ইভেন্ট লুপ (Event Loop) - আশিস গুপ্ত](https://hackernoon.com/understanding-js-the-event-loop-959beae3ac40)
- 📜 [সহজভাবে জাভাস্ক্রিপ্টের ইভেন্ট লুপ (Event Loop) - আশিস গুপ্ত](https://www.zeolearn.com/magazine/understanding-the-javascript-event-loop)
- 📜 [জাভাস্ক্রিপ্টের ইভেন্ট লুপ (Event Loop) - মঞ্জুলা দুবে](https://code.likeagirl.io/what-the-heck-is-event-loop-1e414fccef49)
- 📜 [জাভাস্ক্রিপ্টের ইভেন্ট লুপ (Event Loop) - ফ্লাভিও কোপস](https://flaviocopes.com/javascript-event-loop/)
- 📜 [জাভাস্ক্রিপ্ট কীভাবে কাজ করেঃ ইভেন্ট লুপ (Event Loop) - আলেক্সান্ডার যলাতকভ](https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to-better-coding-with-2f077c4438b5)
- 📜 [টাস্ক (Task), মাইক্রোটাস্ক (Microtask), কিউ (Queues) এবং শিডিউল (Schedules) - জেইক আরশিবাল্ড](https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/)
- 📜 [পিজ্জা রেস্টুরেন্ট দিয়ে জাভাস্ক্রিপ্ট ইভেন্ট লুপ (Event Loop) এর একটি দৃশ্যমান তুলনা - প্রিয়ানশ জৈন](https://dev.to/presto412/visualising-the-javascript-event-loop-with-a-pizza-restaurant-analogy-47a8)
- 📜 [জাভাস্ক্রিপ্টের সাদৃশ্যকরণ - ইভেন্ট লুপ (Event Loop) - লিডিয়া হ্যালি](https://dev.to/lydiahallie/javascript-visualized-event-loop-3dif)

### ভিডিওগুলো

- 🎥 [ইভেন্ট লুপ (Event Loop) জিনিসটা আসলে কী? । JSConf EU - ফিলিপ রবার্টস](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
- 🎥 [জাভাস্ক্রিপ্টের ইভেন্ট লুপ (Event Loop) — ComScience Simplified](https://www.youtube.com/watch?v=XzXIMZMN9k4)
- 🎥 [আমি ইভেন্ট লুপে (Event Loop) আটকে গিয়েছি — ফিলিপ রবার্টস](https://www.youtube.com/watch?v=6MXRNXXgP_0)
- 🎥 [লুপের ভেতর - জেইক আরশিবাল্ড | JSConf.Asia 2018](https://www.youtube.com/watch?v=cCOL7MC4Pl0)
- 🎥 [Desmitificando el Event Loop (Spanish)](https://www.youtube.com/watch?v=Eqq2Rb7LzYE)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 10. setTimeout, setInterval and requestAnimationFrame

### আর্টিকেলসমূহ

- 📜 [সেট টাইমআউট (setTimeout) এবং সেট ইন্টার্ভাল (setInterval) — JavaScript.Info](https://javascript.info/settimeout-setinterval)
- 📜 [সেট ইন্টার্ভাল (setInterval) কেনো ব্যবহার করা উচিত নয় - আকাঙ্খা শর্মা](https://dev.to/akanksha_9560/why-not-to-use-setinterval--2na9)
- 📜 [সেট টাইমআউট (setTimeout) বনাম সেট ইন্টার্ভাল (setInterval) — Develoger](https://develoger.com/settimeout-vs-setinterval-cff85142555b)
- 📜 [রিকোয়েস্ট অ্যানিমেশন ফ্রেম (requestAnimationFrame) এর ব্যবহার — ক্রিস কোয়েয়ার](https://css-tricks.com/using-requestanimationframe/)
- 📜 [সহজভাবে জাভাস্ক্রিপ্টের রিকোয়েস্ট অ্যানিমেশন ফ্রেম (requestAnimationFrame()) — JavaScript Kit](http://www.javascriptkit.com/javatutors/requestanimationframe.shtml)
- 📜 [জাভাস্ক্রিপ্টের টাইম ইন্টার্ভাল (Time Intervals) এর নিয়ন্ত্রণকরণ - অমিত মার্চেন্ট](https://www.amitmerchant.com/Handling-Time-Intervals-In-Javascript/)

### ভিডিওগুলো

- 🎥 [জাভাস্ক্রিপ্টঃ কীভাবে সেট টাইমআউট (setTimeout) এবং সেট ইন্টার্ভাল (setInterval) কাজ করে - কোডিং ব্লকস ইন্ডিয়া](https://www.youtube.com/watch?v=6bPKyl8WYWI)
- 🎥 [জাভাস্ক্রিপ্টের সেট টাইমআউট (setTimeout) এবং সেট ইন্টার্ভাল (setInterval) — techsith](https://www.youtube.com/watch?v=TbCgGWe8LN8)
- 🎥 [জাভাস্ক্রিপ্টের টাইমারস - স্টিভ গ্রিফিথ](https://www.youtube.com/watch?v=0VVJSvlUgtg)
- 🎥 [জাভাস্ক্রিপ্ট সেট টাইমআউট (setTimeout) এবং সেট ইন্টার্ভাল (setInterval) এর ব্যাখ্যা - থিওডোর অ্যান্ডারসন](https://www.youtube.com/watch?v=mVKfrWCOB60)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 11. JavaScript Engines

### আর্টিকেলসমূহ

- 📜 [জাভাস্ক্রিপ্টের ইঞ্জিন - জেন লুপার](http://www.softwaremag.com/javascript-engines/)
- 📜 [ক্রোম ভি৮ (V8) ইঞ্জিন কীভাবে জাভাস্ক্রিপ্টকে মেশিন কোডে রুপান্তর করে সে সম্পর্কিত সহজ ধারণা - DroidHead](https://medium.freecodecamp.org/understanding-the-core-of-nodejs-the-powerful-chrome-v8-engine-79e7eb8af964)
- 📜 [সহজভাবে ভি৮(V8) এর বাইটকোড - ফান্সিস্কা হিনকালমান](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775)
- 📜 [গুগল ভি৮(V8) জাভাস্ক্রিপ্ট ইঞ্জিনের একটি সংক্ষিপ্ত ইতিহাস - ক্ল্যায়ার স্মিথ](https://www.mediacurrent.com/blog/brief-history-googles-v8-javascript-engine/)
- 📜 [জাভাস্ক্রিপ্টের সারমর্মঃ ইঞ্জিন কীভাবে কাজ করে তা কেনো জানা উচিত - রাইনার হাইনিকাম্প](https://medium.freecodecamp.org/javascript-essentials-why-you-should-know-how-the-engine-works-c2cc0d321553)
- 📜 [প্রাথমিক জাভাস্ক্রিপ্ট ইঞ্জিনঃ শেপস (Shapes) এবং ইনলাইন ক্যাশেস (Inline Caches)](https://mathiasbynens.be/notes/shapes-ics)
- 📜 [প্রাথমিক জাভাস্ক্রিপ্ট ইঞ্জিনঃ প্রটোটাইপস (Prototypes) এর সর্বোচ্চকরণ](https://mathiasbynens.be/notes/prototypes)
- 📜 [কীভাবে ভি৮(V8) ইঞ্জিন অ্যারে অপারেশন কে নিঁখুত করে](https://v8.dev/blog/elements-kinds)

### ভিডিওগুলো

- 🎥 [জাভাস্ক্রিপ্ট ইঞ্জিনঃ ভালো দিকগুলো™ — মাথিয়াস বাইনেন্স এবং বেনেডিক্ট মৌরার](https://www.youtube.com/watch?v=5nmpokoRaZI)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 12. Bitwise Operators, Type Arrays and Array Buffers

### আর্টিকেলসমূহ

- 📜 [জাভাস্ক্রিপ্ট প্রোগ্রামিংঃ বিটওয়াইজ অপারেশন (Bitwise Operations) - আলেক্সান্ডার কোনডভ](https://hackernoon.com/programming-with-js-bitwise-operations-393eb0745dc4)
- 📜 [জাভাস্ক্রিপ্টের বিটওয়াইজ অপারেটর (Bitwise Operator) সমূহের বাস্তব ব্যবহার - ian m](https://codeburst.io/using-javascript-bitwise-operators-in-real-life-f551a731ff5)
- 📜 [জাভাস্ক্রিপ্টের বিটওয়াইজ অপারেটর (Bitwise Operators) সমূহ — w3resource](https://www.w3resource.com/javascript/operators/bitwise-operator.php)
- 📜 [জাভাস্ক্রিপ্টের বিটওয়াইজ অপারেটর (Bitwise operators) সমূহ - জো চ্যা](https://medium.com/bother7-blog/bitwise-operators-in-javascript-65c4c69be0d3)
- 📜 [জাভাস্ক্রিপ্টের বাইনারি কম্পিউটেশন (Binary Computation) এবং বিটওয়াইজ অপারেটর (Bitwise Operator) নিয়ে একটি বিস্তারিত আলোচনা - পল ব্রাউন](https://medium.com/techtrument/a-comprehensive-primer-on-binary-computation-and-bitwise-operators-in-javascript-81acf8341f04)
- 📜 [আমি কীভাবে জাভাস্ক্রিপ্টের বিটওয়াইজ অপারেশন বুঝে পারি?](https://www.quora.com/How-can-I-understand-Bitwise-operation-in-JavaScript)

### ভিডিওগুলো

- 🎥 [জাভাস্ক্রিপ্টের বিটওয়াইজ অপারেটরস — Programming with Mosh](https://www.youtube.com/watch?v=mesu75PTDC8)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 13. DOM and Layout Trees

### বইসমূহ

- 📜 [এলোকুয়েন্ট জাভাস্ক্রিপ্ট, তৃতীয় প্রকাশনঃ অ. ১৪ - দ্য ডকুমেন্ট অবজেক্ট মডেল](https://eloquentjavascript.net/14_dom.html)

### আর্টিকেলসমূহ

- 📜 [জাভাস্ক্রিপ্টে ডম (DOM) কিভাবে বুঝা যায় এবং মডিফাই করা যায় - তানিয়া রাসিয়া](https://www.digitalocean.com/community/tutorials/introduction-to-the-dom)
- 📜 [ডকুমেন্ট অবজেক্ট মডেল কি, এবং তার ব্যবহার কেনো জানা উচিত - লিওনার্দো ম্যালডোনাডো](https://medium.freecodecamp.org/whats-the-document-object-model-and-why-you-should-know-how-to-use-it-1a2d0bc5429d)
- 📜 [জাভাস্ক্রিপ্ট ডম (DOM)-এর উদাহরণসহ টিউটোরিয়াল — Guru99](https://www.guru99.com/how-to-use-dom-and-events-in-javascript.html)
- 📜 [ডম কাকে বলে? - ক্রিস কোয়েয়ার](https://css-tricks.com/dom/)
- 📜 [জাভাস্ক্রিপ্টে ডম (DOM) দিয়ে ট্রাভার্স করা - জেল লিউ](https://zellwk.com/blog/dom-traversals/)
- 📜 [ডম ট্রি (DOM Tree)](https://javascript.info/dom-nodes)
- 📜 [জাভাস্ক্রিপ্টের ডম কে কীভাবে ট্রাভার্স করা যায় - ভজিস্লাভ গ্রুজিচ](https://medium.com/javascript-in-plain-english/how-to-traverse-the-dom-in-javascript-d6555c335b4e)
- 📜 [ট্রি কন্সট্রাকশন রেনডার করা - ইলিয়া গ্রিগোরিক](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-tree-construction)
- 📜 [ডম মূলত কী?](https://bitsofco.de/what-exactly-is-the-dom/)
- 📜 [ডম আয়ত্বকরণে ভ্যানিলা জাভাস্ক্রিপ্টের একটি গাইড - ব্রায়ান প্যাক](https://dev.to/bouhm/a-vanilla-js-guide-on-mastering-the-dom-3l9b)

### ভিডিওগুলো

- 🎥 [জাভাস্ক্রিপ্ট ডম — The Net Ninja](https://www.youtube.com/watch?v=FIORjGvT0kk)
- 🎥 [জাভাস্ক্রিপ্ট ডম ক্র্যাশ কোর্স — Traversy Media](https://www.youtube.com/watch?v=0ik6X4DJKCc)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 14. Factories and Classes

### আর্টিকেলসমূহ

- 📜 [জাভাস্ক্রিপ্টে কীভাবে ক্লাস ব্যবহার করতে হয় - তানিয়া রাসিয়া](https://www.digitalocean.com/community/tutorials/understanding-classes-in-javascript)
- 📜 [জাভাস্ক্রিপ্টের ভেতরকার ক্লাস সমূহ - মাজিদ](https://medium.com/tech-tajawal/javascript-classes-under-the-hood-6b26d2667677)
- 📜 [ইএস সিক্স (ES6)-এর ক্লাসসমূহ - নাথানিয়েল ফস্টার](https://www.javascriptjanuary.com/blog/es6-classes)
- 📜 [ইএস সিক্স দিয়ে জাভাস্ক্রিপ্ট, পার্ট. ২ঃ ক্লাস নিয়ে বিশদ আলোচনা - প্যালেক সেনস্ট্যাকে](https://scotch.io/tutorials/better-javascript-with-es6-pt-ii-a-deep-dive-into-classes)
- 📜 [প্লেইন জাভাস্ক্রিপ্ট দিয়ে সহজভাবে ফ্যাক্টরি ডিজাইন প্যাটার্ন বোঝা - আদিত্য আগারওয়াল](https://medium.com/front-end-hacking/understand-the-factory-design-pattern-in-plain-javascript-20b348c832bd)
- 📜 [জাভাস্ক্রিপ্টের ফ্যাক্টরি ফাংশন - জশ মিলার](https://atendesigngroup.com/blog/factory-functions-javascript)
- 📜 [জাভাস্ক্রিপ্ট ইএস সিক্সের ফ্যাক্টরি প্যাটার্ন - SnstsDev](https://medium.com/@SntsDev/the-factory-pattern-in-js-es6-78f0afad17e9)
- 📜 [ক্লাস বনাম ফ্যাক্টরি ফাংশনঃ একটি সম্মুখ বিশ্লেষণ - ক্রিস্টি শালচেশু](https://medium.freecodecamp.org/class-vs-factory-function-exploring-the-way-forward-73258b6a8d15)
- 📜 [ইএসসিক্স এর ক্লাসগুলো কীভাবে কাজ করে এবং আপনি কীভাবে নিজে এমন একটি ক্লাস বানাবেন - রবার্ট গ্রোশ](https://medium.com/@robertgrosse/how-es6-classes-really-work-and-how-to-build-your-own-fd6085eb326a)
- 📜 [সহজভাবে জাভাস্ক্রিপ্টের 'সুপার' (Super)](https://jordankasper.com/understanding-super-in-javascript)
- 📜 [জাভাস্ক্রিপ্টের ক্লাস বুঝার জন্য একটি সহজ গাইড](https://dev.to/lawrence_eagles/an-easy-guide-to-understanding-classes-in-javascript-3bcm)

### ভিডিওগুলো

- 🎥 [জাভাস্ক্রিপ্টের ফ্যাক্টরি ফাংশন — Programming with Mosh](https://www.youtube.com/watch?v=jpegXpQpb3o)
- 🎥 [জাভাস্ক্রিপ্টের ফ্যাক্টরি ফাংশন — Fun Fun Function](https://www.youtube.com/watch?v=ImwrezYhw4w)
- 🎥 [জাভাস্ক্রিপ্ট টিউটোরিয়ালঃ ফাংশনের ফ্যাক্টরি — Crypto Chan](https://www.youtube.com/watch?v=R7-IwpH80UE)

**[⬆ উপরে ফিরে যান](#table-of-contents)**

---

## 15. this, call, apply and bind

### Reference

- 📜 [call() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/call)
- 📜 [bind() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_objects/Function/bind)
- 📜 [apply() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/apply)

### Articles

- 📜 [Grokking call(), apply() and bind() methods in JavaScript — Aniket Kudale](https://levelup.gitconnected.com/grokking-call-apply-and-bind-methods-in-javascript-392351a4be8b)
- 📜 [How-to: call() , apply() and bind() in JavaScript — Niladri Sekhar Dutta](https://www.codementor.io/niladrisekhardutta/how-to-call-apply-and-bind-in-javascript-8i1jca6jp)
- 📜 [JavaScript’s Apply, Call, and Bind Methods are Essential for JavaScript Professionals — Richard Bovell](http://javascriptissexy.com/javascript-apply-call-and-bind-methods-are-essential-for-javascript-professionals/)
- 📜 [WTF is this - Understanding the this keyword, call, apply, and bind in JavaScript — Tyler McGinnis](https://tylermcginnis.com/this-keyword-call-apply-bind-javascript/)
- 📜 [Javascript: call(), apply() and bind() — Omer Goldberg](https://medium.com/@omergoldberg/javascript-call-apply-and-bind-e5c27301f7bb)
- 📜 [The difference between call / apply / bind — Ivan Sifrim](https://medium.com/@ivansifrim/the-differences-between-call-apply-bind-276724bb825b)
- 📜 [What the hack is call, apply, bind in JavaScript — Ritik](https://dev.to/ritik_dev_js/what-the-hack-is-call-apply-bind-in-javascript-11ce)
- 📜 [Mastering 'this' in JavaScript: Callbacks and bind(), apply(), call() — Michelle Gienow](https://thenewstack.io/mastering-javascript-callbacks-bind-apply-call/)
- 📜 [JavaScript’s apply, call, and bind explained by hosting a cookout — Kevin Kononenko](https://dev.to/kbk0125/javascripts-apply-call-and-bind-explained-by-hosting-a-cookout-32jo)
- 📜 [How AND When to use bind, call, and apply in Javascript — Eigen X](https://www.eigenx.com/blog/https/mediumcom/eigen-x/how-and-when-to-use-bind-call-and-apply-in-javascript-77b6f42898fb)
- 📜 [JavaScript .bind() vs .apply() and .call() — Hack Sparrow](https://www.hacksparrow.com/javascript-bind-vs-apply-and-call.html)
- 📜 [Let me explain to you what is `this`. (Javascript) — Jason Yu](https://dev.to/ycmjason/let-me-explain-to-you-what-is-this-javascript-44ja)
- 📜 [Understanding the “this” Keyword in JavaScript — Pavan](https://medium.com/quick-code/understanding-the-this-keyword-in-javascript-cb76d4c7c5e8)
- 📜 [How to understand the keyword this and context in JavaScript — Lukas Gisder-Dubé](https://medium.freecodecamp.org/how-to-understand-the-keyword-this-and-context-in-javascript-cd624c6b74b8)
- 📜 [What the heck is this in Javascript? — Hridayesh Sharma](https://dev.to/_hridaysharma/what-the-heck-is-this-in-javascript-37n1)
- 📜 [This and Bind In Javascript — Brian Barbour](https://dev.to/steelvoltage/this-and-bind-in-javascript-2pam)
- 📜 [3 Techniques for Maintaining Your Sanity Using "This" in JavaScript — Carl](https://dev.to/canderson93/3-techniques-for-maintaining-your-sanity-using-this-in-javascript-3idf)
- 📜 [Mastering the JavaScript "this" Keyword — Aakash Srivastav](https://dev.to/aakashsr/mastering-the-javascript-this-keyword-4pfa)
- 📜 [This binding in JavaScript – 4. New binding — Spyros Argalias](https://dev.to/sargalias/this-binding-in-javascript-4-new-binding-2p1n)
- 📜 [A quick intro to 'this' in JavaScript — Natalie Smith](https://dev.to/thatgalnatalie/a-quick-intro-to-this-in-javascript-2mhp)
- 📜 [Explaining JavaScript 'this' to my cat — Andrey K](https://dev.to/cat__logic/explaining-javascript-this-to-my-cat-1kig)
- 📜 [A conversation with the 'this' keyword in Javascript — Karen Efereyan](https://dev.to/developerkaren/a-conversation-with-the-this-keyword-in-javascript-3j6g)
- 📜 [What are call(), apply() and bind() in JavaScript — Amitav Mishra](https://jscurious.com/what-are-call-apply-and-bind-in-javascript/)
- 📜 [Understanding 'this' binding in JavaScript — Yasemin Cidem](https://yasemincidem.medium.com/understanding-this-binding-in-javascript-86687397c76d)

### Videos

- 🎥 [JavaScript call, apply and bind — techsith](https://www.youtube.com/watch?v=c0mLRpw-9rI)
- 🎥 [JavaScript Practical Applications of Call, Apply and Bind functions— techsith](https://www.youtube.com/watch?v=AYVYxezrMWA)
- 🎥 [JavaScript (call, bind, apply) — curious aatma](https://www.youtube.com/watch?v=Uy0NOXLBraE)
- 🎥 [Understanding Functions and 'this' In The World of ES2017 — Bryan Hughes](https://www.youtube.com/watch?v=AOSYY1_np_4)
- 🎥 [bind and this - Object Creation in JavaScript - FunFunFunction](https://www.youtube.com/watch?v=GhbhD1HR5vk)
- 🎥 [JS Function Methods call(), apply(), and bind() — Steve Griffith](https://www.youtube.com/watch?v=uBdH0iB1VDM)

**[⬆ Back to Top](#table-of-contents)**

---

## 16. new, Constructor, instanceof and Instances

### Articles

- 📜 [JavaScript For Beginners: the ‘new’ operator — Brandon Morelli](https://codeburst.io/javascript-for-beginners-the-new-operator-cee35beb669e)
- 📜 [Let’s demystify JavaScript’s ‘new’ keyword — Cynthia Lee](https://medium.freecodecamp.org/demystifying-javascripts-new-keyword-874df126184c)
- 📜 [Constructor, operator "new" — JavaScript.Info](https://javascript.info/constructor-new)
- 📜 [Understanding JavaScript Constructors — Faraz Kelhini](https://css-tricks.com/understanding-javascript-constructors/)
- 📜 [Use Constructor Functions — Openclassrooms](https://openclassrooms.com/en/courses/3523231-learn-to-code-with-javascript/4379006-use-constructor-functions)
- 📜 [Beyond `typeof` and `instanceof`: simplifying dynamic type checks — Dr. Axel Rauschmayer](http://2ality.com/2017/08/type-right.html)
- 📜 [What Is the Instanceof Operator in JavaScript — appendTo](https://appendto.com/2016/10/what-is-the-instanceof-operator-in-javascript/)
- 📜 [Function and Object, instances of each other — Kiro Risk](https://javascriptrefined.io/function-and-object-instances-of-each-other-1e1095d5faac)

**[⬆ Back to Top](#table-of-contents)**

---

## 17. Prototype Inheritance and Prototype Chain

### Reference

- 📜 [Inheritance and the prototype chain — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)

### Articles

- 📜 [Javascript : Prototype vs Class — Valentin PARSY](https://medium.com/@parsyval/javascript-prototype-vs-class-a7015d5473b)
- 📜 [JavaScript engine fundamentals: optimizing prototypes — Mathias Bynens](https://mathiasbynens.be/notes/prototypes)
- 📜 [JavaScript Prototype — NC Patro](https://codeburst.io/javascript-prototype-cb29d82b8809)
- 📜 [Prototype in Javascript — Sandeep Ranjan](https://www.codementor.io/sandeepranjan2007/prototype-in-javascipt-knbve0lqo)
- 📜 [Prototypes in JavaScript — Rupesh Mishra](https://hackernoon.com/prototypes-in-javascript-5bba2990e04b)
- 📜 [Prototype in JavaScript: it’s quirky, but here’s how it works — Pranav Jindal](https://medium.freecodecamp.org/prototype-in-js-busted-5547ec68872)
- 📜 [Understanding JavaScript: Prototype and Inheritance — Alexander Kondov](https://hackernoon.com/understanding-javascript-prototype-and-inheritance-d55a9a23bde2)
- 📜 [Understanding Classes (ES5) and Prototypal Inheritance in JavaScript — Hridayesh Sharma](https://dev.to/_hridaysharma/understanding-classes-es5-and-prototypal-inheritance-in-javascript-n8d)
- 📜 [prototype, **proto** and Prototypal inheritance in JavaScript — Varun Dey](https://dev.to/varundey/prototype-proto-and-prototypal-inheritance-in-javascript-2inl)
- 📜 [Prototypal Inheritance — JavaScript.Info](https://javascript.info/prototype-inheritance)
- 📜 [How To Work with Prototypes and Inheritance in JavaScript — Tania Rascia](https://www.digitalocean.com/community/tutorials/understanding-prototypes-and-inheritance-in-javascript)
- 📜 [Master JavaScript Prototypes & Inheritance — Arnav Aggarwal](https://codeburst.io/master-javascript-prototypes-inheritance-d0a9a5a75c4e)
- 📜 [JavaScript’s Prototypal Inheritance Explained Using CSS — Nash Vail](https://medium.freecodecamp.org/understanding-prototypal-inheritance-in-javascript-with-css-93b2fcda75e4)
- 📜 [Prototypal Inheritance in JavaScript — Jannis Redmann](https://gist.github.com/derhuerst/a585c4916b1c361cc6f0)
- 📜 [Demystifying ES6 Classes And Prototypal Inheritance ― Neo Ighodaro](https://scotch.io/tutorials/demystifying-es6-classes-and-prototypal-inheritance)
- 📜 [Intro To Prototypal Inheritance — Dharani Jayakanthan](https://dev.to/danny/intro-to-prototypal-inheritance---js-9di)
- 📜 [Let’s Build Prototypal Inheritance in JS — var-che](https://dev.to/varche/let-s-build-prototypal-inheritance-in-js-56mm)
- 📜 [Objects, Prototypes and Classes in JavaScript — Atta](https://dev.to/attacomsian/objects-prototypes-and-classes-in-javascript-3i9b)
- 📜 [The magical world of JavaScript prototypes — Belén](https://dev.to/ladybenko/the-magical-world-of-javascript-prototypes-1mhg)
- 📜 [Understanding Prototypal Inheritance In JavaScript — Lawrence Eagles](https://dev.to/lawrence_eagles/understanding-prototypal-inheritance-in-javascript-4f31#chp-4)
- 📜 [Objects and Prototypes in JavaScript — Irena Popova](https://dev.to/irenejpopova/objects-and-prototypes-in-javascript-2eie)

### Videos

- 🎥 [Javascript Prototype Inheritance — Avelx](https://www.youtube.com/watch?v=sOrtAjyk4lQ)
- 🎥 [JavaScript Prototype Inheritance Explained pt. I — techsith](https://www.youtube.com/watch?v=7oNWNlMrkpc)
- 🎥 [JavaScript Prototype Inheritance Explained pt. II — techsith](https://www.youtube.com/watch?v=uIlj6_z_wL8)
- 🎥 [JavaScript Prototype Inheritance Explained — Kyle Robinson](https://www.youtube.com/watch?v=qMO-LTOrJaE)
- 🎥 [Advanced Javascript - Prototypal Inheritance In 1 Minute](https://www.youtube.com/watch?v=G6l5CHl67HQ)
- 🎥 [An Overview Of Classical Javascript Classes and Prototypal Inheritance — Pentacode](https://www.youtube.com/watch?v=phwzuiJJPpQ)
- 🎥 [Object Oriented JavaScript - Prototype — The Net Ninja](https://www.youtube.com/watch?v=4jb4AYEyhRc)
- 🎥 [Prototype in JavaScript — kudvenkat](https://www.youtube.com/watch?v=2rkEbcptR64)
- 🎥 [JavaScript Using Prototypes — O'Reilly](https://www.youtube.com/watch?v=oCwCcNvaXAQ)
- 🎥 [A Beginner's Guide to Javascript's Prototype — Tyler Mcginnis](https://www.youtube.com/watch?v=XskMWBXNbp0)
- 🎥 [Prototypes in Javascript - p5.js Tutorial — The Coding Train](https://www.youtube.com/watch?v=hS_WqkyUah8)

### Books

- [You Don't Know JS, 1st Edition: this & Object Prototypes — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/tree/1st-ed)

**[⬆ Back to Top](#table-of-contents)**

---

## 18. Object.create and Object.assign

### Reference

- 📜 [Object.create() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create)
- 📜 [Object.assign() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)

### Articles

- 📜 [Object.create in JavaScript — Rupesh Mishra](https://medium.com/@happymishra66/object-create-in-javascript-fa8674df6ed2)
- 📜 [Object.create(): the New Way to Create Objects in JavaScript — Rob Gravelle](https://www.htmlgoodies.com/beyond/javascript/object.create-the-new-way-to-create-objects-in-javascript.html)
- 📜 [Basic Inheritance with Object.create — Joshua Clanton](http://adripofjavascript.com/blog/drips/basic-inheritance-with-object-create.html)
- 📜 [Object.create() In JavaScript — GeeksforGeeks](https://www.geeksforgeeks.org/object-create-javascript/)
- 📜 [Understanding the difference between Object.create() and the new operator — Jonathan Voxland](https://medium.com/@jonathanvox01/understanding-the-difference-between-object-create-and-the-new-operator-b2a2f4749358)
- 📜 [JavaScript Object Creation: Patterns and Best Practices — Jeff Mott](https://www.sitepoint.com/javascript-object-creation-patterns-best-practises/)
- 📜 [Dealing With Objects in JavaScript With Object.assign, Object.keys and hasOwnProperty](https://alligator.io/js/dealing-with-objects/)
- 📜 [Copying Objects in JavaScript ― Orinami Olatunji](https://scotch.io/bar-talk/copying-objects-in-javascript)
- 📜 [JavaScript: Object.assign() — Thiago S. Adriano](https://codeburst.io/javascript-object-assign-bc9696dcbb6e)
- 📜 [How to deep clone a JavaScript Object — Flavio Copes](https://flaviocopes.com/how-to-clone-javascript-object/)
- 📜 [Object.create(): When and Why to Use — VZing](https://dev.to/vzing/object-create-when-and-why-to-use-20m9)

### Videos

- 🎥 [Object.assign() explained — Aaron Writes Code](https://www.youtube.com/watch?v=aw7NfYhR5rc)
- 🎥 [Object.assign() Method — techsith](https://www.youtube.com/watch?v=9Ky4X6inpi4)

**[⬆ Back to Top](#table-of-contents)**

---

## 19. map, reduce, filter

### Articles

- 📜 [JavaScript Functional Programming — map, filter and reduce — Bojan Gvozderac](https://medium.com/jsguru/javascript-functional-programming-map-filter-and-reduce-846ff9ba492d)
- 📜 [Learn map, filter and reduce in Javascript — João Miguel Cunha](https://medium.com/@joomiguelcunha/learn-map-filter-and-reduce-in-javascript-ea59009593c4)
- 📜 [JavaScript’s Map, Reduce, and Filter — Dan Martensen](https://danmartensen.svbtle.com/javascripts-map-reduce-and-filter)
- 📜 [How to Use Map, Filter, & Reduce in JavaScript — Peleke Sengstacke](https://code.tutsplus.com/tutorials/how-to-use-map-filter-reduce-in-javascript--cms-26209)
- 📜 [JavaScript — Learn to Chain Map, Filter, and Reduce — Brandon Morelli](https://codeburst.io/javascript-learn-to-chain-map-filter-and-reduce-acd2d0562cd4)
- 📜 [Javascript data structure with map, reduce, filter and ES6 — Deepak Gupta](https://codeburst.io/write-beautiful-javascript-with-%CE%BB-fp-es6-350cd64ab5bf)
- 📜 [Understanding map, filter and reduce in Javascript — Luuk Gruijs](https://hackernoon.com/understanding-map-filter-and-reduce-in-javascript-5df1c7eee464)
- 📜 [Functional Programming in JS: map, filter, reduce (Pt. 5) — Omer Goldberg](https://hackernoon.com/functional-programming-in-js-map-filter-reduce-pt-5-308a205fdd5f)
- 📜 [JavaScript: Map, Filter, Reduce — William S. Vincent](https://wsvincent.com/functional-javascript-map-filter-reduce/)
- 📜 [Arrow Functions: Fat and Concise Syntax in JavaScript — Kyle Pennell](https://www.sitepoint.com/es6-arrow-functions-new-fat-concise-syntax-javascript/)
- 📜 [JavaScript: Arrow Functions for Beginners — Brandon Morelli](https://codeburst.io/javascript-arrow-functions-for-beginners-926947fc0cdc)
- 📜 [When (and why) you should use ES6 arrow functions — and when you shouldn’t — Cynthia Lee](https://medium.freecodecamp.org/when-and-why-you-should-use-es6-arrow-functions-and-when-you-shouldnt-3d851d7f0b26)
- 📜 [JavaScript — Learn & Understand Arrow Functions — Brandon Morelli](https://codeburst.io/javascript-learn-understand-arrow-functions-fe2083533946)
- 📜 [(JavaScript )=> Arrow functions — sigu](https://medium.com/podiihq/javascript-arrow-functions-27d4c3334b83)
- 📜 [Javascript.reduce() — Paul Anderson](https://medium.com/@panderson.dev/javascript-reduce-79aab078da23)
- 📜 [Why you should replace forEach with map and filter in JavaScript — Roope Hakulinen](https://gofore.com/en/why-you-should-replace-foreach/)
- 📜 [Simplify your JavaScript – Use .map(), .reduce(), and .filter() — Etienne Talbot](https://medium.com/poka-techblog/simplify-your-javascript-use-map-reduce-and-filter-bd02c593cc2d)
- 📜 [JavaScript’s Reduce Method Explained By Going On a Diet — Kevin Kononenko](https://blog.codeanalogies.com/2018/07/24/javascripts-reduce-method-explained-by-going-on-a-diet/)
- 📜 [Difference between map, filter and reduce in JavaScript — Amirata Khodaparast](https://medium.com/@amiratak88/difference-between-map-filter-and-reduce-in-javascript-822ff79d5160)
- 📜 [Map⇄Filter⇄Reduce↻ — ashay mandwarya](https://hackernoon.com/map-filter-reduce-ebbed4be4201)
- 📜 [Finding Your Way With .map() — Brandon Wozniewicz](https://medium.freecodecamp.org/finding-your-way-with-map-aecb8ca038f6)
- 📜 [How to write your own map, filter and reduce functions in JavaScript — Hemand Nair](https://medium.freecodecamp.org/how-to-write-your-own-map-filter-and-reduce-functions-in-javascript-ab1e35679d26)
- 📜 [How to Manipulate Arrays in JavaScript — Bolaji Ayodeji](https://www.freecodecamp.org/news/manipulating-arrays-in-javascript/)
- 📜 [How to simplify your codebase with map(), reduce(), and filter() in JavaScript — Alex Permyakov](https://www.freecodecamp.org/news/15-useful-javascript-examples-of-map-reduce-and-filter-74cbbb5e0a1f)
- 📜 [.map(), .filter(), and .reduce() — Andy Pickle](https://dev.to/pickleat/map-filter-and-reduce-2efb)
- 📜 [Map/Filter/Reduce Crash Course — Chris Achard](https://dev.to/chrisachard/map-filter-reduce-crash-course-5gan)
- 📜 [Map, Filter and Reduce – Animated — JavaScript Teacher](https://medium.com/@js_tut/map-filter-and-reduce-animated-7fe391a35a47)
- 📜 [Map, Filter, Reduce and others Arrays Iterators You Must Know to Become an Algorithms Wizard — Mauro Bono](https://dev.to/uptheirons78/map-filter-reduce-and-others-arrays-iterators-you-must-know-to-become-an-algorithms-wizard-4209)
- 📜 [How to Use JavaScript’s .map, .filter, and .reduce — Avery Duffin](https://medium.com/better-programming/how-to-javascripts-map-vs-filter-vs-reduce-80d87a5a0a24)
- 📜 [Javascript performance test - for vs for each vs (map, reduce, filter, find) — Deepak Gupta](https://towardsdatascience.com/javascript-performance-test-for-vs-for-each-vs-map-reduce-filter-find-32c1113f19d7)
- 📜 [Using .map(), .filter() and .reduce() properly — Sasanka Kudagoda](https://medium.com/javascript-in-plain-english/using-map-filter-and-reduce-properly-50e07f80c8b2)
- 📜 [Mastering the JavaScript Reduce method ✂️ — sanderdebr](https://dev.to/sanderdebr/mastering-the-javascript-reduce-method-2foj)

### Videos

- 🎥 [Map, Filter and Reduce — Lydia Hallie](https://www.youtube.com/watch?v=UXiYii0Y7Nw)
- 🎥 [Functional JavaScript: Map, forEach, Reduce, Filter — Theodore Anderson](https://www.youtube.com/watch?v=vytzLlY_wmU)
- 🎥 [JavaScript Array superpowers: Map, Filter, Reduce (part I) — Michael Rosata](https://www.youtube.com/watch?v=qTeeVd8hOFY)
- 🎥 [JavaScript Array superpowers: Map, Filter, Reduce (part 2) — Michael Rosata](https://www.youtube.com/watch?v=gIm9xLYudL0)
- 🎥 [JavaScript Higher Order Functions - Filter, Map, Sort & Reduce — Epicop](https://www.youtube.com/watch?v=zYBeEPxNSbw)
- 🎥 [[Array Methods 2/3] .filter + .map + .reduce — CodeWithNick](https://www.youtube.com/watch?v=4qWlqD0yYTU)
- 🎥 [Arrow functions in JavaScript - What, Why and How — Fun Fun Function](https://www.youtube.com/watch?v=6sQDTgOqh-I)
- 🎥 [Learning Functional Programming with JavaScript — Anjana Vakil - JSUnconf](https://www.youtube.com/watch?v=e-5obm1G_FY&t=1521s)
- 🎥 [Map - Parte 2 JavaScript - Fun Fun Function](https://www.youtube.com/watch?v=bCqtb-Z5YGQ&t=17s)
- 🎥 [Reduce basics - Part 3 of FP in JavaScript - Fun Fun Function](https://www.youtube.com/watch?v=Wl98eZpkp-c)
- 🎥 [Reduce Advanced - Part 4 of FP in JavaScript - Fun Fun Function](https://www.youtube.com/watch?v=1DMolJ2FrNY&t=621s)
- 🎥 [reduce Array Method | JavaScript Tutorial - Florin Pop](https://www.youtube.com/watch?v=IXp06KekEjM)
- 🎥 [map Array Method | JavaScript Tutorial - Florin Pop](https://www.youtube.com/watch?v=P4RAFdZDn3M)

**[⬆ Back to Top](#table-of-contents)**

---

## 20. Pure Functions, Side Effects, State Mutation and Event Propagation

### Articles

- 📜 [Javascript and Functional Programming — Pure Functions — Omer Goldberg](https://hackernoon.com/javascript-and-functional-programming-pt-3-pure-functions-d572bb52e21c)
- 📜 [Master the JavaScript Interview: What is a Pure Function? — Eric Elliott](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976)
- 📜 [JavaScript: What Are Pure Functions And Why Use Them? — James Jeffery](https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c)
- 📜 [Pure functions in JavaScript — @nicoespeon](http://www.nicoespeon.com/en/2015/01/pure-functions-javascript/)
- 📜 [Functional Programming: Pure Functions — Arne Brasseur](https://www.sitepoint.com/functional-programming-pure-functions/)
- 📜 [Pure Functions In Javascript — Krunal](https://appdividend.com/2017/04/10/pure-functions-in-javascript/)
- 📜 [Making your JavaScript Pure — Jack Franklin](https://alistapart.com/article/making-your-javascript-pure)
- 📜 [Arrays, Objects and Mutations — Federico Knüssel](https://medium.com/@fknussel/arrays-objects-and-mutations-6b23348b54aa)
- 📜 [The State of Immutability — Maciej Sikora](https://medium.com/dailyjs/the-state-of-immutability-169d2cd11310)
- 📜 [How to deal with dirty side effects in your pure functional JavaScript — James Sinclair](https://jrsinclair.com/articles/2018/how-to-deal-with-dirty-side-effects-in-your-pure-functional-javascript/)
- 📜 [Preventing Side Effects in JavaScript — David Walsh](https://davidwalsh.name/preventing-sideeffects-javascript)
- 📜 [Wielding Pure Functions in JavaScript and Function Composition — Peleke Sengstacke](https://scotch.io/tutorials/wielding-pure-functions-in-javascript-and-function-composition)
- 📜 [JavaScript: Pure Functions — William S. Vincent](https://wsvincent.com/javascript-pure-functions/)
- 📜 [Functional programming paradigms in modern JavaScript: Pure functions — Alexander Kondov](https://hackernoon.com/functional-programming-paradigms-in-modern-javascript-pure-functions-797d9abbee1)
- 📜 [Understanding Javascript Mutation and Pure Functions — Chidume Nnamdi](https://blog.bitsrc.io/understanding-javascript-mutation-and-pure-functions-7231cc2180d3)
- 📜 [Functional-ish JavaScript — Daniel Brain](https://medium.com/@bluepnume/functional-ish-javascript-205c05d0ed08)
- 📜 [Event Propagation — MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
- 📜 [Event Propagation — Bubbling and capturing](https://javascript.info/bubbling-and-capturing)

### Videos

- 🎥 [Pure Functions — Hexlet](https://www.youtube.com/watch?v=dZ41D6LDSBg)
- 🎥 [Pure Functions - Functional Programming in JavaScript — Paul McBride](https://www.youtube.com/watch?v=Jh_Uzqzz_wM)
- 🎥 [JavaScript Pure Functions — Seth Alexander](https://www.youtube.com/watch?v=frT3H-eBmPc)
- 🎥 [JavaScript Pure vs Impure Functions Explained — Theodore Anderson](https://www.youtube.com/watch?v=AHbRVJzpB54)
- 🎥 [Pure Functions - Programação Funcional: Parte 1 - Fun Fun Function](https://www.youtube.com/watch?v=BMUiFMZr7vk)
- 🎥 [Event Propagation - JavaScript Event Bubbling and Propagation - Steve Griffith](https://www.youtube.com/watch?v=JYc7gr9Ehl0)

**[⬆ Back to Top](#table-of-contents)**

---

## 21. Closures

### Reference

- 📜 [Closures — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
- 📜 [Closure — JavaScript.Info](https://javascript.info/closure)

### Articles

- 📜 [I never understood JavaScript closures — Olivier De Meulder](https://medium.com/dailyjs/i-never-understood-javascript-closures-9663703368e8)
- 📜 [Understand JavaScript Closures With Ease — Richard Bovell](http://javascriptissexy.com/understand-javascript-closures-with-ease/)
- 📜 [Understanding JavaScript Closures — Codesmith](https://codeburst.io/understanding-javascript-closures-da6aab330302)
- 📜 [Understand Closures in JavaScript — Brandon Morelli](https://codeburst.io/understand-closures-in-javascript-d07852fa51e7)
- 📜 [A simple guide to help you understand closures in JavaScript — Prashant Ram](https://medium.freecodecamp.org/javascript-closures-simplified-d0d23fa06ba4)
- 📜 [Understanding JavaScript Closures: A Practical Approach — Paul Upendo](https://scotch.io/tutorials/understanding-javascript-closures-a-practical-approach)
- 📜 [Understanding JavaScript: Closures — Alexander Kondov](https://hackernoon.com/understanding-javascript-closures-4188edf5ea1b)
- 📜 [How to use JavaScript closures with confidence — Léna Faure](https://hackernoon.com/how-to-use-javascript-closures-with-confidence-85cd1f841a6b)
- 📜 [JavaScript closures by example — tyler](https://howchoo.com/g/mge2mji2mtq/javascript-closures-by-example)
- 📜 [JavaScript — Closures and Scope — Alex Aitken](https://codeburst.io/javascript-closures-and-scope-3784c75b9290)
- 📜 [Discover the power of closures in JavaScript — Cristi Salcescu](https://medium.freecodecamp.org/discover-the-power-of-closures-in-javascript-5c472a7765d7)
- 📜 [Simplified JavaScript: Getting Started with Closures — Code Like A Girl](https://code.likeagirl.io/simplified-javascript-getting-started-with-closures-f40f65317d00)
- 📜 [The Ultimate Guide to Hoisting, Scopes, and Closures in JavaScript — Tyler McGinnis](https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/)
- 📜 [Getting Closure — RealLifeJS](http://reallifejs.com/the-meat/getting-closure/)
- 📜 [Closure, Currying and IIFE in JavaScript — Ritik](https://dev.to/ritik_dev_js/what-the-hack-is-closure-currying-and-iife-in-javascript-32m9)
- 📜 [Understanding Closures in JavaScript — Sukhjinder Arora](https://blog.bitsrc.io/a-beginners-guide-to-closures-in-javascript-97d372284dda)
- 📜 [A basic guide to Closures in JavaScript — Parathan Thiyagalingam](https://medium.freecodecamp.org/a-basic-guide-to-closures-in-javascript-9fc8b7e3463e)
- 📜 [Closures: Using Memoization — Brian Barbour](https://dev.to/steelvoltage/closures-using-memoization-3597)
- 📜 [A Brief Introduction to Closures and Lexical Scoping in JavaScript — Ashutosh K Singh](https://medium.com/better-programming/a-brief-introduction-to-closures-and-lexical-scoping-in-javascript-8a5866496232)
- 📜 [Demystify Closures — stereobooster](https://dev.to/stereobooster/demystify-closures-5g42)
- 📜 [Scopes and Closures - JavaScript Concepts — Agney Menon](https://dev.to/boywithsilverwings/scopes-and-closures-javascript-concepts-4dfj)
- 📜 [Understanding Closures in JavaScript — Matt Popovich](https://dev.to/mattpopovich/understanding-closures-in-javascript-3k0d)
- 📜 [whatthefuck.is · A Closure - Dan Abramov](https://whatthefuck.is/closure)
- 📜 [Closures in JavaScript can... - Brandon LeBoeuf](https://dev.to/brandonleboeuf/closure-in-javascript-49n7)

### Videos

- 🎥 [JavaScript The Hard Parts: Closure, Scope & Execution Context - Codesmith](https://www.youtube.com/watch?v=XTAzsODSCsM)
- 🎥 [Javascript Closure — techsith](https://www.youtube.com/watch?v=71AtaJpJHw0)
- 🎥 [Closures — Fun Fun Function](https://www.youtube.com/watch?v=CQqwU2Ixu-U)
- 🎥 [Closures in JavaScript — techsith](https://www.youtube.com/watch?v=-xqJo5VRP4A)
- 🎥 [JavaScript Closures 101: What is a closure? — JavaScript Tutorials](https://www.youtube.com/watch?v=yiEeiMN2Khs)
- 🎥 [Closures — freeCodeCamp](https://www.youtube.com/watch?v=1JsJx1x35c0)
- 🎥 [JavaScript Closures — CodeWorkr](https://www.youtube.com/watch?v=-rLrGAXK8WE)

**[⬆ Back to Top](#table-of-contents)**

---

## 22. High Order Functions

### Books

- 📜 [Eloquent JavaScript, 3rd Edition: Ch. 5 - Higher-order Functions](https://eloquentjavascript.net/05_higher_order.html)

### Articles

- 📜 [Higher-Order Functions in JavaScript — M. David Green](https://www.sitepoint.com/higher-order-functions-javascript/)
- 📜 [Higher Order Functions: Using Filter, Map and Reduce for More Maintainable Code — Guido Schmitz](https://medium.freecodecamp.org/higher-order-functions-in-javascript-d9101f9cf528)
- 📜 [First-class and Higher Order Functions: Effective Functional JavaScript — Hugo Di Francesco](https://hackernoon.com/effective-functional-javascript-first-class-and-higher-order-functions-713fde8df50a)
- 📜 [Higher Order Functions in JavaScript — John Hannah](https://www.lullabot.com/articles/higher-order-functions-in-javascript)
- 📜 [Higher-order Functions — Richard Bovell](http://javascriptissexy.com/tag/higher-order-functions/)
- 📜 [Fun With Higher Order Functions In JavaScript — Derick](https://derickbailey.com/2015/10/21/fun-with-higher-order-functions-in-javascript/)
- 📜 [Just a reminder on how to use high order functions — Pedro Filho](https://github.com/pedroapfilho/high-order-functions)
- 📜 [Understanding Higher-Order Functions in JavaScript — Sukhjinder Arora](https://blog.bitsrc.io/understanding-higher-order-functions-in-javascript-75461803bad)
- 📜 [Higher Order Functions - A pragmatic approach — emmanuel ikwuoma](https://dev.to/nuel_ikwuoma/higher-order-functions-a-pragmatic-approach-51fb)

### Videos

- 🎥 [JavaScript Higher Order Functions & Arrays — Traversy Media](https://www.youtube.com/watch?v=rRgD1yVwIvE)
- 🎥 [Higher Order Functions — Fun Fun Function](https://www.youtube.com/watch?v=BMUiFMZr7vk)
- 🎥 [Higher Order Functions in Javascript — Raja Yogan](https://www.youtube.com/watch?v=dTlpYnmBW9I)
- 🎥 [Higher Order Iterators in JavaScript — Fun Fun Function](https://www.youtube.com/watch?v=GYRMNp1SKXA)
- 🎥 [Higher Order Functions in JavaScript — The Coding Train](https://www.youtube.com/watch?v=H4awPsyugS0)
- 🎥 [Part 1: An Introduction to Callbacks and Higher Order Functions - Codesmith](https://www.youtube.com/watch?v=7E8ctomPQJw)
- 🎥 [Part 2: Understanding Why We Need Higher Order Functions - Codesmith](https://www.youtube.com/watch?v=28MXziDZkE4)
- 🎥 [Higher-Order Functions ft. Functional Programming - Akshay Saini](https://www.youtube.com/watch?v=HkWxvB1RJq0)

**[⬆ Back to Top](#table-of-contents)**

---

## 23. Recursion

### Articles

- 📜 [Recursion in JavaScript — Kevin Ennis](https://medium.freecodecamp.org/recursion-in-javascript-1608032c7a1f)
- 📜 [Understanding Recursion in JavaScript — Zak Frisch](https://medium.com/@zfrisch/understanding-recursion-in-javascript-992e96449e03)
- 📜 [Learn and Understand Recursion in JavaScript — Brandon Morelli](https://codeburst.io/learn-and-understand-recursion-in-javascript-b588218e87ea)
- 📜 [Recursion in Functional JavaScript — M. David Green](https://www.sitepoint.com/recursion-functional-javascript/)
- 📜 [Programming with JS: Recursion — Alexander Kondov](https://hackernoon.com/programming-with-js-recursion-31371e2bf808)
- 📜 [Anonymous Recursion in JavaScript — simo](https://dev.to/simov/anonymous-recursion-in-javascript)
- 📜 [Recursion, iteration and tail calls in JS — loverajoel](http://www.jstips.co/en/javascript/recursion-iteration-and-tail-calls-in-js/)
- 📜 [Understanding Recursion in JavaScript with Confidence — Jay](https://www.thecodingdelight.com/understanding-recursion-javascript/)
- 📜 [Intro to Recursion — Brad Newman](https://medium.com/@newmanbradm/intro-to-recursion-984a8bd50f4b)
- 📜 [Accio Recursion!: Your New Favorite JavaScript Spell — Leanne Cabey](https://medium.com/datadriveninvestor/accio-recursion-your-new-favorite-javascript-spell-7e10d3125fb3)
- 📜 [Recursion Explained (with Examples) — Christina](https://dev.to/christinamcmahon/recursion-explained-with-examples-4k1m)

### Videos

- 🎥 [Recursion In JavaScript — techsith](https://www.youtube.com/watch?v=VtG0WAUvq2w)
- 🎥 [Recursion — Fun Fun Function](https://www.youtube.com/watch?v=k7-N8R0-KY4)
- 🎥 [Recursion and Recursive Functions — Hexlet](https://www.youtube.com/watch?v=vLhHyGTkjCs)
- 🎥 [Recursion: Recursion() — JS Monthly — Lucas da Costa](https://www.youtube.com/watch?v=kGXVsd8pBLw)
- 🎥 [Recursive Function in JavaScript — kudvenkat](https://www.youtube.com/watch?v=uyjsR9eNTIw)
- 🎥 [What on Earth is Recursion? — Computerphile](https://www.youtube.com/watch?v=Mv9NEXX1VHc)
- 🎥 [Javascript Tutorial 34: Introduction To Recursion — codedamn](https://www.youtube.com/watch?v=9NO5dXSlbv8)
- 🎥 [Recursion, Iteration, and JavaScript: A Love Story | JSHeroes 2018 — Anjana Vakil](https://www.youtube.com/watch?v=FmiQr4nfoPQ)

**[⬆ Back to Top](#table-of-contents)**

---

## 24. Collections and Generators

### Reference

- 📜 [Generator — MDN web docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator)

### Articles

- 📜 [ES6 In Depth: Collections — Jason Orendorff](https://hacks.mozilla.org/2015/06/es6-in-depth-collections/)
- 📜 [ES6 Collections: Using Map, Set, WeakMap, WeakSet — Kyle Pennell](https://www.sitepoint.com/es6-collections-map-set-weakmap-weakset/)
- 📜 [ES6 WeakMaps, Sets, and WeakSets in Depth — Nicolás Bevacqua](https://ponyfoo.com/articles/es6-weakmaps-sets-and-weaksets-in-depth)
- 📜 [Introduction to Sets in JavaScript — Alligator.io](https://alligator.io/js/sets-introduction/)
- 📜 [Introduction to Maps in JavaScript — Alligator.io](https://alligator.io/js/maps-introduction/)
- 📜 [Map, Set, WeakMap and WeakSet — JavaScript.Info](https://javascript.info/map-set-weakmap-weakset)
- 📜 [Maps in ES6 - A Quick Guide — Ben Mildren](https://dev.to/mildrenben/maps-in-es6---a-quick-guide-35pk)
- 📜 [ES6 — Set vs Array — What and when? — Maya Shavin](https://medium.com/front-end-hacking/es6-set-vs-array-what-and-when-efc055655e1a)
- 📜 [ES6 — Map vs Object — What and when? — Maya Shavin](https://medium.com/front-end-hacking/es6-map-vs-object-what-and-when-b80621932373)
- 📜 [ES6: Working with Sets in JavaScript — Dead Code Rising](http://www.deadcoderising.com/es6-working-with-sets-in-javascript/)
- 📜 [Array vs Set vs Map vs Object — Real-time use cases in Javascript (ES6/ES7) — Rajesh Babu](https://codeburst.io/array-vs-set-vs-map-vs-object-real-time-use-cases-in-javascript-es6-47ee3295329b)
- 📜 [How to create an array of unique values in JavaScript using Sets — Claire Parker-Jones](https://dev.to/claireparker/how-to-create-an-array-of-unique-values-in-javascript-using-sets-5dg6)
- 📜 [What You Should Know About ES6 Maps — Just Chris](https://hackernoon.com/what-you-should-know-about-es6-maps-dc66af6b9a1e)
- 📜 [ES6 Maps in Depth — Nicolás Bevacqua](https://ponyfoo.com/articles/es6-maps-in-depth)
- 📜 [What are JavaScript Generators and how to use them — Vladislav Stepanov](https://codeburst.io/what-are-javascript-generators-and-how-to-use-them-c6f2713fd12e)
- 📜 [Understanding JavaScript Generators With Examples — Arfat Salman](https://codeburst.io/understanding-generators-in-es6-javascript-with-examples-6728834016d5)
- 📜 [The Basics of ES6 Generators — Kyle Simpson](https://davidwalsh.name/es6-generators)
- 📜 [An Introduction to JavaScript Generators — Alice Kallaugher](https://dev.to/kallaugher/an-introduction-to-javascript-generators-1224)

### Videos

- 🎥 [JavaScript ES6 / ES2015 Set, Map, WeakSet and WeakMap — Traversy Media](https://www.youtube.com/watch?v=ycohYSx5h9w)
- 🎥 [The Differences between ES6 Maps and Sets — Steve Griffith](https://www.youtube.com/watch?v=m4abICrldQI)
- 🎥 [Javascript Generators - THEY CHANGE EVERYTHING - ES6 Generators Harmony Generators — LearnCode.academy](https://www.youtube.com/watch?v=QO07THdLWQo)

**[⬆ Back to Top](#table-of-contents)**

---

## 25. Promises

### Reference

- 📜 [Promise — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)

### Articles

- 📜 [JavaScript Promises for Dummies ― Jecelyn Yeen](https://scotch.io/tutorials/javascript-promises-for-dummies)
- 📜 [Understanding promises in JavaScript — Gokul N K](https://hackernoon.com/understanding-promises-in-javascript-13d99df067c1)
- 📜 [Master the JavaScript Interview: What is a Promise? — Eric Elliott](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261)
- 📜 [An Overview of JavaScript Promises — Sandeep Panda](https://www.sitepoint.com/overview-javascript-promises/)
- 📜 [How to use Promises in JavaScript — Prashant Ram](https://medium.freecodecamp.org/promises-in-javascript-explained-277b98850de)
- 📜 [Implementing Promises In JavaScript — Maciej Cieslar](https://medium.freecodecamp.org/how-to-implement-promises-in-javascript-1ce2680a7f51)
- 📜 [JavaScript: Promises explained with simple real life analogies — Shruti Kapoor](https://codeburst.io/javascript-promises-explained-with-simple-real-life-analogies-dd6908092138)
- 📜 [Promises for Asynchronous Programming — Exploring JS](http://exploringjs.com/es6/ch_promises.html)
- 📜 [JavaScript Promises Explained By Gambling At A Casino — Kevin Kononenko](https://blog.codeanalogies.com/2018/08/26/javascript-promises-explained-by-gambling-at-a-casino/)
- 📜 [ES6 Promises: Patterns and Anti-Patterns — Bobby Brennan](https://medium.com/datafire-io/es6-promises-patterns-and-anti-patterns-bbb21a5d0918)
- 📜 [A Simple Guide to ES6 Promises — Brandon Morelli](https://codeburst.io/a-simple-guide-to-es6-promises-d71bacd2e13a)
- 📜 [The ES6 Promises — Manoj Singh Negi](https://codeburst.io/the-es6-promises-87a979ab27e4)
- 📜 [ES6 Promises in Depth — Nicolás Bevacqua](https://ponyfoo.com/articles/es6-promises-in-depth)
- 📜 [Playing with Javascript Promises: A Comprehensive Approach — Rajesh Babu](https://codeburst.io/playing-with-javascript-promises-a-comprehensive-approach-25ab752c78c3)
- 📜 [How to Write a JavaScript Promise — Brandon Wozniewicz](https://medium.freecodecamp.org/how-to-write-a-javascript-promise-4ed8d44292b8)
- 📜 [A Coding Writer’s Guide: An Introduction To ES6 Promises — Andrew Ly](https://medium.com/@andrewly07/a-coding-writers-guide-an-introduction-to-es6-promises-9ff9f9e88f6c)
- 📜 [Understanding Promises in JavaScript — Chris Noring](https://dev.to/itnext/reverse-engineering-understand-promises-1jfc)
- 📜 [Converting callbacks to promises — Zell Liew](https://dev.to/zellwk/converting-callbacks-to-promises-nhn)
- 📜 [JavaScript Promises: Zero To Hero Plus Cheat Sheet — Joshua Saunders](https://medium.com/dailyjs/javascript-promises-zero-to-hero-plus-cheat-sheet-64d75051cffa)
- 📜 [Promises - JavaScript concepts — Agney Menon](https://dev.to/boywithsilverwings/promises-javascript-concepts-293c)
- 📜 [Javascript `Promise` 101 — Igor Irianto](https://dev.to/iggredible/javascript-promise-101-3idl)
- 📜 [Simplify JavaScript Promises — Sunny Singh](https://dev.to/sunnysingh/simplify-javascript-promises-4djb)
- 📜 [The Lowdown on Promises — Aphinya Dechalert](https://medium.com/better-programming/the-low-down-on-promises-af4a96bbb95f)
- 📜 [JavaScript Visualized: Promises & Async/Await — Lydia Hallie](https://dev.to/lydiahallie/javascript-visualized-promises-async-await-5gke)
- 📜 [Promises in JavaScript — Peter Klingelhofer](https://dev.to/peterklingelhofer/promises-in-javascript-3h5k)
- 📜 [Best Practices for ES6 Promises — Basti Ortiz](https://dev.to/somedood/best-practices-for-es6-promises-36da)

### Videos

- 🎥 [Let's Learn ES6 - Promises — Ryan Christiani](https://www.youtube.com/watch?v=vQ3MoXnKfuQ)
- 🎥 [JavaScript ES6 / ES2015 Promises — Traversy Media](https://www.youtube.com/watch?v=XJEHuBZQ5dU)
- 🎥 [Promises — Fun Fun Function](https://www.youtube.com/watch?v=2d7s3spWAzo)
- 🎥 [Error Handling Promises in JavaScript — Fun Fun Function](https://www.youtube.com/watch?v=f8IgdnYIwOU)
- 🎥 [Promises Part 1 - Topics of JavaScript/ES6 — The Coding Train](https://www.youtube.com/watch?v=QO4NXhWo_NM)

**[⬆ Back to Top](#table-of-contents)**

---

## 26. async/await

### Reference

- 📜 [async/await — JavaScript.Info](https://javascript.info/async-await)

### Books

- 📜 [Eloquent JavaScript, 3rd Edition: Ch. 11 - Asynchronous Programming](https://eloquentjavascript.net/11_async.html)
- 📜 [Exploring JS: Asynchronous Programming](http://exploringjs.com/es6/ch_async.html)

### Articles

- 📜 [Understanding async/await in Javascript — Gokul N K](https://hackernoon.com/understanding-async-await-in-javascript-1d81bb079b2c)
- 📜 [Exploring Async/Await Functions in JavaScript — Alligator.io](https://alligator.io/js/async-functions/)
- 📜 [Asynchronous Javascript using async/await — Joy Warugu](https://scotch.io/tutorials/asynchronous-javascript-using-async-await)
- 📜 [Modern Asynchronous JavaScript with async/await — Flavio Copes](https://flaviocopes.com/javascript-async-await/)
- 📜 [Asynchronous JavaScript: From Callback Hell to Async and Await — Demir Selmanovic](https://www.toptal.com/javascript/asynchronous-javascript-async-await-tutorial)
- 📜 [Javascript — ES8 Introducing async/await Functions — Ben Garrison](https://medium.com/@_bengarrison/javascript-es8-introducing-async-await-functions-7a471ec7de8a)
- 📜 [How to escape async/await hell — Aditya Agarwal](https://medium.freecodecamp.org/avoiding-the-async-await-hell-c77a0fb71c4c)
- 📜 [Understanding JavaScript’s async await — Nicolás Bevacqua](https://ponyfoo.com/articles/understanding-javascript-async-await)
- 📜 [JavaScript Async/Await: Serial, Parallel and Complex Flow — TechBrij](https://techbrij.com/javascript-async-await-parallel-sequence)
- 📜 [From JavaScript Promises to Async/Await: why bother? — Chris Nwamba](https://blog.pusher.com/promises-async-await/)
- 📜 [Flow Control in Modern JS: Callbacks to Promises to Async/Await — Craig Buckler](https://www.sitepoint.com/flow-control-callbacks-promises-async-await/)
- 📜 [JavaScript: Promises and Why Async/Await Wins the Battle — Nick Parsons](https://dzone.com/articles/javascript-promises-and-why-asyncawait-wins-the-ba)
- 📜 [How to improve your asynchronous Javascript code with async and await — Indrek Lasn](https://medium.freecodecamp.org/improve-your-asynchronous-javascript-code-with-async-and-await-c02fc3813eda)
- 📜 [Making Fetches Easy With Async Await — Mickey Sheridan](https://medium.com/@micksheridan.24/making-fetches-easy-with-async-await-8a1246efa1f6)
- 📜 [7 Reasons Why JavaScript Async/Await Is Better Than Plain Promises — Mostafa Gaafar](https://dev.to/gafi/7-reasons-to-always-use-async-await-over-plain-promises-tutorial-4ej9)
- 📜 [Asynchronous Operations in JavaScript — Jscrambler](https://dev.to/jscrambler/asynchronous-operations-in-javascript-2p6b)
- 📜 [Async/await: A slight design flaw. — Joey](https://dev.to/joeyhub/async-await-a-slight-design-flaw-2h2j)
- 📜 [JavaScript: Promises or async-await — Gokul N K](https://medium.com/better-programming/should-i-use-promises-or-async-await-126ab5c98789)
- 📜 [Async / Await: From Zero to Hero — Zhi Yuan](https://dev.to/zhiyuanamos/async-await-from-zero-to-hero-a22)
- 📜 [JavaScript Visualized: Promises & Async/Await — Lydia Hallie](https://dev.to/lydiahallie/javascript-visualized-promises-async-await-5gke)

### Videos

- 🎥 [Async + Await — Wes Bos](https://www.youtube.com/watch?v=9YkUCxvaLEk)
- 🎥 [Asynchrony: Under the Hood — Shelley Vohr](https://www.youtube.com/watch?v=SrNQS8J67zc)
- 🎥 [async/await in JavaScript - What, Why and How — Fun Fun Function](https://www.youtube.com/watch?v=568g8hxJJp4&index=3&list=PL0zVEGEvSaeHJppaRLrqjeTPnCH6)
- 🎥 [async/await Part 1 - Topics of JavaScript/ES8 — The Coding Train](https://www.youtube.com/watch?v=XO77Fib9tSI&index=3&list=PLRqwX-V7Uu6bKLPQvPRNNE65kBL62mVfx)
- 🎥 [async/await Part 2 - Topics of JavaScript/ES8 — The Coding Train](https://www.youtube.com/watch?v=chavThlNz3s&index=4&list=PLRqwX-V7Uu6bKLPQvPRNNE65kBL62mVfx)
- 🎥 [Complete Guide to JS Async & Await ES2017/ES8 — Colt Steele](https://www.youtube.com/watch?v=krAYA4rvbdA)

**[⬆ Back to Top](#table-of-contents)**

---

## 27. Data Structures

### Articles

- 📜 [Data Structures in JavaScript — Thon Ly](https://medium.com/siliconwat/data-structures-in-javascript-1b9aed0ea17c)
- 📜 [Algorithms and Data Structures in JavaScript — Oleksii Trekhleb](https://itnext.io/algorithms-and-data-structures-in-javascript-a71548f902cb)
- 📜 [Data Structures: Objects and Arrays ― Chris Nwamba](https://scotch.io/courses/10-need-to-know-javascript-concepts/data-structures-objects-and-arrays)
- 📜 [Data structures in JavaScript — Benoit Vallon](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/)
- 📜 [Playing with Data Structures in Javascript — Anish K.](https://blog.cloudboost.io/playing-with-data-structures-in-javascript-stack-a55ebe50f29d)
- 📜 [The Little Guide of Queue in JavaScript — Germán Cutraro](https://hackernoon.com/the-little-guide-of-queue-in-javascript-4f67e79260d9)
- 📜 [All algorithms writing with JavaScript in the book 'Algorithms Fourth Edition'](https://github.com/barretlee/algorithms)
- 📜 [Collection of classic computer science paradigms in JavaScript](https://github.com/nzakas/computer-science-in-javascript)
- 📜 [All the things you didn't know you wanted to know about data structures](https://github.com/jamiebuilds/itsy-bitsy-data-structures)
- 📜 [JavaScript Data Structures: 40 Part Series — miku86](https://dev.to/miku86/series/3259)
- 📜 [Data Structures: Understanding Graphs — Rachel Hawa](https://medium.com/javascript-in-plain-english/data-structures-understanding-graphs-82509d35e6b5)
- 📜 [Data Structures Two Ways: Linked List (Pt 1) — Freddie Duffield](https://dev.to/freddieduffield/data-structures-two-ways-linked-list-2n61)
- 📜 [Data Structures Two Ways: Linked List (Pt 2) — Freddie Duffield](https://dev.to/freddieduffield/data-structures-two-ways-linked-list-pt2-2i60)
- 📜 [Graph Data Structures Explained in JavaScript — Adrian Mejia](https://dev.to/amejiarosario/graph-data-structures-for-beginners-5edn)

### Videos

- 🎥 [Algorithms In Javascript | Ace Your Interview — Eduonix Learning Solutions](https://www.youtube.com/watch?v=H_EBPZgiAas&list=PLDmvslp_VR0zYUSth_8O69p4_cmvZEgLa)
- 🎥 [Data Structures and Algorithms in JavaScript — freeCodeCamp](https://www.youtube.com/watch?v=Gj5qBheGOEo&list=PLWKjhJtqVAbkso-IbgiiP48n-O-JQA9PJ)
- 🎥 [Learning JavaScript Data Structures and Algorithms: Sorting — Packt Video](https://www.youtube.com/watch?v=Ymh_AurrMbA)

**[⬆ Back to Top](#table-of-contents)**

---

## 28. Expensive Operation and Big O Notation

### Articles

- 📜 [Big O Notation in Javascript — César Antón Dorantes](https://medium.com/cesars-tech-insights/big-o-notation-javascript-25c79f50b19b)
- 📜 [Time Complexity/Big O Notation — Tim Roberts](https://medium.com/javascript-scene/time-complexity-big-o-notation-1a4310c3ee4b)
- 📜 [Big O in JavaScript — Gabriela Medina](https://medium.com/@gmedina229/big-o-in-javascript-36ff67766051)
- 📜 [Big O Search Algorithms in JavaScript — Bradley Braithwaite](http://www.bradoncode.com/blog/2012/04/big-o-algorithm-examples-in-javascript.html)
- 📜 [Time Complexity Analysis in JavaScript — Jennifer Bland](https://www.jenniferbland.com/time-complexity-analysis-in-javascript/)
- 📜 [Algorithms in plain English: time complexity and Big-O Notation — Michael Olorunnisola](https://medium.freecodecamp.org/time-is-complex-but-priceless-f0abd015063c)
- 📜 [An Introduction to Big O Notation — Joseph Trettevik](https://dev.to/lofiandcode/an-introduction-to-big-o-notation-210o)

### Videos

- 🎥 [JavaScript: Intro to Big O Notation and Function Runtime — Eric Traub](https://www.youtube.com/watch?v=HgA5VOFan5E)
- 🎥 [Essential Big O for JavaScript Developers — Dave Smith](https://www.youtube.com/watch?v=KatlvCFHPRo)
- 🎥 [Big O Notation - Time Complexity Analysis — WebTunings](https://www.youtube.com/watch?v=ALl86xJiTD8)

**[⬆ Back to Top](#table-of-contents)**

---

## 29. Algorithms

### Articles

- 📜 [Data Structures and Algorithms using ES6](https://github.com/Crizstian/data-structure-and-algorithms-with-ES6)
- 📜 [Algorithms and data structures implemented in JavaScript with explanations and links to further readings](https://github.com/trekhleb/javascript-algorithms)
- 📜 [JS: Interview Algorithm](http://www.thatjsdude.com/interview/js1.html)
- 📜 [Algorithms in JavaScript — Thon Ly](https://medium.com/siliconwat/algorithms-in-javascript-b0bed68f4038)
- 📜 [JavaScript Objects, Square Brackets and Algorithms — Dmitri Grabov](https://medium.freecodecamp.org/javascript-objects-square-brackets-and-algorithms-e9a2916dc158)
- 📜 [Atwood's Law applied to CS101 - Classic algorithms and data structures implemented in JavaScript](https://github.com/felipernb/algorithms.js)
- 📜 [Data Structures and Algorithms library in JavaScript](https://github.com/yangshun/lago)
- 📜 [Collection of computer science algorithms and data structures written in JavaScript](https://github.com/idosela/algorithms-in-javascript)
- 📜 [Algorithms and Data Structures in JavaScript — Oleksii Trekhleb](https://dev.to/trekhleb/algorithms-and-data-structures-in-javascript-49i3)

**[⬆ Back to Top](#table-of-contents)**

---

## 30. Inheritance, Polymorphism and Code Reuse

### Reference

- 📜 [Inheritance in JavaScript — MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Inheritance)
- 📜 [Class inheritance, super — JavaScript.Info](https://javascript.info/class-inheritance)

### Articles

- 📜 [Inheritance in JavaScript — Rupesh Mishra](https://hackernoon.com/inheritance-in-javascript-21d2b82ffa6f)
- 📜 [Simple Inheritance with JavaScript — David Catuhe](https://www.sitepoint.com/simple-inheritance-javascript/)
- 📜 [JavaScript — Inheritance, delegation patterns and Object linking — NC Patro](https://codeburst.io/javascript-inheritance-25fe61ab9f85)
- 📜 [Object Oriented JavaScript: Polymorphism with examples — Knoldus Blogs](https://blog.knoldus.com/object-oriented-javascript-polymorphism-with-examples/)
- 📜 [Program Like Proteus — A beginner’s guide to polymorphism in Javascript — Sam Galson](https://medium.com/yld-engineering-blog/program-like-proteus-a-beginners-guide-to-polymorphism-in-javascript-867bea7c8be2)
- 📜 [Object-oriented JavaScript: A Deep Dive into ES6 Classes — Jeff Mott](https://www.sitepoint.com/object-oriented-javascript-deep-dive-es6-classes/)

### Videos

- 🎥 [Inheritance in JavaScript — kudvenkat](https://www.youtube.com/watch?v=yXlFR81tDBM)
- 🎥 [JavaScript ES6 Classes and Inheritance — Traversy Media](https://www.youtube.com/watch?v=RBLIm5LMrmc)
- 🎥 [Polymorphism in JavaScript — kudvenkat](https://www.youtube.com/watch?v=zdovG9cuEBA)

**[⬆ Back to Top](#table-of-contents)**

---

## 31. Design Patterns

### Books

- 📜 [Learning JavaScript Design Patterns — Addy Osmani ](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)

### Articles

- 📜 [4 JavaScript Design Patterns You Should Know — Devan Patel](https://scotch.io/bar-talk/4-javascript-design-patterns-you-should-know)
- 📜 [JavaScript Design Patterns – Beginner's Guide to Mobile Web Development — Soumyajit Pathak](https://medium.com/beginners-guide-to-mobile-web-development/javascript-design-patterns-25f0faaaa15)
- 📜 [JavaScript Design Patterns — Akash Pal](https://medium.com/front-end-hacking/javascript-design-patterns-ed9d4c144c81)
- 📜 [Javascript Design Patterns: What They Are & How To Use Them — Patrick Simpson](https://seesparkbox.com/foundry/javascript_design_patterns)
- 📜 [JavaScript Design Patterns: Understanding Design Patterns in JavaScript - Sukhjinder Arora](https://blog.bitsrc.io/understanding-design-patterns-in-javascript-13345223f2dd)
- 📜 [All the 23 (GoF) design patterns implemented in Javascript — Felipe Beline](https://github.com/fbeline/Design-Patterns-JS)
- 📜 [The Power of the Module Pattern in JavaScript — jsmanifest](https://medium.com/better-programming/the-power-of-the-module-pattern-in-javascript-3c73f7cd10e8)
- 📜 [Design Patterns for Developers using JavaScript pt. I — Oliver Mensah](https://dev.to/omensah/design-patterns-for-developers-using-javascript----part-one--b3e)
- 📜 [Design Patterns for Developers using JavaScript pt. II — Oliver Mensah](https://dev.to/omensah/design-patterns-for-developers-using-javascript---part-two--3p39)
- 📜 [Design patterns in modern JavaScript development](https://levelup.gitconnected.com/design-patterns-in-modern-javascript-development-ec84d8be06ca)
- 📜 [Understanding Design Patterns: Iterator using Dev.to and Medium social networks! — Carlos Caballero](https://dev.to/carlillo/understanding-design-patterns-iterator-using-dev-to-and-medium-social-networks-3bdd)
- 📜 [JavaScript Design Patterns - Factory Pattern — KristijanFištrek](https://dev.to/kristijanfistrek/javascript-design-patterns-factory-pattern-562p)
- 📜 [JavaScript Design Pattern — Module Pattern - Factory Pattern — Moon](https://medium.com/javascript-in-plain-english/javascript-design-pattern-module-pattern-555737eccecd)
- 📜 [Design Patterns: Null Object - Carlos Caballero](https://medium.com/better-programming/design-patterns-null-object-5ee839e37892)
- 📜 [Strategy Pattern - Francesco Ciulla](https://dev.to/francescoxx/strategy-pattern-5oh)
- 📜 [Adapter Pattern - Francesco Ciulla](https://dev.to/francescoxx/adapter-pattern-5bjk)
- 📜 [The Power of Composite Pattern in JavaScript - jsmanifest](https://dev.to/jsmanifest/the-power-of-composite-pattern-in-javascript-2732)
- 📜 [In Defense of Defensive Programming - Adam Nathaniel Davis](https://dev.to/bytebodger/in-defense-of-defensive-programming-k45)

### Videos

- 🎥 [JavaScript Design Patterns — Udacity](https://www.udacity.com/course/javascript-design-patterns--ud989)
- 🎥 [JavaScript Patterns for 2017 — Scott Allen](https://www.youtube.com/watch?v=hO7mzO83N1Q)

**[⬆ Back to Top](#table-of-contents)**

---

## 32. Partial Applications, Currying, Compose and Pipe

### Books

- 📜 [Functional-Light JavaScript: Ch. 3 - Managing Function Inputs — Kyle Simpson](https://github.com/getify/Functional-Light-JS/blob/master/manuscript/ch3.md)

### Articles

- 📜 [Use function composition in JavaScript — Rémi](https://www.codementor.io/michelre/use-function-composition-in-javascript-gkmxos5mj)
- 📜 [Currying in JavaScript ES6 — Adam Bene](https://blog.benestudio.co/currying-in-javascript-es6-540d2ad09400)
- 📜 [Composition and Currying Elegance in JavaScript — Pragyan Das](https://medium.com/@pragyan88/writing-middleware-composition-and-currying-elegance-in-javascript-8b15c98a541b)
- 📜 [Functional JavaScript: Function Composition For Every Day Use — Joel Thoms](https://hackernoon.com/javascript-functional-composition-for-every-day-use-22421ef65a10)
- 📜 [Functional Composition: compose() and pipe() — Anton Paras](https://medium.com/@acparas/what-i-learned-today-july-2-2017-ab9a46dbf85f)
- 📜 [Why The Hipsters Compose Everything: Functional Composing In JavaScript — A. Sharif](http://busypeoples.github.io/post/functional-composing-javascript/)
- 📜 [A Gentle Introduction to Functional JavaScript pt III: Functions for making functions — James Sinclair](https://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-functions/)
- 📜 [Curry And Compose (why you should be using something like ramda in your code) — jsanchesleao](https://jsleao.wordpress.com/2015/02/22/curry-and-compose-why-you-should-be-using-something-like-ramda-in-your-code/)
- 📜 [Function Composition in JavaScript with Pipe — Andy Van Slaars](https://vanslaars.io/post/create-pipe-function/)
- 📜 [Practical Functional JavaScript with Ramda — Andrew D'Amelio, Yuri Takhteyev](https://developer.telerik.com/featured/practical-functional-javascript-ramda/)
- 📜 [The beauty in Partial Application, Currying, and Function Composition — Joel Thoms](https://hackernoon.com/the-beauty-in-partial-application-currying-and-function-composition-d885bdf0d574)
- 📜 [Curry or Partial Application? — Eric Elliott](https://medium.com/javascript-scene/curry-or-partial-application-8150044c78b8)
- 📜 [Partial Application in JavaScript — Ben Alman](http://benalman.com/news/2012/09/partial-application-in-javascript/)
- 📜 [Partial Application of Functions — Functional Reactive Ninja](https://hackernoon.com/partial-application-of-functions-dbe7d9b80760)
- 📜 [Currying vs Partial Application — Deepak Gupta](https://codeburst.io/javascript-currying-vs-partial-application-4db5b2442be8)
- 📜 [Partial Application in ECMAScript 2015 — Ragan Wald](http://raganwald.com/2015/04/01/partial-application.html)
- 📜 [Functional Composition in Javascript — Joe Cortopassi](https://joecortopassi.com/articles/functional-composition-in-javascript/)
- 📜 [So You Want to be a Functional Programmer pt. I — Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536)
- 📜 [So You Want to be a Functional Programmer pt. II — Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-2-7005682cec4a)
- 📜 [So You Want to be a Functional Programmer pt. III — Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-3-1b0fd14eb1a7)
- 📜 [So You Want to be a Functional Programmer pt. IV — Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-4-18fbe3ea9e49)
- 📜 [So You Want to be a Functional Programmer pt. V — Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-5-c70adc9cf56a)
- 📜 [An introduction to the basic principles of Functional Programming — TK](https://medium.freecodecamp.org/an-introduction-to-the-basic-principles-of-functional-programming-a2c2a15c84)
- 📜 [Concepts of Functional Programming in Javascript — TK](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)
- 📜 [An Introduction to Functional Programming Style in JavaScript — JavaScript Teacher](https://medium.freecodecamp.org/an-introduction-to-functional-programming-style-in-javascript-71fcc050f064)
- 📜 [A practical guide to writing more functional JavaScript — Nadeesha Cabral](https://medium.freecodecamp.org/a-practical-guide-to-writing-more-functional-javascript-db49409f71)
- 📜 [A simple explanation of functional pipe in JavaScript — Ben Lesh](https://dev.to/benlesh/a-simple-explanation-of-functional-pipe-in-javascript-2hbj)

### Videos

- 🎥 [Compose vs Pipe: Functional Programming in JavaScript — Chyld Studios](https://www.youtube.com/watch?v=Wl2ejJOqHUU)
- 🎥 [JavaScript Functional Programing: Compose — Theodore Anderson](https://www.youtube.com/watch?v=jigHxo9YR30)
- 🎥 [Function Composition - Functional JavaScript — NWCalvank](https://www.youtube.com/watch?v=mth5WpEc4Qs)
- 🎥 [JavaScript Function Composition Explained — Theodore Anderson](https://www.youtube.com/watch?v=Uam37AlzPYw)
- 🎥 [Let's code with function composition — Fun Fun Function](https://www.youtube.com/watch?v=VGB9HbL1GHk)
- 🎥 [Partial Application vs. Currying — NWCalvank](https://www.youtube.com/watch?v=DzLkRsUN2vE)
- 🎥 [JavaScript Partial Application — Theodore Anderson](https://www.youtube.com/watch?v=jkebgHEcvac)

**[⬆ Back to Top](#table-of-contents)**

---

## 33. Clean Code

### Articles

- 📜 [Clean Code concepts adapted for JavaScript — Ryan McDermott](https://github.com/ryanmcdermott/clean-code-javascript)
- 📜 [JavaScript Clean Coding Best Practices — András Tóth](https://blog.risingstack.com/javascript-clean-coding-best-practices-node-js-at-scale/)
- 📜 [Function parameters in JavaScript Clean Code — Kevin Peters](https://medium.com/@kevin_peters/function-parameters-in-javascript-clean-code-4caac109159b)
- 📜 [Keeping your code clean — Samuel James](https://codeburst.io/keeping-your-code-clean-d30bcffd1a10)
- 📜 [Best Practices for Using Modern JavaScript Syntax — M. David Green](https://www.sitepoint.com/modern-javascript-best-practices/)
- 📜 [best practices for cross node/web development - Jimmy Wärting](https://github.com/cross-js/cross-js)
- 📜 [Writing Clean Code - Dylan Paulus](https://dev.to/ganderzz/on-writing-clean-code-57cm)
- 📜 [Writing Clean Code and The Practice of Programming - Nityesh Agarwal](https://dev.to/nityeshaga/writing-clean-code-and-the-practice-of-programming-actionable-advice-for-beginners-5f0k)
- 📜 [Clean code, dirty code, human code - Daniel Irvine](https://dev.to/d_ir/clean-code-dirty-code-human-code-6nm)
- 📜 [Practical Ways to Write Better JavaScript - Ryland G](https://dev.to/taillogs/practical-ways-to-write-better-javascript-26d4)

### Videos

- 🎥 [JavaScript Pro Tips - Code This, NOT That](https://www.youtube.com/watch?v=Mus_vwhTCq0)
- 🎥 [Clean Code: Functions(Part 1) - Beau teaches](https://www.youtube.com/watch?v=RR_dQ4sBSBM)

**[⬆ Back to Top](#table-of-contents)**
