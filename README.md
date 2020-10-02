<h1 align="center">Learn Programming Free</h1>
<h3 align="center">About List of best free programming resources on the internet</h3>

## About 
You can find free reasources to learn programming
 - courses
 - blogs
 - books 
 - youtube playlist

## Supported Platforms

* Android
* iOS
* Web [http://learnprogrammingfree.codingboy.in/](http://learnprogrammingfree.codingboy.in/)

#### How to use the app locally on your machine ?

<u>Requirements</u>

1. Flutter installed on your machine.
2. A simulator/emulator for running the application.

**Step #1** : Clone this repository using 

``` git clone https://github.com/viralvaghela/learnprogrammingfree.git ```

**Step #2** : move the directory

``` cd learnprogrammingfree```

**Step #3** : Run the following command in the directory

``` flutter packages get```

**Step #4**: Open a simulator / emulator and run the application

``` flutter run```

# Contributing

Thank you for considering and taking the time to contribute to this project!

## Download & install

First, clone the repository with the 'clone' command, or just download the zip.

```
$ git clone https://github.com/viralvaghela/learnprogrammingfree.git
```

Now, you can add books,videos,blogs etc in the resources/json.data 
```json
 {
        "id": 1,
        "name": "Flutter Complete Beginner Course",
        "instructor": "Mtechviral",
        "url": "https://www.youtube.com/watch?v=6wQwnTIBD1Y",
        "description": "Flutter complete beginner course by Mtechviral",
        "image": "http://learnprogrammingfree.codingboy.in/resources/images/flutter.png",
        "tags": [
            "flutter",
            "mobile development"
        ]
  }
```

if you have image file then upload inside resources/images/ and write image address in json.data and dont forget to increment the id when you add new data.

## How to Report Bugs and Request Feature

Please open [a new issue in the GitHub repository](https://github.com/viralvaghela/learnprogrammingfree/issues) with steps to reproduce the problem you're experiencing.

Be sure to include as much information including screenshots, text output, and both your expected and actual results.