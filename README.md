- 👋 Hi, I’m @monishthiru
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
<html><head>
    <title>Index</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #293462;
            color: #040D12;
            margin: 0;
            padding: 0;
        }

        h1 {
            text-align: center;
            margin-top: 20px;
            color: #F6F1F1;
            animation: fadeIn 1s;
        }

        h2, h3 {
            text-align: center;
            margin: 10px auto;
            color: #F6F1F1;
            animation: fadeIn 1s;
        }

        #questionnaireForm {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            animation: fadeIn 1s;
        }

        .question {
            margin-bottom: 20px;
        }

        .answer {
            display: flex;
            align-items: center;
            margin-top: 5px;
        }

        .answer input[type="radio"] {
            margin-right: 5px;
        }

        input[type="submit"] {
            display: block;
            margin: 20px auto 0;
            padding: 10px 20px;
            background-color: #428bca;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            animation: fadeIn 1s;
        }

        #results {
            text-align: center;
            font-size: 18px;
            font-weight: bold;
            margin-top: 20px;
            display: none;
            animation: fadeIn 1s;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        /* Colorful pop effect for the questionnaire */
        .questionnaire-pop {
            animation: pop 0.5s;
        }

        @keyframes pop {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }
    </style>
</head>
<body>
    <h1>Autism Questionnaire</h1><style>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>


