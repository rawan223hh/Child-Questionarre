<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Child Element Quiz</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; text-align: center; background-color: #f8f9fa; }
        .container { max-width: 700px; margin: auto; background: white; padding: 20px; border-radius: 10px; box-shadow: 0px 0px 10px #ccc; }
        .question { margin-bottom: 15px; text-align: left; }
        h2 { color: #4CAF50; }
        .result { display: none; margin-top: 20px; font-weight: bold; padding: 15px; border-radius: 10px; background: #ffebcd; text-align: left; }
        .btn { background: #4CAF50; color: white; border: none; padding: 10px 15px; cursor: pointer; border-radius: 5px; }
        img { width: 150px; display: block; margin: auto; margin-bottom: 20px; }
    </style>
</head>
<body>

<!-- Spectra Cure Clinic Logo -->
<img src="YOUR_IMAGE_URL_HERE" alt="Spectra Cure Clinic Logo">

<div class="container">
    <h2>Child Element Personality Quiz</h2>
    <form id="quiz-form">
        <div id="questions"></div>
        <button type="submit" class="btn">Get Results / احصل على النتائج</button>
    </form>
    <div class="result" id="result"></div>
</div>

<script>
    const questions = {
        "Wood": [
            ["Does your child enjoy trying new things and taking on challenges?", "هل يحب طفلك تجربة أشياء جديدة وخوض التحديات؟"],
            ["Does your child love movement and physical activities?", "هل يحب طفلك الأنشطة البدنية والحركة؟"]
        ],
        "Fire": [
            ["Does your child love being around people and enjoy attention?", "هل يحب طفلك أن يكون بين الناس ويستمتع بالاهتمام؟"],
            ["Does your child have a playful and energetic personality?", "هل يتمتع طفلك بشخصية مرحة ومليئة بالطاقة؟"]
        ],
        "Earth": [
            ["Is your child caring and thoughtful towards others?", "هل طفلك عطوف ويهتم بالآخرين؟"],
            ["Does your child prefer working in groups rather than alone?", "هل يفضل طفلك العمل في مجموعات بدلًا من العمل منفردًا؟"]
        ],
        "Metal": [
            ["Does your child like having a routine and dislike surprises?", "هل يحب طفلك الروتين ويكره المفاجآت؟"],
            ["Is your child detail-oriented and organized?", "هل طفلك دقيق ومنظم؟"]
        ],
        "Water": [
            ["Does your child have a big imagination and love to dream?", "هل لدى طفلك خيال واسع ويحب الأحلام؟"],
            ["Does your child prefer quiet, peaceful environments?", "هل يفضل طفلك البيئات الهادئة والمسالمة؟"]
        ]
    };

    const resultsData = {
        "Wood": {
            "traits": "Energetic, curious, strong-willed, quick to act.",
            "encouragement": "Encourage activities like hiking, martial arts, and hands-on learning.",
            "careers": "Entrepreneur, emergency responder, doctor, lawyer, artist."
        },
        "Fire": {
            "traits": "Excitable, social, playful, optimistic.",
            "encouragement": "Use team sports, role-playing, and creative arts like dance and acting.",
            "careers": "Teacher, journalist, chef, musician, daycare worker."
        },
        "Earth": {
            "traits": "Caring, kind, thoughtful, loves teamwork.",
            "encouragement": "Encourage group activities, storytelling, and structured routines.",
            "careers": "Teacher, social worker, nurse, artist."
        },
        "Metal": {
            "traits": "Organized, careful, detail-oriented.",
            "encouragement": "Provide structured schedules, problem-solving games, and hands-on crafts.",
            "careers": "Engineer, accountant, scientist, architect."
        },
        "Water": {
            "traits": "Imaginative, quiet, reflective, loves deep thinking.",
            "encouragement": "Encourage writing, drawing, and solo creative projects.",
            "careers": "Writer, psychologist, artist, researcher."
        }
    };

    function createQuiz() {
        const quizContainer = document.getElementById("questions");
        for (let element in questions) {
            const header = document.createElement("h3");
            header.textContent = element + " Element / عنصر " + element;
            quizContainer.appendChild(header);

            questions[element].forEach((q, index) => {
                const questionDiv = document.createElement("div");
                questionDiv.classList.add("question");
                questionDiv.innerHTML = `
                    <label>${q[0]}<br><strong>${q[1]}</strong></label><br>
                    <input type="radio" name="${element}-${index}" value="1" required> 1 (Rarely) / نادرًا
                    <input type="radio" name="${element}-${index}" value="2"> 2 (Sometimes) / أحيانًا
                    <input type="radio" name="${element}-${index}" value="3"> 3 (Very Often) / غالبًا
                `;
                quizContainer.appendChild(questionDiv);
            });
        }
    }

    function calculateResults(event) {
        event.preventDefault();

        let scores = { Wood: 0, Fire: 0, Earth: 0, Metal: 0, Water: 0 };

        const formData = new FormData(event.target);
        for (let [key, value] of formData.entries()) {
            const element = key.split("-")[0];
            scores[element] += parseInt(value);
        }

        const highestElement = Object.keys(scores).reduce((a, b) => (scores[a] > scores[b] ? a : b));

        const resultDiv = document.getElementById("result");
        resultDiv.innerHTML = `
            <h3>Dominant Element: ${highestElement} / العنصر المسيطر: ${highestElement}</h3>
            <p><strong>Traits:</strong> ${resultsData[highestElement].traits}</p>
            <p><strong>Encouragement:</strong> ${resultsData[highestElement].encouragement}</p>
            <p><strong>Potential Careers:</strong> ${resultsData[highestElement].careers}</p>
        `;
        resultDiv.style.display = "block";
    }

    document.getElementById("quiz-form").addEventListener("submit", calculateResults);
    createQuiz();
</script>

</body>
</html>
