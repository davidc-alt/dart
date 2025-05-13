<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dartmouth Acceptance</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&family=Source+Sans+Pro:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Source Sans Pro', sans-serif; /* Default sans-serif font */
            color: #1a1a1a; /* Dark gray for text, common in official documents */
            background-color: #f8f9fa; /* Light off-white background */
            line-height: 1.6;
        }
        .letter-container {
            max-width: 800px; /* Max width for larger screens, but will scale down */
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff; /* White paper background */
            box-shadow: 0 0 15px rgba(0,0,0,0.1); /* Subtle shadow for depth */
            border-radius: 8px; /* Slightly rounded corners for the "paper" */
        }
        .header-logo {
            width: 150px; /* Adjust as needed */
            margin-bottom: 20px;
        }
        .dartmouth-green {
            color: #00693e; /* Dartmouth Green */
        }
        .serif-font {
            font-family: 'Merriweather', serif; /* Serif font for specific elements like headers or important text */
        }
        .signature-font {
            font-family: 'Dancing Script', cursive; /* A cursive font for signatures, though this is a placeholder */
            /* For a more realistic signature, an image would be better */
        }
        .watermark {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) rotate(-45deg);
            font-size: 5rem; /* Large font size */
            color: rgba(0, 105, 62, 0.05); /* Very light Dartmouth Green */
            font-weight: bold;
            z-index: 0; /* Behind the content */
            pointer-events: none; /* Allows clicking through */
            text-transform: uppercase;
            font-family: 'Merriweather', serif;
        }
        .content-wrapper {
            position: relative;
            z-index: 1; /* Above the watermark */
        }

        /* Mobile specific adjustments */
        @media (max-width: 600px) {
            .letter-container {
                margin: 10px;
                padding: 15px;
                box-shadow: none; /* Remove shadow on mobile for a cleaner look */
                border-radius: 0;
            }
            .header-logo {
                width: 120px;
                margin: 0 auto 20px auto; /* Center logo on mobile */
                display: block;
            }
            h1 {
                font-size: 1.8rem;
            }
            h2 {
                font-size: 1.3rem;
            }
            p, li {
                font-size: 0.95rem;
            }
            .watermark {
                font-size: 3rem;
            }
        }
    </style>
</head>
<body class="bg-gray-100">
    <div class="letter-container my-4 md:my-8">
        <div class="watermark">DARTMOUTH</div>
        <div class="content-wrapper">
            <header class="text-center mb-8">
                <div class="serif-font text-3xl md:text-4xl font-bold dartmouth-green mb-2">DARTMOUTH COLLEGE</div>
                <p class="text-sm text-gray-600">Office of Undergraduate Admissions</p>
                <p class="text-sm text-gray-600">6010 McNutt Hall, Hanover, New Hampshire 03755-3541</p>
            </header>

            <section class="mb-6 text-sm">
                <p class="mb-4">March 27, 2025</p> <p>David Bondarescu</p> <p>60 E woodruff ave</p> <p>Arcadia ca 91006</p> <p class="mt-2">Dear David,</p> </section>

            <main class="text-justify">
                <p class="mb-4">
                    It is with great pleasure that I offer you admission to Dartmouth College's Class of 2029. The Admissions Committee was profoundly impressed with your application, recognizing your exceptional academic achievements, your thoughtful engagement with the world around you, and the distinctive qualities you would bring to our vibrant community. </p>
                <p class="mb-4">
                    Choosing a college is a significant decision, and we know you have many excellent options. At Dartmouth, you will find a unique blend of a world-class research university and an intimate undergraduate-focused liberal arts college. Our faculty are leaders in their fields who are deeply committed to teaching and mentorship. You will join a community of passionate, curious, and kind individuals from all backgrounds, united by a love of learning and a desire to make a positive impact.
                </p>
                <h2 class="serif-font text-xl md:text-2xl font-semibold dartmouth-green my-4">A Community of Scholars</h2>
                <p class="mb-4">
                    From the historic Dartmouth Green to the state-of-the-art facilities across campus, you will discover an environment that fosters intellectual exploration and personal growth. Our D-Plan academic calendar offers flexibility to pursue internships, research, and study abroad opportunities, tailoring your education to your unique interests and aspirations. Whether you're drawn to the humanities, sciences, arts, or engineering, Dartmouth provides the resources and support for you to thrive.
                </p>
                <p class="mb-4">
                    We encourage you to explore our campus, either virtually or in person, during our Dimensions of Dartmouth program for admitted students. This is an excellent opportunity to meet current students and faculty, attend sample classes, and experience the spirit of Dartmouth firsthand. More information about Dimensions and other resources for admitted students can be found on the enclosed materials and on our website at <a href="#" class="dartmouth-green underline hover:text-green-700">admissions.dartmouth.edu/welcometo29s</a>. </p>
                 <h2 class="serif-font text-xl md:text-2xl font-semibold dartmouth-green my-4">Next Steps</h2>
                <p class="mb-4">
                    To accept your place in the Class of 2029, please submit your enrollment card and deposit by May 1, 2025. Details regarding financial aid, if applicable, are provided in a separate communication. We understand this is a significant commitment, and our team is available to answer any questions you may have. </p>
                <p class="mb-4">
                    David, we are excited by the prospect of you joining the Dartmouth family. Your talents and perspectives will enrich our community, and we believe Dartmouth will provide you with an unparalleled educational experience. </p>
                <p class="mb-4">
                    Congratulations again on this outstanding achievement. We look forward to welcoming you to Hanover!
                </p>
            </main>

            <footer class="mt-8">
                <p>Sincerely,</p>
                <p class="signature-font text-2xl dartmouth-green mt-2 mb-1">Lee Coffin</p> <p class="font-semibold">Lee Coffin</p>
                <p>Vice Provost for Enrollment and Dean of Admissions & Financial Aid</p>
                <p class="text-xs text-gray-500 mt-6">
                    Dartmouth College is committed to the principle of equal opportunity for all its students, faculty, staff, and applicants for admission and employment.
                </p>
            </footer>
        </div>
    </div>
    <script>
        // Optional: Any JavaScript for interactivity could go here.
        // For this use case, it's mainly HTML and CSS.
        console.log("Dartmouth Acceptance Letter Loaded");
    </script>
</body>
</html>
