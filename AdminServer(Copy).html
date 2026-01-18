<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta name="description" content="Disney+ Infinite - The Ultimate Cinematic Experience">
    <title>Disney+ Infinite | Ultimate Architect Build</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    <script src="https://unpkg.com/framer-motion@10.16.4/dist/framer-motion.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            darkMode: 'class', // Enables class-based dark mode toggling
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif'],
                    },
                    colors: {
                        // DARK MODE PALETTE
                        dark: {
                            bg: '#050505',       /* Almost Pitch Black */
                            surface: '#0F0F0F',  /* Surface Layer */
                            card: '#161616',     /* Card Layer */
                            text: '#EDEDED',     /* High Contrast Text */
                            muted: '#A3A3A3',    /* Secondary Text */
                            border: '#262626'    /* Subtle Borders */
                        },
                        // LIGHT MODE PALETTE
                        light: {
                            bg: '#FFFFFF',       /* Pure White */
                            surface: '#F4F4F5',  /* Off White */
                            card: '#FFFFFF',     /* Card Layer */
                            text: '#09090B',     /* Deep Ink Black */
                            muted: '#71717A',    /* Secondary Text */
                            border: '#E4E4E7'    /* Light Borders */
                        },
                        // BRAND ACCENTS
                        brand: {
                            primary: '#2563EB',  /* Vivid Blue */
                            secondary: '#7C3AED', /* Deep Purple */
                            accent: '#F59E0B',   /* Amber Gold */
                            danger: '#EF4444'    /* Alert Red */
                        }
                    },
                    boxShadow: {
                        'cinema': '0 40px 80px -20px rgba(0, 0, 0, 0.6)',
                        'floating': '0 20px 40px -10px rgba(0, 0, 0, 0.2)',
                        'glow': '0 0 40px rgba(37, 99, 235, 0.2)',
                    },
                    transitionProperty: {
                        'height': 'height',
                        'spacing': 'margin, padding',
                    }
                }
            }
        }
    </script>

    <style>
        /* Base Reset */
        * {
            box-sizing: border-box;
            -webkit-tap-highlight-color: transparent;
            touch-action: pan-y;
            user-select: none; /* App-like feel */
        }

        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            overflow-x: hidden;
            font-family: 'Poppins', sans-serif;
            /* Smooth Background Transition for Dark Mode */
            transition: background-color 0.5s ease-in-out, color 0.5s ease-in-out;
        }

        /* Dark Mode Body Background */
        html.dark body {
            background-color: #050505;
            color: #EDEDED;
        }

        /* Light Mode Body Background */
        body {
            background-color: #FFFFFF;
            color: #09090B;
        }

        /* Hiding Scrollbars for a cleaner UI */
        .hide-scroll::-webkit-scrollbar {
            display: none;
        }
        .hide-scroll {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* 3D Perspective Stage */
        .stage-3d {
            perspective: 1000px;
            transform-style: preserve-3d;
        }
    </style>
</head>
<body>

    <div id="root"></div>

    <script type="text/babel">
            const { useState, useEffect, useContext, createContext, useRef, useMemo } = React;
        const { motion, AnimatePresence } = window.Motion;

        /**
         * ====================================================================
         * APPLICATION LOGIC START
         * ====================================================================
         */
         {
}


        /* * ------------------------------------------------------------------
         * DATA LAYER: THE UNIVERSE DATABASE
         * Contains detailed information for all 6 sections.
         * ------------------------------------------------------------------
         */
        const UNIVERSE_DB = [
            {
                id: "sec_pixie",
                title: "Pixie Hollow",
                description: "Enter the magical world of fairies.",
                items: [
                    { 
                        id: "char_rosetta", 
                        name: "Rosetta", 
                        movie: "Tinkerbell", 
                        year: "2008",
                        role: "Garden Fairy",
                        quote: "I'm not just a pretty face, you know.",
                        rating: 4.8, 
                        color: "from-rose-400 to-pink-600", 
                        shadow: "shadow-pink-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/d/db/Rosetta_%28Disney_Fairies%29.png", 
                        desc: "Rosetta is a garden fairy who is polite and well-mannered, but also has a quick wit and a lot of charm. She loves fashion and flowers.",
                        stats: { charm: 95, magic: 80, speed: 75 }
                    },
                    { 
                        id: "char_tink", 
                        name: "Tink", 
                        movie: "Peter Pan", 
                        year: "1953",
                        role: "Tinker Fairy",
                        quote: "All you need is faith, trust, and pixie dust.",
                        rating: 4.9, 
                        color: "from-green-400 to-emerald-600", 
                        shadow: "shadow-green-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/3/31/Tinker_Bell_character_artwork.png", 
                        desc: "Tinker Bell is a tinker fairy. She is sassy, feisty, and extremely loyal to her friends. She fixes things.",
                        stats: { charm: 88, magic: 85, speed: 90 }
                    },
                    { 
                        id: "char_silver", 
                        name: "Silvermist", 
                        movie: "Tinkerbell", 
                        year: "2008",
                        role: "Water Fairy",
                        quote: "Water can be strong or gentle.",
                        rating: 4.7, 
                        color: "from-blue-400 to-cyan-600", 
                        shadow: "shadow-blue-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/a/a2/Silvermist.png", 
                        desc: "Silvermist is a water fairy. She is quirky, sweet, and looks at the world differently than the others.",
                        stats: { charm: 92, magic: 90, speed: 80 }
                    }
                ]
            },
            {
                title: "Inside The Mind",
                description: "Meet the voices inside your head.",
                items: [
                    { 
                        id: "char_sadness", 
                        name: "Sadness", 
                        movie: "Inside Out", 
                        year: "2015",
                        role: "Core Emotion",
                        quote: "Crying helps me slow down and obsess.",
                        rating: 5.0, 
                        color: "from-blue-500 to-indigo-700", 
                        shadow: "shadow-indigo-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/c/c2/Inside_Out_Sadness.png", 
                        desc: "Sadness is the voice of reason. Thoughtful, empathetic, and vital to Riley's emotional balance.",
                        stats: { charm: 70, magic: 95, speed: 40 }
                    },
                    { 
                        id: "char_disgust", 
                        name: "Disgust", 
                        movie: "Inside Out", 
                        year: "2015",
                        role: "Core Emotion",
                        quote: "Ew, no.",
                        rating: 4.6, 
                        color: "from-green-500 to-teal-700", 
                        shadow: "shadow-green-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/b/b3/Inside_Out_Disgust.png", 
                        desc: "Disgust is highly opinionated and extremely honest. She prevents Riley from being poisoned.",
                        stats: { charm: 80, magic: 75, speed: 70 }
                    },
                    { 
                        id: "char_anger", 
                        name: "Anger", 
                        movie: "Inside Out", 
                        year: "2015",
                        role: "Core Emotion",
                        quote: "I saw it first!",
                        rating: 4.8, 
                        color: "from-red-500 to-orange-700", 
                        shadow: "shadow-red-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/9/9b/Inside_Out_Anger.png", 
                        desc: "Anger feels very passionately about making sure things are fair for Riley. He has a fiery temper.",
                        stats: { charm: 60, magic: 80, speed: 85 }
                    }
                ]
            },
            {
                title: "Zootopia PD",
                description: "Protecting the city where anyone can be anything.",
                items: [
                    { 
                        id: "char_judy", 
                        name: "Judy", 
                        movie: "Zootopia", 
                        year: "2016",
                        role: "Officer",
                        quote: "I am not giving up.",
                        rating: 4.9, 
                        color: "from-purple-400 to-indigo-600", 
                        shadow: "shadow-purple-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/thumb/6/6f/Judy_Hopps.png/220px-Judy_Hopps.png", 
                        desc: "Officer Judy Hopps is the first rabbit officer in Zootopia. Optimistic and determined to prove herself.",
                        stats: { charm: 90, magic: 10, speed: 95 }
                    },
                    { 
                        id: "char_nick", 
                        name: "Nick", 
                        movie: "Zootopia", 
                        year: "2016",
                        role: "Con Artist",
                        quote: "It's called a hustle, sweetheart.",
                        rating: 4.9, 
                        color: "from-orange-400 to-amber-600", 
                        shadow: "shadow-orange-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/thumb/9/90/Nick_Wilde.png/220px-Nick_Wilde.png", 
                        desc: "Nick Wilde is a charming, small-time con artist fox with a big mouth and a lot of opinions.",
                        stats: { charm: 98, magic: 10, speed: 85 }
                    },
                    { 
                        id: "char_flash", 
                        name: "Flash", 
                        movie: "Zootopia", 
                        year: "2016",
                        role: "DMV Clerk",
                        quote: "Niiiiiice.",
                        rating: 4.5, 
                        color: "from-stone-400 to-stone-600", 
                        shadow: "shadow-stone-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/e/ea/Flash_the_Sloth_Zootopia.png", 
                        desc: "Flash is the fastest sloth at the DMV. He takes his time, much to Judy's frustration.",
                        stats: { charm: 80, magic: 5, speed: 1 }
                    }
                ]
            },
            {
                title: "Frozen Kingdom",
                description: "The cold never bothered them anyway.",
                items: [
                    { 
                        id: "char_elsa", 
                        name: "Elsa", 
                        movie: "Frozen", 
                        year: "2013",
                        role: "Queen",
                        quote: "Let it go.",
                        rating: 5.0, 
                        color: "from-cyan-400 to-blue-600", 
                        shadow: "shadow-cyan-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/thumb/5/5e/Elsa_from_Disney%27s_Frozen.png/220px-Elsa_from_Disney%27s_Frozen.png", 
                        desc: "Elsa has magical powers to create ice and snow. She is regal, reserved, but lives in fear of her power.",
                        stats: { charm: 90, magic: 100, speed: 80 }
                    },
                    { 
                        id: "char_olaf", 
                        name: "Olaf", 
                        movie: "Frozen", 
                        year: "2013",
                        role: "Snowman",
                        quote: "I like warm hugs!",
                        rating: 4.8, 
                        color: "from-sky-300 to-blue-400", 
                        shadow: "shadow-sky-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/thumb/5/51/Olaf_from_Disney%27s_Frozen.png/220px-Olaf_from_Disney%27s_Frozen.png", 
                        desc: "Olaf is a snowman who loves warm hugs. He is the friendliest snowman in Arendelle.",
                        stats: { charm: 99, magic: 50, speed: 60 }
                    },
                    { 
                        id: "char_anna", 
                        name: "Anna", 
                        movie: "Frozen", 
                        year: "2013",
                        role: "Princess",
                        quote: "Love is an open door.",
                        rating: 4.9, 
                        color: "from-fuchsia-400 to-purple-600", 
                        shadow: "shadow-fuchsia-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/thumb/d/d0/Anna_from_Disney%27s_Frozen.png/220px-Anna_from_Disney%27s_Frozen.png", 
                        desc: "Anna is more daring than graceful. She is the most optimistic and caring person you will ever meet.",
                        stats: { charm: 95, magic: 20, speed: 85 }
                    }
                ]
            },
            {
                title: "Classic Heroes",
                description: "Legends that started it all.",
                items: [
                    { 
                        id: "char_aladdin", 
                        name: "Aladdin", 
                        movie: "Aladdin", 
                        year: "1992",
                        role: "Hero",
                        quote: "Do you trust me?",
                        rating: 4.7, 
                        color: "from-purple-500 to-violet-700", 
                        shadow: "shadow-purple-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/e/e4/Aladdin_Disney.png", 
                        desc: "Aladdin is a street rat with a heart of gold. He uses his wit to survive the streets of Agrabah.",
                        stats: { charm: 92, magic: 10, speed: 90 }
                    },
                    { 
                        id: "char_hercules", 
                        name: "Hercules", 
                        movie: "Hercules", 
                        year: "1997",
                        role: "Demigod",
                        quote: "I can go the distance.",
                        rating: 4.6, 
                        color: "from-yellow-500 to-orange-600", 
                        shadow: "shadow-orange-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/b/b4/Hercules_Disney_promotional_art.png", 
                        desc: "Hercules is the son of Zeus. He has god-like strength but must prove himself a true hero.",
                        stats: { charm: 80, magic: 50, speed: 85 }
                    },
                    { 
                        id: "char_tarzan", 
                        name: "Tarzan", 
                        movie: "Tarzan", 
                        year: "1999",
                        role: "Wild Man",
                        quote: "Two worlds, one family.",
                        rating: 4.7, 
                        color: "from-green-500 to-lime-700", 
                        shadow: "shadow-lime-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/2/29/Tarzan_Disney_Char.png", 
                        desc: "Tarzan was raised by gorillas. He is strong, wild, and deeply connected to the jungle.",
                        stats: { charm: 85, magic: 0, speed: 98 }
                    }
                ]
            },
            {
                title: "Toy Story Gang",
                description: "You've got a friend in me.",
                items: [
                    { 
                        id: "char_woody", 
                        name: "Woody", 
                        movie: "Toy Story", 
                        year: "1995",
                        role: "Sheriff",
                        quote: "Reach for the sky!",
                        rating: 4.9, 
                        color: "from-yellow-400 to-amber-700", 
                        shadow: "shadow-amber-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/0/01/Sheriff_Woody.png", 
                        desc: "Woody is Andy's favorite toy. He is a cowboy doll who is loyal, passionate, and a natural leader." ,
                        stats: { charm: 95, magic: 0, speed: 70 }
                    },
                    { 
                        id: "char_buzz", 
                        name: "Buzz", 
                        movie: "Toy Story", 
                        year: "1995",
                        role: "Space Ranger",
                        quote: "To infinity and beyond!",
                        rating: 4.8, 
                        color: "from-green-400 to-purple-600", 
                        shadow: "shadow-green-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/b/b4/Buzz_Lightyear.png", 
                        desc: "Buzz Lightyear is a space ranger. He comes in peace and is ready to go to infinity and beyond.",
                        stats: { charm: 85, magic: 5, speed: 85 }
                    },
                    { 
                        id: "char_jessie", 
                        name: "Jessie", 
                        movie: "Toy Story 2", 
                        year: "1999",
                        role: "Cowgirl",
                        quote: "Yee-haw!",
                        rating: 4.7, 
                        color: "from-red-400 to-rose-600", 
                        shadow: "shadow-rose-500/40", 
                        img: "https://upload.wikimedia.org/wikipedia/en/d/d3/Jessie_%28Toy_Story%29.png", 
                        desc: "Jessie is a yodeling cowgirl doll. She is exuberant, brave, and very athletic.",
                        stats: { charm: 92, magic: 0, speed: 90 }
                    }
                ]
            }
        ];

        /* * ------------------------------------------------------------------
         * CONTEXT: THEME PROVIDER (NORMAL TRANSITION)
         * Simplifies the theme logic to just class switching.
         * ------------------------------------------------------------------
         */
        const ThemeContext = createContext();

        function ThemeProvider({ children }) {
            const [isDark, setIsDark] = useState(false);

            // Function to toggle theme smoothly
            const toggleTheme = () => {
                setIsDark(prev => !prev);
            };

            // Effect to update the DOM
            useEffect(() => {
                if (isDark) {
                    document.documentElement.classList.add('dark');
                } else {
                    document.documentElement.classList.remove('dark');
                }
            }, [isDark]);

            return (
                <ThemeContext.Provider value={{ isDark, toggleTheme }}>
                    {children}
                </ThemeContext.Provider>
            );
        }

        /* * ------------------------------------------------------------------
         * ASSETS: VECTOR ICONS (SVG)
         * Fully drawn out SVGs for crisp rendering on all devices.
         * ------------------------------------------------------------------
         */
        const Icons = {
            Sun: () => (
                <svg className="w-8 h-8 text-yellow-400 drop-shadow-md" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M12 2.25a.75.75 0 01.75.75v2.25a.75.75 0 01-1.5 0V3a.75.75 0 01.75-.75zM6.166 5.106a.75.75 0 010 1.06l-1.591 1.591a.75.75 0 01-1.06-1.06l1.591-1.591a.75.75 0 011.06 0zm11.668 0a.75.75 0 011.06 0l1.591 1.591a.75.75 0 11-1.06 1.06l-1.591-1.591a.75.75 0 010-1.06zM12 7.5a4.5 4.5 0 100 9 4.5 4.5 0 000-9zM21.75 12a.75.75 0 01-.75.75h-2.25a.75.75 0 010-1.5H21a.75.75 0 01.75.75zM4.5 12a.75.75 0 01-.75.75H1.5a.75.75 0 010-1.5H3.75a.75.75 0 01.75.75zM17.834 18.834a.75.75 0 010 1.06l-1.591 1.591a.75.75 0 01-1.06-1.06l1.591-1.591a.75.75 0 011.06 0zm-11.668 0a.75.75 0 011.06 0l1.591 1.591a.75.75 0 01-1.06 1.06l-1.591-1.591a.75.75 0 010-1.06zM12 21.75a.75.75 0 01.75.75v2.25a.75.75 0 01-1.5 0V22.5a.75.75 0 01.75-.75z" />
                </svg>
            ),
            Moon: () => (
                <svg className="w-8 h-8 text-blue-200 drop-shadow-md" fill="currentColor" viewBox="0 0 24 24">
                    <path fillRule="evenodd" d="M9.528 1.718a.75.75 0 01.162.819A8.97 8.97 0 009 6a9 9 0 009 9 8.97 8.97 0 003.463-.69.75.75 0 01.981.98 10.503 10.503 0 01-9.694 6.46c-5.799 0-10.5-4.701-10.5-10.5 0-4.368 2.667-8.112 6.46-9.694a.75.75 0 01.818.162z" clipRule="evenodd" />
                </svg>
            ),
            Android: () => (
                <svg className="w-8 h-8 text-[#3DDC84]" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M17.523 15.3414C17.523 16.7369 16.3769 17.868 14.9625 17.868C13.5481 17.868 12.402 16.7369 12.402 15.3414C12.402 13.9459 13.5481 12.8148 14.9625 12.8148C16.3769 12.8148 17.523 13.9459 17.523 15.3414ZM6.37687 17.868C4.96248 17.868 3.81641 16.7369 3.81641 15.3414C3.81641 13.9459 4.96248 12.8148 6.37687 12.8148C7.79126 12.8148 8.93733 13.9459 8.93733 15.3414C8.93733 16.7369 7.79126 17.868 6.37687 17.868ZM18.7303 9.40822L20.8407 5.75168C20.9427 5.57502 20.8816 5.34863 20.7049 5.24665C20.5283 5.14466 20.3019 5.20573 20.1999 5.38239L18.0699 9.07252C16.4883 8.3514 14.717 7.9502 12.85 7.89921V7.89921L12.8466 7.89921C10.9796 7.9502 9.20836 8.3514 7.62672 9.07252L5.49672 5.38239C5.39473 5.20573 5.16834 5.14466 4.99168 5.24665C4.81502 5.34863 4.75395 5.57502 4.85594 5.75168L6.96633 9.40822C3.12027 11.5161 0.490234 15.3855 0.490234 19.897H25.2064C25.2064 15.3855 22.5764 11.5161 18.7303 9.40822Z"/>
                </svg>
            ),
            Apple: () => (
                <svg className="w-8 h-8 text-[#A3AAAE]" fill="currentColor" viewBox="0 0 384 512">
                    <path d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 49.7-25.2 74 27.1 2.7 53.7-21.3 69.1-36.4z"/>
                </svg>
            ),
            News: () => (
                <div className="w-8 h-8 rounded-lg bg-gradient-to-tr from-pink-500 to-rose-500 flex items-center justify-center text-white font-black text-lg shadow-lg">N</div>
            ),
            Profile: () => (
                <div className="w-8 h-8 rounded-full bg-gradient-to-tr from-blue-500 to-cyan-500 border-2 border-white shadow-lg"></div>
            ),
            Back: () => (
                <svg width="28" height="28" fill="none" stroke="currentColor" strokeWidth="3" viewBox="0 0 24 24">
                    <path strokeLinecap="round" strokeLinejoin="round" d="M15 19l-7-7 7-7"/>
                </svg>
            ),
            Heart: ({filled}) => (
                <svg className={`w-8 h-8 transition-colors duration-300 ${filled ? 'text-red-500 fill-current' : 'text-white'}`} fill="none" stroke="currentColor" strokeWidth="2.5" viewBox="0 0 24 24">
                    <path strokeLinecap="round" strokeLinejoin="round" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                </svg>
            ),
            Search: () => (
                <svg className="w-6 h-6 text-gray-400 group-hover:text-brand-primary transition-colors duration-300" fill="none" stroke="currentColor" strokeWidth="2.5" viewBox="0 0 24 24">
                    <path strokeLinecap="round" strokeLinejoin="round" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/>
                </svg>
            ),
            Play: () => (
                <svg className="w-6 h-6 fill-current" viewBox="0 0 24 24">
                    <path d="M8 5v14l11-7z"/>
                </svg>
            )
        };

        /* * ------------------------------------------------------------------
         * ANIMATION VARIANTS
         * Staggered animation configuration for the "Typewriter/Slide Up" effect.
         * ------------------------------------------------------------------
         */
        const textContainerVariants = {
            hidden: { opacity: 0 },
            show: {
                opacity: 1,
                transition: {
                    staggerChildren: 0.15, // Delay between each line
                    delayChildren: 0.5     // Wait for modal expansion
                }
            },
            exit: {
                opacity: 0,
                transition: {
                    staggerChildren: 0.05,
                    staggerDirection: -1
                }
            }
        };

        const textItemVariants = {
            hidden: { y: 30, opacity: 0, filter: "blur(10px)" },
            show: { 
                y: 0, 
                opacity: 1, 
                filter: "blur(0px)",
                transition: { type: "spring", stiffness: 40, damping: 15 }
            },
            exit: { y: 20, opacity: 0, filter: "blur(5px)" }
        };

        /* * ------------------------------------------------------------------
         * COMPONENT: DETAIL MODAL
         * The main full-screen view for a character.
         * ------------------------------------------------------------------
         */
        function DetailModal({ item, onClose, isFav, toggleFav }) {
            return (
                <motion.div 
                    className="fixed inset-0 z-50 bg-light-bg dark:bg-dark-bg flex flex-col overflow-y-auto hide-scroll"
                    initial={{ clipPath: "circle(0% at 50% 50%)" }}
                    animate={{ clipPath: "circle(150% at 50% 50%)" }}
                    exit={{ clipPath: "circle(0% at 50% 50%)" }}
                    transition={{ duration: 1.0, ease: [0.22, 1, 0.36, 1] }}
                >
                    <motion.div 
                        layoutId={`bg-${item.id}`} 
                        className={`w-full h-[55vh] relative shrink-0 bg-gradient-to-br ${item.color} shadow-cinema flex items-center justify-center overflow-hidden rounded-b-[70px]`}
                    >
                        <div className="absolute top-0 left-0 w-full px-8 pt-12 flex justify-between z-50">
                            <motion.button 
                                onClick={onClose} 
                                whileTap={{scale:0.9}} 
                                className="w-14 h-14 bg-white/20 backdrop-blur-xl rounded-full flex items-center justify-center text-white border border-white/20 hover:bg-white/30 transition-colors"
                            >
                                <Icons.Back />
                            </motion.button>
                            <motion.button 
                                onClick={toggleFav} 
                                whileTap={{scale:0.9}} 
                                className="w-14 h-14 bg-white/20 backdrop-blur-xl rounded-full flex items-center justify-center text-white border border-white/20 hover:bg-white/30 transition-colors"
                            >
                                <Icons.Heart filled={isFav} />
                            </motion.button>
                        </div>

                        <motion.div layoutId={`img-${item.id}`} className="mt-16 z-20">
                             <motion.img 
                                src={item.img} 
                                alt={item.name}
                                className="h-[450px] object-contain drop-shadow-[0_40px_80px_rgba(0,0,0,0.6)]"
                                animate={{ y: [0, -20, 0] }}
                                transition={{ repeat: Infinity, duration: 6, ease: "easeInOut" }}
                             />
                        </motion.div>

                        <h1 className="absolute bottom-[-30px] w-full text-center text-[120px] font-black text-white opacity-10 tracking-tighter leading-none select-none pointer-events-none">
                            {item.name}
                        </h1>
                    </motion.div>

                    <div className="p-10 flex-1 relative">
                        <motion.div 
                            variants={textContainerVariants}
                            initial="hidden"
                            animate="show"
                            exit="exit"
                            className="flex flex-col gap-8 max-w-2xl mx-auto"
                        >
                            <motion.div variants={textItemVariants}>
                                <motion.h1 layoutId={`title-${item.id}`} className="text-6xl font-black text-light-text dark:text-dark-text tracking-tight">
                                    {item.name}
                                </motion.h1>
                                <p className="text-brand-primary font-bold text-sm tracking-[0.4em] uppercase mt-2">{item.role}</p>
                            </motion.div>

                            <motion.div variants={textItemVariants} className="flex flex-wrap items-center gap-4">
                                <span className="px-5 py-2 rounded-2xl bg-light-surface dark:bg-dark-surface text-sm font-bold uppercase tracking-widest text-light-muted dark:text-dark-muted border border-light-border dark:border-dark-border">
                                    {item.movie} ({item.year})
                                </span>
                                <div className="flex items-center gap-1 text-brand-gold text-lg font-bold">
                                    <span>★ {item.rating}</span>
                                </div>
                            </motion.div>

                            <motion.div variants={textItemVariants}>
                                <p className="text-xl text-light-muted dark:text-dark-muted leading-relaxed font-medium">
                                    {item.desc}
                                </p>
                                <div className="mt-4 pl-4 border-l-4 border-brand-primary">
                                    <p className="italic text-lg text-light-text dark:text-dark-text">"{item.quote}"</p>
                                </div>
                            </motion.div>

                            <motion.div variants={textItemVariants} className="grid grid-cols-3 gap-4 mt-4">
                                {Object.entries(item.stats).map(([key, value], i) => (
                                    <div key={key} className="p-6 bg-light-surface dark:bg-dark-card rounded-3xl text-center border border-light-border dark:border-white/5">
                                        <p className="text-xs font-black uppercase text-light-muted dark:text-dark-muted tracking-widest">{key}</p>
                                        <p className="text-3xl font-black text-light-text dark:text-dark-text mt-1">{value}</p>
                                    </div>
                                ))}
                            </motion.div>

                            <motion.div variants={textItemVariants} className="mt-6 pb-10">
                                <button className="w-full py-6 bg-light-text dark:bg-brand-primary text-white rounded-[35px] font-black text-2xl shadow-xl active:scale-95 transition-transform flex items-center justify-center gap-3">
                                    <Icons.Play />
                                    <span>Watch Movie</span>
                                </button>
                            </motion.div>
                        </motion.div>
                    </div>
                </motion.div>
            );
        }

        /* * ------------------------------------------------------------------
         * COMPONENT: CHARACTER CARD
         * The list item that appears in the horizontal scrollers.
         * ------------------------------------------------------------------
         */
        function CharacterCard({ item, onClick }) {
            return (
                <motion.div 
                    layoutId={`wrapper-${item.id}`}
                    onClick={onClick}
                    className="relative w-[300px] h-[450px] shrink-0 pt-20 cursor-pointer group perspective-1000"
                    whileHover={{ y: -15, transition: { duration: 0.4 } }}
                    whileTap={{ scale: 0.95 }}
                >
                    <motion.div 
                        layoutId={`bg-${item.id}`}
                        className={`absolute bottom-0 w-full h-[380px] rounded-[50px] bg-gradient-to-br ${item.color} ${item.shadow} shadow-cinema flex flex-col justify-end p-8 overflow-hidden`}
                    >
                        <div className="relative z-10">
                            <motion.h2 layoutId={`title-${item.id}`} className="text-4xl font-black text-white drop-shadow-md leading-none">
                                {item.name}
                            </motion.h2>
                            <p className="text-white/80 font-bold uppercase text-[11px] tracking-[0.3em] mt-3 opacity-80">{item.movie}</p>
                        </div>
                        <div className="absolute -top-20 -right-20 w-64 h-64 bg-white opacity-10 rounded-full blur-3xl group-hover:scale-125 transition-transform duration-700"></div>
                    </motion.div>

                    <motion.div 
                        layoutId={`img-${item.id}`}
                        className="absolute top-0 left-0 w-full flex justify-center z-20 pointer-events-none"
                    >
                        <motion.img 
                            src={item.img} 
                            alt={item.name}
                            className="h-[360px] object-contain drop-shadow-[0_20px_40px_rgba(0,0,0,0.4)]"
                            initial={{ y: 0 }}
                            animate={{ y: [0, -12, 0] }} 
                            transition={{ repeat: Infinity, duration: 5, ease: "easeInOut" }}
                        />
                    </motion.div>
                </motion.div>
            );
        }

        /* * ------------------------------------------------------------------
         * COMPONENT: SECTION ROW
         * A reusable horizontal scrolling section.
         * ------------------------------------------------------------------
         */
        function SectionRow({ title, description, items, onSelect }) {
            const constraintRef = useRef(null);
            const [width, setWidth] = useState(0);

            useEffect(() => {
                if(constraintRef.current) {
                    setWidth(constraintRef.current.scrollWidth - constraintRef.current.offsetWidth);
                }
            }, [items]);

            return (
                <div className="pl-8 mb-12">
                    <div className="pr-8 mb-6">
                        <h3 className="text-3xl font-black tracking-tight text-light-text dark:text-dark-text">{title}</h3>
                        <p className="text-sm font-medium text-light-muted dark:text-dark-muted mt-1">{description}</p>
                    </div>
                    <motion.div ref={constraintRef} className="overflow-hidden cursor-grab active:cursor-grabbing">
                        <motion.div 
                            className="flex gap-8 pr-12 pb-12 pt-4 w-max"
                            drag="x" 
                            dragConstraints={{ right: 0, left: -width }}
                        >
                            {items.map(item => (
                                <CharacterCard key={item.id} item={item} onClick={() => onSelect(item)} />
                            ))}
                        </motion.div>
                    </motion.div>
                </div>
            );
        }

        /* * ------------------------------------------------------------------
         * COMPONENT: MENU DRAWER
         * The slide-down menu with options.
         * ------------------------------------------------------------------
         */
        function MenuDrawer({ isOpen, onClose }) {
            const menuItems = [
                { id: 1, title: "Android", sub: "Disney OS", icon: <Icons.Android />, bg: "bg-green-100 dark:bg-green-900/20" },
                { id: 2, title: "iOS", sub: "Apple Eco", icon: <Icons.Apple />, bg: "bg-gray-100 dark:bg-gray-800/40" },
                { id: 3, title: "Apps", sub: "Store", icon: <Icons.Android />, bg: "bg-blue-100 dark:bg-blue-900/20" },
                { id: 4, title: "Magic", sub: "Themes", icon: <Icons.Sun />, bg: "bg-yellow-100 dark:bg-yellow-900/20" },
                { id: 5, title: "News", sub: "Updates", icon: <Icons.News />, bg: "bg-pink-100 dark:bg-pink-900/20" },
                { id: 6, title: "Profile", sub: "Me", icon: <Icons.Profile />, bg: "bg-purple-100 dark:bg-purple-900/20" }
            ];

            return (
                <AnimatePresence>
                    {isOpen && (
                        <>
                            <motion.div 
                                initial={{ opacity: 0 }} animate={{ opacity: 1 }} exit={{ opacity: 0 }} 
                                onClick={onClose} className="fixed inset-0 bg-black/60 backdrop-blur-sm z-40" 
                            />
                            <motion.div 
                                initial={{ y: "-100%" }} animate={{ y: 0 }} exit={{ y: "-120%" }}
                                transition={{ type: "spring", stiffness: 50, damping: 20 }}
                                className="fixed top-0 left-0 w-full bg-light-bg dark:bg-dark-card z-[60] rounded-b-[50px] shadow-cinema overflow-hidden border-b border-white/5"
                            >
                                <div className="p-8 pb-12">
                                    <div className="flex justify-between items-center mb-8">
                                        <h2 className="text-4xl font-black italic text-light-text dark:text-dark-text tracking-tighter">Menu</h2>
                                        <button onClick={onClose} className="w-12 h-12 bg-gray-200 dark:bg-white/10 rounded-full flex items-center justify-center dark:text-white text-xl font-bold">✕</button>
                                    </div>
                                    <div className="grid grid-cols-2 gap-4">
                                        {menuItems.map(item => (
                                            <motion.div key={item.id} whileTap={{ scale: 0.95 }} className={`p-6 rounded-3xl ${item.bg} flex flex-col items-center gap-3 cursor-pointer`}>
                                                <div className="p-4 bg-white dark:bg-black/30 rounded-full shadow-sm">{item.icon}</div>
                                                <div className="text-center">
                                                    <h3 className="font-bold text-lg text-gray-800 dark:text-white">{item.title}</h3>
                                                    <p className="text-xs font-bold uppercase text-gray-500">{item.sub}</p>
                                                </div>
                                            </motion.div>
                                        ))}
                                    </div>
                                </div>
                            </motion.div>
                        </>
                    )}
                </AnimatePresence>
            );
        }

        
        /* * ------------------------------------------------------------------
         * COMPONENT: MAIN APP ORCHESTRATOR
         * Handles state, data filtering, and layout.
         * ------------------------------------------------------------------
         */
        function App() {
            const { isDark, toggleTheme } = useContext(ThemeContext);
            const [selectedChar, setSelectedChar] = useState(null);
            const [isMenuOpen, setIsMenuOpen] = useState(false);
            const [searchTerm, setSearchTerm] = useState("");
            const [favorites, setFavorites] = useState([]);

            const toggleFav = (id) => {
                if(favorites.includes(id)) setFavorites(favorites.filter(fav => fav !== id));
                else setFavorites([...favorites, id]);
            };

            // SEARCH FILTERING LOGIC
            // Returns a new structure retaining the section headers
            const filteredSections = UNIVERSE_DB.map(section => ({
                ...section,
                items: section.items.filter(item => item.name.toLowerCase().includes(searchTerm.toLowerCase()))
            })).filter(section => section.items.length > 0);

            return (
                <div className="min-h-screen relative pb-32">
                    
                    {/* --- HEADER --- */}
                    <header className="px-8 pt-12 pb-6 flex justify-between items-center sticky top-0 z-30 bg-light-bg/80 dark:bg-dark-bg/80 backdrop-blur-xl border-b border-transparent dark:border-white/5 transition-all duration-500">
                        <div className="flex flex-col">
                            <h1 className="text-4xl font-black italic tracking-tighter text-transparent bg-clip-text bg-gradient-to-r from-brand-primary to-brand-secondary">Disney+</h1>
                            <span className="text-[10px] font-bold tracking-[0.6em] uppercase text-light-muted dark:text-dark-muted ml-1">Infinite</span>
                        </div>

                        <div className="flex items-center gap-6">
                            {/* 3D TOGGLE BUTTON */}
                            <div className="stage-3d w-14 h-14 cursor-pointer" onClick={toggleTheme}>
                                <motion.div 
                                    className="w-full h-full relative"
                                    animate={{ rotateY: isDark ? 180 : 0 }}
                                    transition={{ duration: 0.8, ease: "backOut" }}
                                    style={{ transformStyle: "preserve-3d" }}
                                >
                                    {/* Front Face: Sun */}
                                    <div className="absolute inset-0 bg-white border-2 border-gray-100 rounded-full flex items-center justify-center shadow-lg" style={{ backfaceVisibility: 'hidden' }}>
                                        <Icons.Sun />
                                    </div>
                                    {/* Back Face: Moon */}
                                    <div className="absolute inset-0 bg-dark-card border-2 border-white/10 rounded-full flex items-center justify-center shadow-lg" style={{ backfaceVisibility: 'hidden', transform: 'rotateY(180deg)' }}>
                                        <Icons.Moon />
                                    </div>
                                </motion.div>
                            </div>

                            {/* MENU HAMBURGER */}
                            <motion.button 
                                whileTap={{ scale: 0.9 }}
                                onClick={() => setIsMenuOpen(true)}
                                className="w-14 h-14 bg-white dark:bg-white/5 rounded-2xl border border-gray-100 dark:border-white/10 flex flex-col items-center justify-center gap-1.5 shadow-sm"
                            >
                                <div className="w-6 h-[3px] bg-light-text dark:bg-white rounded-full"></div>
                                <div className="w-4 h-[3px] bg-light-text dark:bg-white rounded-full ml-auto mr-3"></div>
                            </motion.button>
                        </div>
                    </header>

                    {/* --- SEARCH BAR --- */}
                    <div className="px-8 mt-8 mb-12">
                        <div className="w-full h-20 bg-light-bg dark:bg-dark-card rounded-3xl flex items-center px-8 gap-6 shadow-sm border border-light-border dark:border-white/5 transition-colors group hover:shadow-glow focus-within:shadow-glow">
                            <Icons.Search />
                            <input 
                                type="text" placeholder="Explore the infinite..." 
                                value={searchTerm} onChange={(e) => setSearchTerm(e.target.value)}
                                className="w-full bg-transparent outline-none text-xl font-bold text-light-text dark:text-dark-text placeholder-light-muted dark:placeholder-dark-muted"
                            />
                        </div>
                    </div>

                    {/* --- CONTENT SECTIONS --- */}
                    <div className="flex flex-col gap-4">
                        {filteredSections.map((section, idx) => (
                            <SectionRow 
                                key={idx} 
                                title={section.title} 
                                description={section.description} 
                                items={section.items} 
                                onSelect={setSelectedChar} 
                            />
                        ))}
                    </div>

                    {/* --- MODAL LAYERS --- */}
                    <MenuDrawer isOpen={isMenuOpen} onClose={() => setIsMenuOpen(false)} />
                    
                    <AnimatePresence>
                        {selectedChar && (
                            <DetailModal 
                                item={selectedChar} 
                                onClose={() => setSelectedChar(null)} 
                                isFav={favorites.includes(selectedChar.id)} 
                                toggleFav={() => toggleFav(selectedChar.id)}
                            />
                        )}
                    </AnimatePresence>

                    {/* --- FLOATING BOTTOM NAV --- */}
                    <div className="fixed bottom-0 w-full px-10 pb-10 flex justify-between items-center z-30 pointer-events-none">
                        <div className="flex gap-3">
                            <motion.div animate={{ height: [8, 16, 8] }} transition={{repeat:Infinity, duration:2}} className="w-2 bg-brand-primary rounded-full"></motion.div>
                            <div className="w-2 h-2 bg-gray-300 dark:bg-gray-700 rounded-full"></div>
                            <div className="w-2 h-2 bg-gray-300 dark:bg-gray-700 rounded-full"></div>
                        </div>
                        <motion.button 
                            style={{pointerEvents:'auto'}}
                            whileTap={{ scale: 0.9 }}
                            className="w-16 h-16 bg-gradient-to-tr from-brand-primary to-brand-secondary rounded-full flex items-center justify-center text-white shadow-glow hover:shadow-lg transition-shadow cursor-pointer"
                        >
                             <svg width="28" height="28" fill="none" stroke="currentColor" strokeWidth="3" viewBox="0 0 24 24"><path strokeLinecap="round" strokeLinejoin="round" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                        </motion.button>
                    </div>

                </div>
            );
        }

        /* * ------------------------------------------------------------------
         * ROOT RENDERER
         * ------------------------------------------------------------------
         */
        const root = ReactDOM.createRoot(document.getElementById('root'));
        root.render(
            <ThemeProvider>
                <App />
            </ThemeProvider>
        );
    </script>
<div id="royal-svip-container" dir="rtl">
    
    <style>
        /* -----------------------------------------------------------
           CSS - ROYAL SVIP ISOLATED STYLES
           ----------------------------------------------------------- */
        #royal-svip-container {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: normal;
            position: absolute;
            top: 0; left: 0;
            width: 0; height: 0;
        }
        
        /* دەرگا (Icon) - لە خوارەوەی شاشە */
        #vip-trigger-btn {
            position: fixed; bottom: 30px; right: 30px;
            width: 70px; height: 70px;
            background: radial-gradient(circle, #ffd700, #b8860b);
            border-radius: 50%; border: 3px solid #fff;
            box-shadow: 0 0 25px rgba(255, 215, 0, 0.8);
            z-index: 2147483647; /* بەرزترین لایەر */
            cursor: pointer; display: flex; align-items: center; justify-content: center;
            animation: royalFloat 3s ease-in-out infinite;
            transition: transform 0.3s;
        }
        #vip-trigger-btn:active { transform: scale(0.9); }
        
        @keyframes royalFloat { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); } }
        .vip-crown-icon { font-size: 35px; line-height: 1; filter: drop-shadow(0 2px 2px rgba(0,0,0,0.5)); }

        /* پەنجەرەی سەرەکی (Overlay) */
        #royal-svip-overlay {
            display: none; /* سەرەتا شاراوەیە */
            position: fixed; top: 0; left: 0; width: 100vw; height: 100vh;
            background: #000; z-index: 2147483647;
            overflow-y: auto; overflow-x: hidden;
        }

        /* گۆڕاوەکان */
        #royal-svip-overlay {
            --gold-pale: #fcf6ba; --gold-base: #bf953f; --gold-dark: #8a6e2f;
            --theme-color: #ffd700; --theme-glow: rgba(255, 215, 0, 0.5);
        }
        
        .royal-app {
            width: 100%; min-height: 100%;
            background: radial-gradient(circle at 50% 0%, #1a1a1a, #000000 80%);
            position: relative; color: white; text-align: center;
        }
        
        /* شێوەی تۆڕی پاشبنەما */
        .bg-texture {
            position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            background-image: linear-gradient(rgba(255, 215, 0, 0.03) 1px, transparent 1px),
                              linear-gradient(90deg, rgba(255, 215, 0, 0.03) 1px, transparent 1px);
            background-size: 30px 30px; pointer-events: none;
        }

        /* بەشی سەرەوە (Header) */
        .top-bar-royal {
            display: flex; justify-content: space-between; align-items: center;
            padding: 15px 20px; position: relative; z-index: 50; direction: ltr;
        }
        .nav-icon-royal {
            width: 40px; height: 40px; border-radius: 50%;
            background: rgba(255,255,255,0.1); display: flex; align-items: center; justify-content: center;
            border: 1px solid rgba(255,255,255,0.2); cursor: pointer; color: white; font-size: 18px;
        }
        .page-title-royal {
            font-weight: 900; font-size: 18px; letter-spacing: 2px; text-transform: uppercase;
            background: linear-gradient(to bottom, #fff, #ccc); -webkit-background-clip: text; -webkit-text-fill-color: transparent;
        }

        /* بەشی ئاڵا و وێنە (Banner System) */
        .banner-stage { position: relative; width: 100%; height: 380px; display: flex; justify-content: center; margin-top: -60px; z-index: 2;}
        
        .grand-flag {
            width: 90%; height: 100%;
            background: linear-gradient(180deg, #222 0%, #050505 100%);
            clip-path: polygon(0 0, 100% 0, 100% 88%, 50% 100%, 0 88%);
            position: relative; display: flex; flex-direction: column; align-items: center;
            box-shadow: 0 10px 50px rgba(0,0,0,0.8);
        }
        .grand-flag::before {
            content: ''; position: absolute; inset: 0; padding: 2px;
            background: linear-gradient(180deg, var(--theme-color), transparent 80%);
            -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
            -webkit-mask-composite: xor; mask-composite: exclude;
            clip-path: polygon(0 0, 100% 0, 100% 88%, 50% 100%, 0 88%); pointer-events: none;
        }
        
        .beast-container { width: 220px; height: 220px; margin-top: 80px; position: relative; z-index: 10; animation: floatBeast 4s ease-in-out infinite; }
        @keyframes floatBeast { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); } }
        .beast-img { width: 100%; height: 100%; object-fit: contain; filter: drop-shadow(0 0 30px var(--theme-glow)); }

        .level-headline {
            font-size: 42px; font-weight: 900; margin-top: -10px; position: relative; z-index: 12;
            background: linear-gradient(to bottom, #fff 10%, var(--theme-color) 50%, #8a6e2f 90%);
            -webkit-background-clip: text; -webkit-text-fill-color: transparent;
            filter: drop-shadow(0 4px 0px rgba(0,0,0,0.5)); letter-spacing: -1px;
        }

        /* بەشی هێڵی کەوانەیی (Orbit) */
        .orbit-system { position: relative; width: 100%; height: 80px; margin-top: -50px; z-index: 20; }
        .svg-curve { width: 100%; height: 100%; overflow: visible; }
        .curve-path { fill: none; stroke: rgba(255,255,255,0.15); stroke-width: 1.5; stroke-linecap: round; }
        
        .orbit-dot {
            position: absolute; width: 14px; height: 14px; background: #222;
            border: 1px solid #555; border-radius: 50%; transform: translate(-50%, -50%);
            cursor: pointer; transition: all 0.4s; box-shadow: 0 0 10px rgba(0,0,0,0.5);
        }
        .orbit-dot.active {
            width: 22px; height: 22px; background: radial-gradient(circle at 30% 30%, #fff, var(--theme-color));
            border: 2px solid #fff; box-shadow: 0 0 20px var(--theme-color); z-index: 22;
        }
        .dot-text {
            position: absolute; top: 28px; left: 50%; transform: translateX(-50%);
            font-size: 11px; color: #888; white-space: nowrap; font-weight: bold; opacity: 0; transition: opacity 0.3s;
        }
        .orbit-dot.active .dot-text { opacity: 1; color: var(--theme-color); }

        /* بەشی خاڵەکان (Stats) */
        .stats-panel { padding: 0 30px; margin-top: 10px; text-align: center; position: relative; z-index: 20; }
        .current-status { font-size: 14px; color: #aaa; margin-bottom: 8px; }
        .progress-wrapper { display: flex; flex-direction: column; gap: 5px; }
        .upgrade-label { display: flex; justify-content: flex-end; font-size: 12px; color: #666; font-weight: bold; }
        .bar-track { height: 8px; background: #111; border-radius: 4px; border: 1px solid #333; position: relative; }
        .bar-fill { height: 100%; width: 0%; background: linear-gradient(90deg, var(--gold-dark), var(--theme-color)); border-radius: 4px; position: relative; transition: width 0.6s ease; box-shadow: 0 0 10px var(--theme-color); }
        
        /* بەشی دیارییەکان (Grid) */
        .gifts-zone { padding: 30px 20px; position: relative; z-index: 20; }
        .royal-divider { display: flex; align-items: center; justify-content: center; gap: 15px; margin-bottom: 25px; }
        .wing-graphic { height: 2px; flex-grow: 1; background: linear-gradient(90deg, transparent, var(--theme-color), transparent); }
        .crown-center { width: 30px; height: 30px; background: url('https://img.icons8.com/emoji/48/crown-emoji.png') no-repeat center; background-size: contain; filter: drop-shadow(0 0 10px var(--theme-color)); }
        
        .rights-titles { display: flex; justify-content: space-between; margin-bottom: 15px; font-size: 12px; font-weight: 700; color: var(--theme-color); text-transform: uppercase; }
        .card-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; }
        
        .luxury-card {
            background: linear-gradient(145deg, rgba(30,30,30,0.95), rgba(10,10,10,0.98));
            border: 1px solid #333; border-radius: 12px; height: 110px;
            display: flex; flex-direction: column; align-items: center; justify-content: center;
            position: relative; transition: transform 0.3s; box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }
        .luxury-card.active-card { border-color: var(--theme-color); box-shadow: inset 0 0 20px rgba(255, 215, 0, 0.1), 0 0 10px rgba(255, 215, 0, 0.2); }
        
        .card-badge {
            background: linear-gradient(90deg, #111, #444); border: 1px solid var(--theme-color); color: white;
            padding: 4px 12px; border-radius: 8px 0 8px 0; font-size: 10px; font-weight: bold;
            box-shadow: 0 0 8px var(--theme-color); margin-bottom: 5px;
        }
        .frame-circle { width: 50px; height: 50px; border-radius: 50%; border: 2px solid var(--theme-color); position: relative; box-shadow: 0 0 15px var(--theme-color); }
        .entry-bar { width: 70%; height: 5px; background: linear-gradient(90deg, transparent, var(--theme-color), transparent); border-radius: 3px; box-shadow: 0 0 10px var(--theme-color); }
        .card-text { margin-top: 10px; font-size: 12px; color: #aaa; font-weight: 500; }
        
        .bottom-row { display: flex; gap: 10px; margin-top: 10px; }
        .wide-card { flex: 1; height: 90px; background: rgba(15, 15, 15, 0.9); border: 1px solid #222; border-radius: 12px; display: flex; flex-direction: column; align-items: center; justify-content: center; }
        .chat-bubble-preview { background: #222; border: 1px solid var(--theme-color); padding: 5px 20px; border-radius: 15px 15px 0 15px; color: white; font-size: 12px; }
        .aura-ring { width: 40px; height: 40px; border-radius: 50%; border: 2px dashed var(--theme-color); animation: spinRing 8s linear infinite; }
        @keyframes spinRing { 100% { transform: rotate(360deg); } }

        .deco-banner { position: absolute; top: 0; width: 24px; height: 280px; background: #111; border: 1px solid #333; border-top: none; z-index: 1; }
        .deco-left { left: 4px; clip-path: polygon(0 0, 100% 0, 100% 95%, 50% 100%, 0 95%); }
        .deco-right { right: 4px; clip-path: polygon(0 0, 100% 0, 100% 95%, 50% 100%, 0 95%); }
    </style>

    <div id="vip-trigger-btn" onclick="openRoyalSVIP()">
        <div class="vip-crown-icon">👑</div>
    </div>

    <div id="royal-svip-overlay">
        <div class="royal-app">
            <div class="bg-texture"></div>

            <div class="top-bar-royal">
                <div class="nav-icon-royal" onclick="closeRoyalSVIP()">✕</div>
                <div class="page-title-royal">SVIP CENTER</div>
                <div class="nav-icon-royal">🏠</div>
            </div>

            <div class="banner-stage">
                <div class="deco-banner deco-left"></div>
                <div class="deco-banner deco-right"></div>
                <div class="grand-flag">
                    <div class="beast-container">
                        <img id="mainBeast" src="https://cdn-icons-png.flaticon.com/512/2647/2647314.png" class="beast-img">
                    </div>
                    <div class="level-headline" id="lvlTitle">SVIP 5</div>
                </div>
            </div>

            <div class="orbit-system">
                <svg class="svg-curve" viewBox="0 0 360 80" preserveAspectRatio="none"><path class="curve-path" d="M0,20 Q180,90 360,20" /></svg>
                <div class="orbit-dot" style="left: 10%; top: 28px;" onclick="switchLevel(1)"><span class="dot-text">SVIP1</span></div>
                <div class="orbit-dot" style="left: 30%; top: 45px;" onclick="switchLevel(2)"><span class="dot-text">SVIP2</span></div>
                <div class="orbit-dot" style="left: 50%; top: 52px;" onclick="switchLevel(3)"><span class="dot-text">SVIP3</span></div>
                <div class="orbit-dot" style="left: 70%; top: 45px;" onclick="switchLevel(4)"><span class="dot-text">SVIP4</span></div>
                <div class="orbit-dot" style="left: 90%; top: 28px;" onclick="switchLevel(5)"><span class="dot-text">SVIP5</span></div>
            </div>

            <div class="stats-panel">
                <div class="current-status">ئێستا: <span id="statusTxt" style="color:white; font-weight:bold;">SVIP نییە</span></div>
                <div class="progress-wrapper">
                    <div class="upgrade-label">بەرزکردنەوە: S1 <span id="ptsTxt" style="margin-right:5px; color:#fff;">0/2M</span></div>
                    <div class="bar-track"><div class="bar-fill" id="fillBar"></div></div>
                </div>
                <div class="monthly-info" style="font-size: 11px; color: #666; margin-top: 5px;">باڵانس پڕکردنەوە لە ٣٠ ڕۆژی ڕابردوو: ٠</div>
            </div>

            <div class="gifts-zone">
                <div class="royal-divider"><div class="wing-graphic"></div><div class="crown-center"></div><div class="wing-graphic"></div></div>
                <div class="rights-titles"><span>مافەکانی جلوبەرگی SVIP</span><span>مافە باڵاکانی SVIP</span></div>
                <div class="card-grid">
                    <div class="luxury-card active-card"><div class="card-badge" id="badgeTxt">SVIP 5</div><div class="card-text">لۆگۆ</div></div>
                    <div class="luxury-card"><div class="frame-circle"></div><div class="card-text">چوارچێوە</div></div>
                    <div class="luxury-card"><div class="entry-bar"></div><div class="card-text">هاتنەژوورەوە</div></div>
                </div>
                <div class="bottom-row">
                    <div class="wide-card"><div class="chat-bubble-preview">سڵاو</div><div class="card-text">بڵقی چات</div></div>
                    <div class="wide-card"><div class="aura-ring"></div><div class="card-text">ئەڵقە</div></div>
                </div>
            </div>
            
            <div style="height: 50px;"></div>
        </div>
    </div>

    <script>
        const svipData = {
            1: { name: "SVIP 1", color: "#00e676", img: "https://cdn-icons-png.flaticon.com/512/616/616494.png", prog: "20%" },
            2: { name: "SVIP 2", color: "#2979ff", img: "https://cdn-icons-png.flaticon.com/512/616/616551.png", prog: "40%" },
            3: { name: "SVIP 3", color: "#d500f9", img: "https://cdn-icons-png.flaticon.com/512/616/616568.png", prog: "60%" },
            4: { name: "SVIP 4", color: "#ff1744", img: "https://cdn-icons-png.flaticon.com/512/616/616408.png", prog: "80%" },
            5: { name: "SVIP 5", color: "#ffd700", img: "https://cdn-icons-png.flaticon.com/512/616/616430.png", prog: "100%" }
        };

        function switchLevel(lvl) {
            const d = svipData[lvl];
            // Select only inside the container to prevent conflicts
            const container = document.getElementById('royal-svip-overlay');
            container.style.setProperty('--theme-color', d.color);
            container.style.setProperty('--theme-glow', d.color);
            
            document.getElementById('lvlTitle').innerText = d.name;
            document.getElementById('badgeTxt').innerText = d.name;
            document.getElementById('ptsTxt').innerText = (lvl === 5) ? "MAX" : "0/2M";
            
            const img = document.getElementById('mainBeast');
            img.style.opacity = 0; img.style.transform = "translateY(20px)";
            setTimeout(() => { img.src = d.img; img.style.opacity = 1; img.style.transform = "translateY(0px)"; }, 300);
            
            document.getElementById('fillBar').style.width = d.prog;
            document.getElementById('fillBar').style.background = d.color;
            
            const dots = document.querySelectorAll('.orbit-dot');
            dots.forEach((dot, idx) => {
                if ((idx + 1) === lvl) { 
                    dot.classList.add('active'); 
                    dot.style.background = `radial-gradient(circle at 30% 30%, #fff, ${d.color})`;
                    dot.style.boxShadow = `0 0 20px ${d.color}`;
                } else { 
                    dot.classList.remove('active'); 
                    dot.style.background = '#222';
                    dot.style.boxShadow = 'none';
                }
            });
        }

        function openRoyalSVIP() {
            document.getElementById('royal-svip-overlay').style.display = 'block';
            switchLevel(5);
        }

        function closeRoyalSVIP() {
            document.getElementById('royal-svip-overlay').style.display = 'none';
        }
    </script>
</div>

</body>
</html>
