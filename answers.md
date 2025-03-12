
## About You

1. Introduce Yourself
My name is Anjana George, and I am from Kothamangalam. I hold a B.Com in Computer Applications from Yeldo Mar Baselios College, Kothamangalam.

I started my journey as a Full-Stack Developer Intern at Eduzell Technologies & Solutions LLP, where I worked with React, Laravel, and MySQL. I have hands-on experience in backend development using Laravel 11 and MySQL, and frontend development with React.js, HTML, CSS, and JavaScript, Bootsrap, Tailwind css.

I am passionate about building scalable applications, optimizing performance, and continuously improving my coding skills. I am eager to continuously learn and take on new challenges in software development.


2. Describe Your Development Environment

Operating System: Windows 11
IDE & Tools: VS Code, XAMPP
Editor: VS Code
Config Manager: Git for version control
Installed Tools: Node.js, XAMPP, Composer, VS Code

3. Which Programming Languages Are Installed on Your System?

PHP (via XAMPP, used with Laravel)
JavaScript (Node.js, React.js – Frontend & Backend)
MySQL (via XAMPP)
C / C++

4. Programming Languages I Am Interested in Learning

I am always open to learning new languages based on industry needs and company requirements. Currently, I am particularly interested in:

Python – Useful for backend development,automation, and AI/ML.

Angular – A powerful front-end framework for building dynamic web applications.

Go – High-performance language for backend and cloud applications.



## Social Profile

1. GitHub Profile
  https://github.com/Anjana7581

2. LinkedIn Profile
  https://www.linkedin.com/in/anjana-george-126b97280/



## The Real Stuff.

1. 
    <?php

    function numberToDigits($num) {
        return array_map('intval', str_split($num));
    }

    $number = 12345;
    $result = numberToDigits($number);

    echo "Digits of {$number}:\n";
    print_r($result);

    ?>



 2.    
    <?php

    function toPigLatin($text) {
        $words = explode(' ', $text);
        $translatedWords = [];

        foreach ($words as $word) {
            $firstLetter = substr($word, 0, 1);
            $restOfWord = substr($word, 1);
            $translatedWords[] = $restOfWord . $firstLetter . 'ay';
        }

        return implode(' ', $translatedWords);
    }

    function fromPigLatin($text) {
        $words = explode(' ', $text);
        $originalWords = [];

        foreach ($words as $word) {
            $wordWithoutAy = substr($word, 0, -2); 
            $lastLetter = substr($wordWithoutAy, -1);
            $restOfWord = substr($wordWithoutAy, 0, -1);
            $originalWords[] = $lastLetter . $restOfWord;
        }

        return implode(' ', $originalWords);
    }

    $englishText = "have a great day";
    $pigLatin = toPigLatin($englishText);
    $translatedBack = fromPigLatin($pigLatin);

    echo "Original: $englishText\n";
    echo "Pig Latin: $pigLatin\n";
    echo "Back to English: $translatedBack\n";

    ?>

