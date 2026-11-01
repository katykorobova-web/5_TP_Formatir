<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Тест: Текстовый процессор. Форматирование</title>
    <style>
        /* CSS переменные */
        :root {
            --primary: #2563eb;
            --primary-hover: #1d4ed8;
            --success: #10b981;
            --error: #ef4444;
            --text: #1f2937;
            --text-light: #6b7280;
            --bg: #ffffff;
            --bg-secondary: #f3f4f6;
            --border: #e5e7eb;
            --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        }

        /* Сброс и базовые стили */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background: var(--bg-secondary);
            color: var(--text);
            line-height: 1.6;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        /* Контейнер приложения */
        #app {
            width: 100%;
            max-width: 600px;
        }

        /* Карточка */
        .card {
            background: var(--bg);
            border-radius: 12px;
            padding: 32px;
            box-shadow: var(--shadow);
        }

        /* Заголовки */
        h1 {
            font-size: 1.75rem;
            margin-bottom: 16px;
            color: var(--text);
        }

        h2 {
            font-size: 1.25rem;
            margin-bottom: 12px;
            color: var(--text);
        }

        /* Текст */
        p {
            margin-bottom: 16px;
            color: var(--text-light);
        }

        /* Кнопки */
        button {
            width: 100%;
            padding: 14px 24px;
            font-size: 1rem;
            font-weight: 600;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.2s;
            min-height: 44px;
        }

        button:focus-visible {
            outline: 3px solid var(--primary);
            outline-offset: 2px;
        }

        .btn-primary {
            background: var(--primary);
            color: white;
        }

        .btn-primary:hover {
            background: var(--primary-hover);
        }

        .btn-primary:disabled {
            background: var(--text-light);
            cursor: not-allowed;
        }

        /* Варианты ответов */
        .options {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin: 24px 0;
        }

        .option {
            padding: 16px;
            background: var(--bg-secondary);
            border: 2px solid var(--border);
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.2s;
            text-align: left;
            font-size: 1rem;
            min-height: 44px;
        }

        .option:hover:not(:disabled) {
            border-color: var(--primary);
            background: #eff6ff;
        }

        .option.selected {
            border-color: var(--primary);
            background: #dbeafe;
        }

        .option.correct {
            border-color: var(--success);
            background: #d1fae5;
        }

        .option.incorrect {
            border-color: var(--error);
            background: #fee2e2;
        }

        .option:disabled {
            cursor: not-allowed;
        }

        /* Прогресс */
        .progress {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 24px;
            padding-bottom: 16px;
            border-bottom: 1px solid var(--border);
        }

        .progress-text {
            font-size: 0.875rem;
            color: var(--text-light);
            font-weight: 600;
        }

        /* Объяснение */
        .explanation {
            margin-top: 20px;
            padding: 16px;
            background: #eff6ff;
            border-left: 4px solid var(--primary);
            border-radius: 4px;
        }

        .explanation-title {
            font-weight: 600;
            color: var(--primary);
            margin-bottom: 8px;
        }

        .explanation-text {
            color: var(--text);
            font-size: 0.95rem;
        }

        /* Результат */
        .result-score {
            font-size: 3rem;
            font-weight: 700;
            color: var(--primary);
            text-align: center;
            margin: 24px 0;
        }

        .result-message {
            text-align: center;
            font-size: 1.125rem;
            margin-bottom: 24px;
            color: var(--text);
        }

        /* Адаптивность */
        @media (max-width: 480px) {
            .card {
                padding: 24px 20px;
            }

            h1 {
                font-size: 1.5rem;
            }

            .result-score {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>
    <main id="app" role="main"></main>

    <script>
        // Константы: вопросы теста
        const QUESTIONS = [
            {
                question: "Что такое текстовый процессор?",
                options: [
                    "Простой редактор для набора текста",
                    "Текстовый редактор с расширенными возможностями по созданию документов",
                    "Программа для рисования",
                    "Калькулятор"
                ],
                correct: 1,
                explanation: "Текстовый процессор — это текстовый редактор с расширенными возможностями: вставка изображений, таблиц, схем, формул, графиков."
            },
            {
                question: "Что такое форматирование?",
                options: [
                    "Удаление текста из документа",
                    "Копирование текста",
                    "Этап подготовки документа, в ходе которого совершаются операции по оформлению",
                    "Печать документа"
                ],
                correct: 2,
                explanation: "Форматирование — это один из этапов подготовки документа, в ходе которого совершаются различные операции по оформлению документа."
            },
            {
                question: "Что НЕ относится к форматированию символов (шрифта)?",
                options: [
                    "Выбор гарнитуры",
                    "Изменение размера шрифта",
                    "Выравнивание абзаца",
                    "Изменение цвета текста"
                ],
                correct: 2,
                explanation: "Выравнивание абзаца относится к форматированию абзацев, а не символов. К форматированию символов относятся: гарнитура, размер, начертание, цвет."
            },
            {
                question: "Что такое гарнитура шрифта?",
                options: [
                    "Размер букв",
                    "Вид самих букв, цифр и знаков",
                    "Цвет текста",
                    "Расстояние между строками"
                ],
                correct: 1,
                explanation: "Гарнитура — это вид самих букв, цифр и знаков. Разные гарнитуры имеют разный дизайн букв."
            },
            {
                question: "Какой размер шрифта крупнее?",
                options: [
                    "12",
                    "14",
                    "10",
                    "8"
                ],
                correct: 1,
                explanation: "Размер шрифта (кегль) измеряется в пунктах. Чем больше число, тем крупнее текст. 14 пунктов крупнее 12, 10 и 8."
            },
            {
                question: "Какое начертание обозначается буквой «Ж»?",
                options: [
                    "Курсивное",
                    "Подчёркнутое",
                    "Полужирное",
                    "Зачёркнутое"
                ],
                correct: 2,
                explanation: "Буква «Ж» обозначает полужирное начертание. «К» — курсивное, «Ч» — подчёркнутое."
            },
            {
                question: "Что такое выравнивание по ширине?",
                options: [
                    "Текст прижат к левому краю",
                    "Текст расположен по центру",
                    "Текст распределяется равномерно между обоими краями",
                    "Текст прижат к правому краю"
                ],
                correct: 2,
                explanation: "При выравнивании по ширине текст распределяется равномерно — оба края ровные."
            },
            {
                question: "Для чего используется межстрочный интервал?",
                options: [
                    "Для изменения цвета текста",
                    "Для настройки расстояния по вертикали между строками",
                    "Для выбора гарнитуры",
                    "Для создания списков"
                ],
                correct: 1,
                explanation: "Межстрочный интервал — это расстояние по вертикали между строками текста."
            },
            {
                question: "Какое выравнивание чаще используют для заголовков?",
                options: [
                    "По левому краю",
                    "По правому краю",
                    "По центру",
                    "По ширине"
                ],
                correct: 2,
                explanation: "Заголовки чаще всего выравнивают по центру для лучшего визуального восприятия."
            },
            {
                question: "Что можно вставить в документ с помощью текстового процессора?",
                options: [
                    "Только текст",
                    "Изображения, таблицы, схемы, формулы, графики",
                    "Только изображения",
                    "Только таблицы"
                ],
                correct: 1,
                explanation: "Текстовый процессор позволяет вставлять изображения, таблицы, схемы, формулы, графики и другие объекты."
            }
        ];

        // Состояние приложения
        const state = {
            screen: 'start', // start, quiz, result
            currentQuestion: 0,
            selectedAnswer: null,
            score: 0,
            answered: false
        };

        // Рендер экрана старта
        function renderStart() {
            return `
                <div class="card">
                    <h1>Текстовый процессор. Форматирование</h1>
                    <p>Интерактивный тест по информатике для 5 класса</p>
                    <p>В тесте 10 вопросов. После каждого ответа вы получите объяснение.</p>
                    <button class="btn-primary" onclick="startQuiz()">Начать тест</button>
                </div>
            `;
        }

        // Рендер вопроса
        function renderQuestion() {
            const q = QUESTIONS[state.currentQuestion];
            const questionNum = state.currentQuestion + 1;
            
            let optionsHTML = '';
            q.options.forEach((option, index) => {
                let optionClass = 'option';
                let disabled = '';
                
                if (state.answered) {
                    disabled = 'disabled';
                    if (index === q.correct) {
                        optionClass += ' correct';
                    } else if (index === state.selectedAnswer && index !== q.correct) {
                        optionClass += ' incorrect';
                    }
                } else if (state.selectedAnswer === index) {
                    optionClass += ' selected';
                }
                
                optionsHTML += `
                    <button 
                        class="${optionClass}" 
                        onclick="selectAnswer(${index})"
                        ${disabled}
                        aria-label="Вариант ${index + 1}: ${option}"
                    >${option}</button>
                `;
            });

            let explanationHTML = '';
            if (state.answered) {
                explanationHTML = `
                    <div class="explanation">
                        <div class="explanation-title">Объяснение:</div>
                        <div class="explanation-text">${q.explanation}</div>
                    </div>
                    <button class="btn-primary" onclick="nextQuestion()" style="margin-top: 16px;">
                        ${state.currentQuestion < QUESTIONS.length - 1 ? 'Следующий вопрос' : 'Показать результат'}
                    </button>
                `;
            } else {
                explanationHTML = `
                    <button 
                        class="btn-primary" 
                        onclick="checkAnswer()" 
                        ${state.selectedAnswer === null ? 'disabled' : ''}
                    >Проверить ответ</button>
                `;
            }

            return `
                <div class="card">
                    <div class="progress">
                        <span class="progress-text">Вопрос ${questionNum} из ${QUESTIONS.length}</span>
                        <span class="progress-text">Баллы: ${state.score}</span>
                    </div>
                    <h2>${q.question}</h2>
                    <div class="options" role="radiogroup">
                        ${optionsHTML}
                    </div>
                    ${explanationHTML}
                </div>
            `;
        }

        // Рендер экрана результата
        function renderResult() {
            const percentage = Math.round((state.score / QUESTIONS.length) * 100);
            let message = '';
            
            if (percentage === 100) {
                message = 'Отлично! Вы знаете всё!';
            } else if (percentage >= 80) {
                message = 'Хороший результат!';
            } else if (percentage >= 60) {
                message = 'Неплохо, но есть над чем поработать.';
            } else {
                message = 'Рекомендуем повторить тему.';
            }

            return `
                <div class="card">
                    <h1>Результат теста</h1>
                    <div class="result-score">${state.score} / ${QUESTIONS.length}</div>
                    <div class="result-message">${message}</div>
                    <p style="text-align: center;">Правильных ответов: ${percentage}%</p>
                    <button class="btn-primary" onclick="restartQuiz()" style="margin-top: 24px;">Пройти снова</button>
                </div>
            `;
        }

        // Основная функция рендеринга
        function render() {
            const app = document.getElementById('app');
            
            switch (state.screen) {
                case 'start':
                    app.innerHTML = renderStart();
                    break;
                case 'quiz':
                    app.innerHTML = renderQuestion();
                    break;
                case 'result':
                    app.innerHTML = renderResult();
                    break;
            }
        }

        // Обработчики событий
        function startQuiz() {
            state.screen = 'quiz';
            state.currentQuestion = 0;
            state.score = 0;
            state.selectedAnswer = null;
            state.answered = false;
            render();
        }

        function selectAnswer(index) {
            if (!state.answered) {
                state.selectedAnswer = index;
                render();
            }
        }

        function checkAnswer() {
            if (state.selectedAnswer !== null) {
                state.answered = true;
                const q = QUESTIONS[state.currentQuestion];
                if (state.selectedAnswer === q.correct) {
                    state.score++;
                }
                render();
            }
        }

        function nextQuestion() {
            if (state.currentQuestion < QUESTIONS.length - 1) {
                state.currentQuestion++;
                state.selectedAnswer = null;
                state.answered = false;
                render();
            } else {
                state.screen = 'result';
                render();
            }
        }

        function restartQuiz() {
            state.screen = 'start';
            state.currentQuestion = 0;
            state.score = 0;
            state.selectedAnswer = null;
            state.answered = false;
            render();
        }

        // Инициализация
        function init() {
            render();
        }

        // Запуск приложения
        init();
    </script>
</body>
</html>