<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjAnobqiI_TmkC6GLw-UrklLwLL8cE1A8kjQ&amp;usqp=CAU" alt="paris" class="center" width="150" height="150">


    <h2>Parents are kindly requested to answer the following questions regarding their child's behaviour</h2>
    <form id="questionnaireForm" onsubmit="return calculateScore()" class="questionnaire-pop">
        <!-- Question 1 -->
       <div class="question">
        <label for="q1">1. Does s/he join in playing games with other children easily?</label>
        <div class="answer">
            <input type="radio" name="q1" value="0" id="q1_yes" required="">
            <label for="q1_yes">Yes</label>
            <input type="radio" name="q1" value="1" id="q1_no">
            <label for="q1_no">No</label>
        </div>
    </div>

    <!-- Question 2 -->
    <div class="question">
        <label for="q2">2. Does s/he come up to you spontaneously for a chat?</label>
        <div class="answer">
            <input type="radio" name="q2" value="0" id="q2_yes" required="">
            <label for="q2_yes">Yes</label>
            <input type="radio" name="q2" value="1" id="q2_no">
            <label for="q2_no">No</label>
        </div>
    </div>

    <!-- Question 3 -->
    <div class="question">
        <label for="q3">3. Was s/he speaking by 2 years old?</label>
        <div class="answer">
            <input type="radio" name="q3" value="0" id="q3_yes" required="">
            <label for="q3_yes">Yes</label>
            <input type="radio" name="q3" value="0" id="q3_no">
            <label for="q3_no">No</label>
        </div>
    </div>

    <!-- Question 4 -->
    <div class="question">
        <label for="q4">4. Does s/he enjoy sports?</label>
        <div class="answer">
            <input type="radio" name="q4" value="0" id="q4_yes" required="">
            <label for="q4_yes">Yes</label>
            <input type="radio" name="q4" value="0" id="q4_no">
            <label for="q4_no">No</label>
        </div>
    </div>

    <!-- Question 5 -->
    <div class="question">
        <label for="q5">5. Is it important to him/her to fit in with the peer group?</label>
        <div class="answer">
            <input type="radio" name="q5" value="0" id="q5_yes" required="">
            <label for="q5_yes">Yes</label>
            <input type="radio" name="q5" value="1" id="q5_no">
            <label for="q5_no">No</label>
        </div>
    </div>

    <!-- Question 6 -->
    <div class="question">
        <label for="q6">6. Does s/he appear to notice unusual details that others miss?</label>
        <div class="answer">
            <input type="radio" name="q6" value="1" id="q6_yes" required="">
            <label for="q6_yes">Yes</label>
            <input type="radio" name="q6" value="0" id="q6_no">
            <label for="q6_no">No</label>
        </div>
    </div>

    <!-- Question 7 -->
    <div class="question">
        <label for="q7">7. Does s/he tend to take things literally?</label>
        <div class="answer">
            <input type="radio" name="q7" value="1" id="q7_yes" required="">
            <label for="q7_yes">Yes</label>
            <input type="radio" name="q7" value="0" id="q7_no">
            <label for="q7_no">No</label>
        </div>
    </div>

    <!-- Question 8 -->
    <div class="question">
        <label for="q8">8. When s/he was 3 years old, did s/he spend a lot of time pretending (e.g., play-acting being a superhero, or holding teddy's tea parties)?</label>
        <div class="answer">
            <input type="radio" name="q8" value="0" id="q8_yes" required="">
            <label for="q8_yes">Yes</label>
            <input type="radio" name="q8" value="1" id="q8_no">
            <label for="q8_no">No</label>
        </div>
    </div>

    <!-- Question 9 -->
    <div class="question">
        <label for="q9">9. Does s/he like to do things over and over again, in the same way all the time?</label>
        <div class="answer">
            <input type="radio" name="q9" value="1" id="q9_yes" required="">
            <label for="q9_yes">Yes</label>
            <input type="radio" name="q9" value="0" id="q9_no">
            <label for="q9_no">No</label>
        </div>
    </div>

    <!-- Question 10 -->
    <div class="question">
        <label for="q10">10. Does s/he find it easy to interact with other children?</label>
        <div class="answer">
            <input type="radio" name="q10" value="0" id="q10_yes" required="">
            <label for="q10_yes">Yes</label>
            <input type="radio" name="q10" value="1" id="q10_no">
            <label for="q10_no">No</label>
        </div>
    </div>

    <!-- Question 11-->
    <div class="question">
        <label for="q11">11. Can s/he keep a two-way conversation going?</label>
        <div class="answer">
            <input type="radio" name="q11" value="0" id="q11_yes" required="">
            <label for="q11_yes">Yes</label>
            <input type="radio" name="q11" value="1" id="q11_no">
            <label for="q11_no">No</label>
        </div>
    </div>

    <!-- Question 12 -->
    <div class="question">
        <label for="q12">12. Can s/he read appropriately for his/her age?</label>
        <div class="answer">
            <input type="radio" name="q12" value="0" id="q12_yes" required="">
            <label for="q12_yes">Yes</label>
            <input type="radio" name="q12" value="0" id="q12_no">
            <label for="q12_no">No</label>
        </div>
    </div>

    <!-- Question 13-->
    <div class="question">
        <label for="q13">13. Does s/he mostly have the same interests as his/her peers?</label>
        <div class="answer">
            <input type="radio" name="q13" value="0" id="q13_yes" required="">
            <label for="q13_yes">Yes</label>
            <input type="radio" name="q13" value="1" id="q13_no">
            <label for="q13_no">No</label>
        </div>
    </div>

    <!-- Question 14-->
    <div class="question">
        <label for="q14">14. Does s/he have an interest which takes up so much time that s/he does little else?</label>
        <div class="answer">
            <input type="radio" name="q14" value="1" id="q14_yes" required="">
            <label for="q14_yes">Yes</label>
            <input type="radio" name="q14" value="0" id="q14_no">
            <label for="q14_no">No</label>
        </div>
    </div>

    <!-- Question 15-->
    <div class="question">
        <label for="q15">15. Does s/he have friends, rather than just acquaintances?</label>
        <div class="answer">
            <input type="radio" name="q15" value="0" id="q15_yes" required="">
            <label for="q15_yes">Yes</label>
            <input type="radio" name="q15" value="1" id="q15_no">
            <label for="q15_no">No</label>
        </div>
    </div>

    <!-- Question 16-->
    <div class="question">
        <label for="q16">16.  Does s/he often bring you things s/he is interested in to show you?</label>
        <div class="answer">
            <input type="radio" name="q16" value="0" id="q16_yes" required="">
            <label for="q16_yes">Yes</label>
            <input type="radio" name="q16" value="1" id="q16_no">
            <label for="q16_no">No</label>
        </div>
    </div>

    <!-- Question 17-->
    <div class="question">
        <label for="q17">17. Does s/he enjoy joking around?</label>
        <div class="answer">
            <input type="radio" name="q17" value="0" id="q17_yes" required="">
            <label for="q17_yes">Yes</label>
            <input type="radio" name="q17" value="1" id="q17_no">
            <label for="q17_no">No</label>
        </div>
    </div>

    <!-- Question 18-->
    <div class="question">
        <label for="q18">18. Does s/he have difficulty understanding the rules for polite behavior?</label>
        <div class="answer">
            <input type="radio" name="q18" value="1" id="q18_yes" required="">
            <label for="q18_yes">Yes</label>
            <input type="radio" name="q18" value="0" id="q18_no">
            <label for="q18_no">No</label>
        </div>
    </div>

    <!-- Question 19-->
    <div class="question">
        <label for="q19">19. Does s/he appear to have an unusual memory for details?</label>
        <div class="answer">
            <input type="radio" name="q19" value="1" id="q19_yes" required="">
            <label for="q19_yes">Yes</label>
            <input type="radio" name="q19" value="0" id="q19_no">
            <label for="q19_no">No</label>
        </div>
    </div>

    <!-- Question 20-->
    <div class="question">
        <label for="q20">20. Is his/her voice unusual (e.g., overly adult, flat, or very monotonous)?</label>
        <div class="answer">
            <input type="radio" name="q20" value="1" id="q20_yes" required="">
            <label for="q20_yes">Yes</label>
            <input type="radio" name="q20" value="0" id="q20_no">
            <label for="q20_no">No</label>
        </div>
    </div>

    <!-- Question 21-->
    <div class="question">
        <label for="q21">21.Are people important to him/her?</label>
        <div class="answer">
            <input type="radio" name="q21" value="0" id="q21_yes" required="">
            <label for="q21_yes">Yes</label>
            <input type="radio" name="q21" value="1" id="q21_no">
            <label for="q21_no">No</label>
        </div>
    </div>

    <!-- Question 22-->
    <div class="question">
        <label for="q22">22. Can s/he dress him/herself?</label>
        <div class="answer">
            <input type="radio" name="q22" value="0" id="q22_yes" required="">
            <label for="q22_yes">Yes</label>
            <input type="radio" name="q22" value="0" id="q22_no">
            <label for="q22_no">No</label>
        </div>
    </div>

    <!-- Question 23-->
    <div class="question">
        <label for="q23">23. Does s/he sometimes lose the listener because of not explaining what s/he is talking about?</label>
        <div class="answer">
            <input type="radio" name="q23" value="1" id="q23_yes" required="">
            <label for="q23_yes">Yes</label>
            <input type="radio" name="q23" value="0" id="q23_no">
            <label for="q23_no">No</label>
        </div>
    </div>

    <!-- Question 24-->
    <div class="question">
        <label for="q24">24. Does s/he play imaginatively with other children, and engage in role-play?</label>
        <div class="answer">
            <input type="radio" name="q24" value="0" id="q24_yes" required="">
            <label for="q24_yes">Yes</label>
            <input type="radio" name="q24" value="1" id="q24_no">
            <label for="q24_no">No</label>
        </div>
    </div>

    <!-- Question 25-->
    <div class="question">
        <label for="q25">25. Does s/he often do or say things that are tactless or socially inappropriate?</label>
        <div class="answer">
            <input type="radio" name="q25" value="1" id="q25_yes" required="">
            <label for="q25_yes">Yes</label>
            <input type="radio" name="q25" value="0" id="q25_no">
            <label for="q25_no">No</label>
        </div>
    </div>

    <!-- Question 26-->
    <div class="question">
        <label for="q26">26. Can s/he count to 50 without leaving out any numbers?</label>
        <div class="answer">
            <input type="radio" name="q26" value="0" id="q26_yes" required="">
            <label for="q26_yes">Yes</label>
            <input type="radio" name="q26" value="0" id="q26_no">
            <label for="q26_no">No</label>
        </div>
    </div>

    <!-- Question 27-->
    <div class="question">
        <label for="q27">27. Does s/he try to impose routines on him/herself, or on others, in such a way that it causes problems?</label>
        <div class="answer">
            <input type="radio" name="q27" value="1" id="q27_yes" required="">
            <label for="q27_yes">Yes</label>
            <input type="radio" name="q27" value="0" id="q27_no">
            <label for="q27_no">No</label>
        </div>
    </div>

    <!-- Question 28-->
    <div class="question">
        <label for="q28">28. Does s/he have any unusual and repetitive movements?</label>
        <div class="answer">
            <input type="radio" name="q28" value="1" id="q28_yes" required="">
            <label for="q28_yes">Yes</label>
            <input type="radio" name="q28" value="0" id="q28_no">
            <label for="q28_no">No</label>
        </div>
    </div>

    <!-- Question 29-->
    <div class="question">
        <label for="q29">29. Have teachers/health visitors ever expressed any concerns about his/her development?</label>
        <div class="answer">
            <input type="radio" name="q29" value="0" id="q29_yes" required="">
            <label for="q29_yes">Yes</label>
            <input type="radio" name="q29" value="0" id="q29_no">
            <label for="q29_no">No</label>
        </div>
    </div>

    <!-- Question 30-->
    <div class="question">
        <label for="q30">30. Does s/he sometimes say “you” or “s/he” when s/he means “I”?</label>
        <div class="answer">
            <input type="radio" name="q30" value="1" id="q30_yes" required="">
            <label for="q30_yes">Yes</label>
            <input type="radio" name="q30" value="0" id="q30_no">
            <label for="q30_no">No</label>
        </div>
    </div>
        <input type="submit" class="center" value="Submit">
    </form>
    <div id="results"></div>
    
    <script>
        function calculateScore() {
            const formData = new FormData(document.getElementById("questionnaireForm"));
            let score = 0;

            formData.forEach((value, key) => {
                const answerValue = parseInt(value);
                score += answerValue;
            });

            // Redirect to the speedometer page and pass the score as a parameter
            window.location.href = `score.html?score=${score}`;

            return false; 
            // Prevent the form from actually submitting and refreshing the page
        }
    </script>


</body></html>
