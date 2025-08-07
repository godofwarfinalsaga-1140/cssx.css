
body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background-color: #f8fafc; /* Light blue-gray background */
            color: #334155; /* Dark gray text */
        }
        /* Styling for section headings */
        .section-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 8px;
            margin-bottom: 32px;
        }
        .section-heading::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 60%;
            height: 3px;
            background-color: #6366f1; /* Indigo color for underline */
            border-radius: 2px;
        }
        /* Styling for concept cards */
        .concept-card {
            background-color: #ffffff;
            padding: 24px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08); /* Soft shadow */
            border: 1px solid #e2e8f0; /* Light border */
            transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
        }
        .concept-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.12);
        }
        .concept-name {
            font-family: 'Inter', monospace; /* Monospace for code snippets */
            background-color: #e0e7ff; /* Light indigo background */
            color: #4338ca; /* Darker indigo text */
            padding: 4px 8px;
            border-radius: 4px;
            font-weight: 600;
            display: inline-block;
            margin-bottom: 12px;
        }
        .concept-description {
            color: #475569; /* Slate 700 */
            line-height: 1.6;
        }
        /* اینجا باید آکولاد بسته برای بلوک قبلی باشد، نه آکولاد باز */
