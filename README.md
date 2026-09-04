<!DOCTYPE html>
<html class="scroll-smooth" lang="ne">
<head>
    <meta charset="utf-8" />
    <meta content="width=device-width, initial-scale=1.0" name="viewport" />
    <title>FB भिडियो डाउनलोडर - छिटो, नि:शुल्क र HD फेसबुक भिडियो डाउनलोडर</title>
    <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&display=swap" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet" />
    <style>
        @layer base {
            html,
            body {
                margin: 0;
                padding: 0;
            }
            body {
                overscroll-behavior: none;
            }
            main>:first-child {
                margin-top: 0 !important;
            }
            main>:last-child {
                margin-bottom: 0 !important;
            }
        }
        ::-webkit-scrollbar {
            display: none;
        }
    </style>
    <script src="https://cdn.tailwindcss.com">
    </script>
    <script id="tailwind-config">
        tailwind.config = {
            "darkMode": "class",
            "theme": {
                "extend": {
                    "colors": {
                        "tertiary": "#00628d",
                        "secondary": "#0051d5",
                        "surface-dim": "#d2d9f4",
                        "outline": "#727785",
                        "surface-variant": "#dae2fd",
                        "inverse-primary": "#adc6ff",
                        "primary-fixed-dim": "#adc6ff",
                        "surface-container-high": "#e2e7ff",
                        "secondary-fixed-dim": "#b4c5ff",
                        "surface-tint": "#005bc0",
                        "on-tertiary-fixed-variant": "#004c6e",
                        "surface-container": "#eaedff",
                        "on-tertiary-container": "#fcfcff",
                        "on-secondary-container": "#fefcff",
                        "tertiary-container": "#007cb1",
                        "tertiary-fixed-dim": "#89ceff",
                        "on-tertiary-fixed": "#001e2f",
                        "on-error": "#ffffff",
                        "surface": "#faf8ff",
                        "primary-fixed": "#d8e2ff",
                        "background": "#faf8ff",
                        "error": "#ba1a1a",
                        "on-secondary-fixed-variant": "#003ea8",
                        "on-primary-fixed": "#001a41",
                        "on-surface": "#131b2e",
                        "on-primary-container": "#fefcff",
                        "surface-container-lowest": "#ffffff",
                        "error-container": "#ffdad6",
                        "on-error-container": "#93000a",
                        "inverse-surface": "#283044",
                        "on-primary-fixed-variant": "#004493",
                        "on-secondary-fixed": "#00174b",
                        "secondary-fixed": "#dbe1ff",
                        "surface-container-highest": "#dae2fd",
                        "outline-variant": "#c1c6d6",
                        "surface-container-low": "#f2f3ff",
                        "on-tertiary": "#ffffff",
                        "on-background": "#131b2e",
                        "on-primary": "#ffffff",
                        "primary-container": "#0070eb",
                        "on-secondary": "#ffffff",
                        "secondary-container": "#316bf3",
                        "surface-bright": "#faf8ff",
                        "on-surface-variant": "#414754",
                        "tertiary-fixed": "#c9e6ff",
                        "primary": "#0058bc",
                        "inverse-on-surface": "#eef0ff"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "gutter-sm": "0.5rem",
                        "container-sm": "36rem",
                        "container-lg": "64rem",
                        "container-md": "48rem",
                        "gutter-xs": "0.25rem",
                        "container-max": "80rem",
                        "gutter-lg": "1.5rem",
                        "gutter-xl": "2rem",
                        "gutter-md": "1rem"
                    },
                    "fontFamily": {
                        "label-md": ["Inter"],
                        "headline-xl-mobile": ["Inter"],
                        "body-lg": ["Inter"],
                        "headline-xl": ["Inter"],
                        "body-md": ["Inter"],
                        "headline-lg-mobile": ["Inter"],
                        "headline-lg": ["Inter"],
                        "label-sm": ["Inter"],
                        "label-lg": ["Inter"],
                        "body-sm": ["Inter"],
                        "title-lg": ["Inter"],
                        "headline-md": ["Inter"]
                    },
                    "fontSize": {
                        "label-md": ["13px", { "lineHeight": "18px", "letterSpacing": "0.01em", "fontWeight": "600" }],
                        "headline-xl-mobile": ["32px", { "lineHeight": "40px", "letterSpacing": "-0.02em", "fontWeight": "800" }],
                        "body-lg": ["18px", { "lineHeight": "28px", "fontWeight": "400" }],
                        "headline-xl": ["44px", { "lineHeight": "52px", "letterSpacing": "-0.025em", "fontWeight": "800" }],
                        "body-md": ["15px", { "lineHeight": "24px", "fontWeight": "400" }],
                        "headline-lg-mobile": ["24px", { "lineHeight": "32px", "letterSpacing": "-0.015em", "fontWeight": "700" }],
                        "headline-lg": ["32px", { "lineHeight": "40px", "letterSpacing": "-0.02em", "fontWeight": "700" }],
                        "label-sm": ["11px", { "lineHeight": "16px", "letterSpacing": "0.03em", "fontWeight": "600" }],
                        "label-lg": ["15px", { "lineHeight": "20px", "letterSpacing": "-0.005em", "fontWeight": "600" }],
                        "body-sm": ["13px", { "lineHeight": "20px", "fontWeight": "400" }],
                        "title-lg": ["18px", { "lineHeight": "26px", "letterSpacing": "-0.01em", "fontWeight": "600" }],
                        "headline-md": ["22px", { "lineHeight": "30px", "letterSpacing": "-0.015em", "fontWeight": "600" }]
                    }
                }
            }
        };
    </script>
</head>

<body class="bg-background font-body-md text-on-surface antialiased min-h-screen relative flex flex-col">
    <div class="pointer-events-none absolute top-0 left-1/2 -translate-x-1/2 w-full max-w-container-max h-[420px] bg-[radial-gradient(ellipse_at_top,_rgba(0,112,235,0.12)_0%,_rgba(250,248,255,0)_70%)] z-0"></div>

    <!-- Header -->
    <header class="fixed top-0 left-0 right-0 w-full z-50 bg-surface/80 backdrop-blur-xl shadow-[0_1px_8px_rgba(0,0,0,0.04)]">
        <div class="max-w-container-max mx-auto px-gutter-md lg:px-gutter-xl h-16 flex items-center justify-between gap-4">
            <div class="flex items-center gap-3">
                <a class="flex items-center gap-2.5 transition-transform hover:opacity-90" data-path="home" href="#">
                    <img alt="FB भिडियो डाउनलोडर लोगो" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/AEtjO1X30kDYpDeUfOOi0uCcOzgbgSQfPnJFcqvDHTOJx1XKsl5PO9039qN3W_V1LfTVaESH3AuMUrYS-sHDsPv2HH2tyB4F2yTeNH-XWeeWTL62_goQxxYFEeJeoYgcJvlntkiGD-y_ncPyMB7h2xnx07TpTDQZjxJ9KjBUQ5nsTouuWQbPGa2GmoEfjb2TvjWBgvqgJGDhPgxIOZKYnhiRauNITKChLB4xg14tU2lp5pnBiLpSI51efaYjq3o" />
                    <span class="font-title-lg text-title-lg text-primary tracking-tight">FB डाउनलोडर</span>
                </a>
                <span class="hidden sm:inline-flex items-center px-2 py-0.5 rounded-full bg-surface-container-high text-primary text-label-sm font-label-sm uppercase tracking-wider">छिटो HD</span>
            </div>

            <nav class="hidden md:flex items-center gap-1 lg:gap-2" data-active-classes="bg-primary-container text-on-primary-container rounded-lg">
                <a aria-current="page" class="px-3 py-1.5 font-label-md transition-colors bg-primary-container text-on-primary-container rounded-lg" data-path="home" href="#">गृह पृष्ठ</a>
                <a class="px-3 py-1.5 rounded-lg text-on-surface-variant font-label-md text-label-md transition-colors hover:bg-surface-container hover:text-on-surface" data-path="how-it-works" href="#">कसरी काम गर्छ</a>
                <a class="px-3 py-1.5 rounded-lg text-on-surface-variant font-label-md text-label-md transition-colors hover:bg-surface-container hover:text-on-surface" data-path="features" href="#">विशेषताहरू</a>
                <a class="px-3 py-1.5 rounded-lg text-on-surface-variant font-label-md text-label-md transition-colors hover:bg-surface-container hover:text-on-surface" data-path="video-formats" href="#">फर्म्याटहरू</a>
                <a class="px-3 py-1.5 rounded-lg text-on-surface-variant font-label-md text-label-md transition-colors hover:bg-surface-container hover:text-on-surface" data-path="faq" href="#">सोधिने प्रश्नहरू</a>
                <a class="px-3 py-1.5 rounded-lg text-on-surface-variant font-label-md text-label-md transition-colors hover:bg-surface-container hover:text-on-surface" data-path="about" href="#">हाम्रो बारेमा</a>
            </nav>

            <div class="flex items-center gap-3">
                <a class="hidden sm:inline-flex items-center gap-1.5 px-3.5 py-1.5 rounded-lg bg-primary text-on-primary font-label-md text-label-md shadow-sm transition-all hover:bg-primary-container hover:text-on-primary-container" data-path="home" href="#">
                    <span class="material-symbols-outlined text-[18px]">content_paste_go</span>
                    <span>टास्नुहोस् र जानुहोस्</span>
                </a>
                <div class="w-8 h-8 rounded-full bg-primary flex items-center justify-center">
                    <span class="material-symbols-outlined text-on-primary text-[18px]">person</span>
                </div>
                <details class="md:hidden relative group">
                    <summary class="list-none cursor-pointer p-1.5 rounded-lg text-on-surface-variant hover:bg-surface-container hover:text-on-surface flex items-center justify-center">
                        <span class="material-symbols-outlined text-[24px]">menu</span>
                    </summary>
                    <div class="absolute right-0 top-full mt-2 w-56 p-2 bg-surface-container-lowest rounded-xl shadow-[0_10px_25px_-5px_rgba(24,119,242,0.12)] flex flex-col gap-1 z-50">
                        <a class="px-3 py-2 rounded-lg text-on-surface-variant font-label-md text-label-md hover:bg-surface-container hover:text-on-surface transition-colors" data-path="home" href="#">गृह पृष्ठ</a>
                        <a class="px-3 py-2 rounded-lg text-on-surface-variant font-label-md text-label-md hover:bg-surface-container hover:text-on-surface transition-colors" data-path="how-it-works" href="#">कसरी काम गर्छ</a>
                        <a class="px-3 py-2 rounded-lg text-on-surface-variant font-label-md text-label-md hover:bg-surface-container hover:text-on-surface transition-colors" data-path="features" href="#">विशेषताहरू</a>
                        <a class="px-3 py-2 rounded-lg text-on-surface-variant font-label-md text-label-md hover:bg-surface-container hover:text-on-surface transition-colors" data-path="video-formats" href="#">भिडियो फर्म्याटहरू</a>
                        <a class="px-3 py-2 rounded-lg text-on-surface-variant font-label-md text-label-md hover:bg-surface-container hover:text-on-surface transition-colors" data-path="faq" href="#">सोधिने प्रश्नहरू</a>
                        <a class="px-3 py-2 rounded-lg text-on-surface-variant font-label-md text-label-md hover:bg-surface-container hover:text-on-surface transition-colors" data-path="about" href="#">हाम्रो बारेमा</a>
                        <div class="h-px bg-surface-variant my-1"></div>
                        <a class="px-3 py-1.5 rounded-lg text-on-surface-variant font-body-sm text-body-sm hover:bg-surface-container hover:text-on-surface transition-colors" data-path="privacy-policy" href="#">गोपनीयता नीति</a>
                        <a class="px-3 py-1.5 rounded-lg text-on-surface-variant font-body-sm text-body-sm hover:bg-surface-container hover:text-on-surface transition-colors" data-path="terms-of-service" href="#">सेवा सर्तहरू</a>
                    </div>
                </details>
            </div>
        </div>
    </header>

    <main class="w-full pt-16 relative z-10 flex-grow">
        <div class="flex flex-col w-full">

            <!-- Toast Notification Overlay -->
            <div class="fixed bottom-6 right-6 z-50 transform translate-y-20 opacity-0 transition-all duration-300 pointer-events-none flex items-center gap-3 px-4 py-3 rounded-xl bg-inverse-surface text-inverse-on-surface shadow-xl" id="toastNotification">
                <span class="material-symbols-outlined text-primary-fixed-dim text-[20px]" id="toastIcon">check_circle</span>
                <span class="font-label-md text-label-md" id="toastMessage">लिङ्क क्लिपबोर्डमा प्रतिलिपि गरियो</span>
            </div>

            <!-- Hero Section -->
            <section class="relative w-full pt-10 pb-16 px-gutter-md lg:px-gutter-xl flex flex-col items-center overflow-hidden">
                <div class="absolute -top-24 left-1/2 -translate-x-1/2 w-[720px] h-[340px] bg-primary/10 rounded-full blur-3xl pointer-events-none -z-10"></div>
                <div class="absolute top-48 right-10 w-72 h-72 bg-tertiary/10 rounded-full blur-3xl pointer-events-none -z-10"></div>

                <div class="w-full max-w-container-md mx-auto flex flex-col items-center text-center">
                    <!-- Trust Badge -->
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-surface-container-high text-primary mb-6 shadow-sm hover:bg-surface-container-highest transition-colors cursor-default">
                        <span class="material-symbols-outlined text-[16px] text-primary" style="font-variation-settings: 'FILL' 1;">bolt</span>
                        <span class="font-label-sm text-label-sm uppercase tracking-wider font-semibold">१००% नि:शुल्क र छिटो · कुनै दर्ता आवश्यक छैन · १०८०p सम्म HD</span>
                    </div>

                    <!-- Main Headline -->
                    <h1 class="font-headline-xl text-headline-xl text-on-surface tracking-tight mb-4 max-w-2xl">
                        <span class="text-primary font-extrabold">फेसबुक भिडियोहरू</span> सजिलै डाउनलोड गर्नुहोस्
                    </h1>
                    <p class="font-body-lg text-body-lg text-on-surface-variant max-w-xl mb-8">
                        कुनै पनि सार्वजनिक फेसबुक भिडियो, रिल, वा स्टोरीको लिङ्क टास्नुहोस् र यसलाई मौलिक HD गुणस्तरमा आफ्नो यन्त्रमा सफाईपूर्वक डाउनलोड गर्नुहोस्।
                    </p>

                    <!-- Input Hub Card -->
                    <div class="w-full bg-surface-container-lowest rounded-2xl p-2.5 sm:p-3.5 shadow-xl transition-all relative">
                        <div class="hidden absolute top-0 left-0 right-0 h-1 bg-primary/20 overflow-hidden rounded-t-2xl" id="shimmerLoadingBar">
                            <div class="h-full bg-primary animate-[shimmer_1.4s_infinite_linear] w-1/3"></div>
                        </div>

                        <form class="flex flex-col sm:flex-row items-center gap-2.5 w-full" id="downloadForm" onsubmit="return false;">
                            <div class="relative flex-1 w-full flex items-center bg-surface-container-low rounded-xl px-3.5 h-14 transition-all focus-within:bg-surface-container-lowest focus-within:shadow-md">
                                <span class="material-symbols-outlined text-outline text-[22px] mr-2.5 select-none" id="inputPrefixIcon">link</span>
                                <input autocomplete="off" class="w-full bg-transparent border-none outline-none font-body-md text-body-md text-on-surface placeholder:text-outline/70 focus:ring-0" id="videoUrlInput" placeholder="फेसबुक भिडियो URL यहाँ टास्नुहोस् (जस्तै: facebook.com/watch?v=...)" spellcheck="false" type="text" />
                                <button class="hidden p-1.5 rounded-full text-outline hover:text-on-surface hover:bg-surface-container transition-colors" id="clearBtn" title="इनपुट खाली गर्नुहोस्" type="button">
                                    <span class="material-symbols-outlined text-[18px]">close</span>
                                </button>
                                <button class="ml-1 px-2.5 py-1 rounded-lg bg-surface-container-high text-on-surface-variant hover:text-primary hover:bg-surface-container-highest font-label-sm text-label-sm flex items-center gap-1 transition-all" id="pasteBtn" type="button">
                                    <span class="material-symbols-outlined text-[15px]">content_paste</span>
                                    <span>टास्नुहोस्</span>
                                </button>
                            </div>
                            <button class="w-full sm:w-auto h-14 px-7 rounded-xl bg-primary text-on-primary font-label-lg text-label-lg flex items-center justify-center gap-2 shadow-md hover:bg-primary-container active:scale-[0.98] transition-all flex-shrink-0" id="fetchBtn" type="submit">
                                <span class="material-symbols-outlined text-[20px]" id="fetchBtnIcon">download</span>
                                <span id="fetchBtnText">भिडियो डाउनलोड गर्नुहोस्</span>
                            </button>
                        </form>

                        <div class="mt-3 flex flex-wrap items-center justify-between gap-2 px-1 text-on-surface-variant font-body-sm text-body-sm">
                            <div class="flex items-center gap-1.5">
                                <span class="material-symbols-outlined text-outline text-[16px]">verified_user</span>
                                <span>कुनै कुकी भण्डार गरिँदैन। कुनै दर्ता आवश्यक छैन।</span>
                            </div>
                            <button class="inline-flex items-center gap-1 text-primary hover:text-primary-container font-label-md text-label-md transition-colors group cursor-pointer" id="sampleLinkBtn" type="button">
                                <span>नमूना भिडियो लिङ्क प्रयास गर्नुहोस्</span>
                                <span class="material-symbols-outlined text-[16px] group-hover:translate-x-0.5 transition-transform">arrow_forward</span>
                            </button>
                        </div>

                        <!-- Validation Error Card -->
                        <div class="hidden mt-3 p-3.5 rounded-xl bg-error-container text-on-error-container text-left flex items-start gap-3" id="validationError">
                            <span class="material-symbols-outlined text-error text-[20px] flex-shrink-0 mt-0.5">error</span>
                            <div class="flex-1">
                                <p class="font-label-md text-label-md text-error mb-0.5" id="errorTitle">अमान्य फेसबुक लिङ्क</p>
                                <p class="font-body-sm text-body-sm opacity-90" id="errorMessage">कृपया एउटा सार्वजनिक फेसबुक URL प्रदान गर्नुहोस् (जस्तै: facebook.com/watch?v=..., fb.watch/..., वा facebook.com/reel/...)।</p>
                            </div>
                            <button class="text-on-error-container/75 hover:text-on-error-container p-1" id="dismissErrorBtn" type="button">
                                <span class="material-symbols-outlined text-[18px]">close</span>
                            </button>
                        </div>
                    </div>

                    <!-- Dynamic Loading Status Node -->
                    <div class="hidden mt-6 w-full max-w-container-md bg-surface-container-low rounded-2xl p-6 shadow-sm flex flex-col items-center justify-center gap-4 animate-fade-in" id="loadingStatusCard">
                        <div class="relative w-12 h-12 flex items-center justify-center">
                            <div class="w-12 h-12 rounded-full border-4 border-surface-container-highest border-t-primary animate-spin"></div>
                            <span class="material-symbols-outlined text-primary text-[20px] absolute">cloud_sync</span>
                        </div>
                        <div class="text-center">
                            <h3 class="font-title-lg text-title-lg text-on-surface" id="loadingStageTitle">फेसबुक भिडियो स्ट्रिम विश्लेषण गर्दै</h3>
                            <p class="font-body-sm text-body-sm text-on-surface-variant mt-1" id="loadingStageSubtitle">फेसबुक मिडिया एन्डपोइन्टहरूमा जडान गर्दै र उपलब्ध रिजोलुसनहरू खोज्दै...</p>
                        </div>
                        <div class="w-full max-w-xs bg-surface-container-highest rounded-full h-2 overflow-hidden">
                            <div class="bg-primary h-full w-1/4 rounded-full transition-all duration-300" id="loadingProgressBar"></div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Result / Media Extractor Card Section -->
            <section class="w-full px-gutter-md lg:px-gutter-xl pb-16" id="resultSection">
                <div class="max-w-container-md mx-auto bg-surface-container-lowest rounded-2xl shadow-xl overflow-hidden">
                    <div class="px-6 py-4 bg-surface-container-low flex items-center justify-between flex-wrap gap-3">
                        <div class="flex items-center gap-2">
                            <span class="w-2.5 h-2.5 rounded-full bg-emerald-500 animate-pulse"></span>
                            <span class="font-label-md text-label-md text-on-surface">भिडियो सफलतापूर्वक निकालियो</span>
                            <span class="px-2 py-0.5 rounded-md bg-primary-fixed text-on-primary-fixed font-label-sm text-label-sm uppercase">१०८०p तयार</span>
                        </div>
                        <button class="inline-flex items-center gap-1.5 px-3 py-1 rounded-lg bg-surface-container text-on-surface-variant hover:text-on-surface hover:bg-surface-container-high font-label-md text-label-md transition-colors" id="resetSearchBtn" type="button">
                            <span class="material-symbols-outlined text-[16px]">refresh</span>
                            <span>अर्को डाउनलोड गर्नुहोस्</span>
                        </button>
                    </div>

                    <div class="p-6 grid grid-cols-1 md:grid-cols-12 gap-6">
                        <!-- Thumbnail Preview Pane -->
                        <div class="md:col-span-5 flex flex-col gap-3">
                            <div class="relative w-full aspect-video rounded-xl overflow-hidden bg-surface-container shadow-sm group">
                                <img class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" data-alt="सिनेमेटिक उच्च गुणस्तरको परिदृश्य पूर्वावलोकन" id="resultThumbnail" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCA82v364hSU_6yuSBRf7prTyFOFtx2IaLIJcLHrQM96oE9fd36LzRRvleZOBuDNjWzvMGkX0jQ3z9g2g98brQEG1x6AzHOlkhytNqrfIZoHGBL8BqB5a2B09dGN3nt84fz3BLVmTUf1Yh_HLLtQ4nft7sWf5K3I-HRjkzYothrPNJXEynSE-UZm79HmgW43atzvI8M-2Kj2iMTppsY9Qe5exlnW51hIX-BFfU5IWcb9ISZ4YOLRQZQ" />
                                <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-black/20 pointer-events-none"></div>
                                <div class="absolute top-3 left-3 px-2 py-0.5 rounded bg-primary text-on-primary font-label-sm text-label-sm tracking-wide uppercase font-bold shadow-sm">
                                    HD १०८०p
                                </div>
                                <div class="absolute bottom-3 right-3 px-2 py-0.5 rounded bg-black/80 text-white font-label-sm text-label-sm backdrop-blur-sm" id="resultDuration">
                                    ०२:४५
                                </div>
                                <div class="absolute inset-0 flex items-center justify-center">
                                    <div class="w-12 h-12 rounded-full bg-surface-container-lowest/90 text-primary flex items-center justify-center shadow-lg group-hover:scale-110 transition-transform">
                                        <span class="material-symbols-outlined text-[28px] ml-0.5" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
                                    </div>
                                </div>
                            </div>

                            <div class="p-3 rounded-xl bg-surface-container-low flex items-center justify-between">
                                <div class="flex items-center gap-2.5 min-w-0">
                                    <div class="w-8 h-8 rounded-full bg-primary-container text-on-primary-container flex items-center justify-center font-bold text-label-md flex-shrink-0">
                                        N
                                    </div>
                                    <div class="min-w-0">
                                        <p class="font-label-md text-label-md text-on-surface truncate" id="resultChannel">नेचर एण्ड टेक हब</p>
                                        <p class="font-body-sm text-body-sm text-on-surface-variant">सार्वजनिक फेसबुक रिल</p>
                                    </div>
                                </div>
                                <span class="material-symbols-outlined text-primary text-[20px]">verified</span>
                            </div>
                        </div>

                        <!-- Download Resolution Options Pane -->
                        <div class="md:col-span-7 flex flex-col justify-between">
                            <div>
                                <h2 class="font-title-lg text-title-lg text-on-surface mb-2 leading-snug line-clamp-2" id="resultTitle">
                                    अद्भुत परिदृश्य ड्रोन क्याप्चर र सिनेमेटिक हाइलाइट्स २०२६
                                </h2>
                                <div class="flex flex-wrap items-center gap-2 mb-4">
                                    <span class="px-2.5 py-1 rounded-full bg-surface-container font-label-sm text-label-sm text-on-surface-variant">फर्म्याट: MP4</span>
                                    <span class="px-2.5 py-1 rounded-full bg-surface-container font-label-sm text-label-sm text-on-surface-variant">अडियो: ३२०kbps उच्च</span>
                                    <span class="px-2.5 py-1 rounded-full bg-surface-container font-label-sm text-label-sm text-on-surface-variant">सर्भर: सुपरस्पीड US</span>
                                </div>
                            </div>

                            <div class="flex flex-col gap-2">
                                <span class="font-label-sm text-label-sm text-outline uppercase tracking-wider font-bold">डाउनलोड गुणस्तर छनौट गर्नुहोस्</span>

                                <!-- 1080p FHD Option -->
                                <div class="p-3 rounded-xl bg-surface-container-low hover:bg-surface-container transition-colors flex items-center justify-between gap-3">
                                    <div class="flex items-center gap-3">
                                        <div class="w-9 h-9 rounded-lg bg-primary/10 text-primary flex items-center justify-center font-bold text-label-sm">
                                            १०८०p
                                        </div>
                                        <div>
                                            <div class="flex items-center gap-2">
                                                <span class="font-label-md text-label-md text-on-surface">पूर्ण HD १०८०p</span>
                                                <span class="px-1.5 py-0.5 rounded bg-primary-container/20 text-primary font-label-sm text-label-sm font-semibold">उत्कृष्ट</span>
                                            </div>
                                            <span class="font-body-sm text-body-sm text-on-surface-variant">MP4 फर्म्याट · ~४२.८ MB</span>
                                        </div>
                                    </div>
                                    <button class="download-trigger-btn px-3.5 py-1.5 rounded-lg bg-primary text-on-primary font-label-md text-label-md hover:bg-primary-container shadow-sm flex items-center gap-1.5 active:scale-95 transition-all" data-filename="facebook_video_1080p.mp4" data-quality="1080p" type="button">
                                        <span class="material-symbols-outlined text-[17px]">download</span>
                                        <span>डाउनलोड</span>
                                    </button>
                                </div>

                                <!-- 720p HD Option -->
                                <div class="p-3 rounded-xl bg-surface-container-low hover:bg-surface-container transition-colors flex items-center justify-between gap-3">
                                    <div class="flex items-center gap-3">
                                        <div class="w-9 h-9 rounded-lg bg-surface-container-high text-on-surface flex items-center justify-center font-bold text-label-sm">
                                            ७२०p
                                        </div>
                                        <div>
                                            <span class="font-label-md text-label-md text-on-surface">उच्च परिभाषा ७२०p</span>
                                            <p class="font-body-sm text-body-sm text-on-surface-variant">MP4 फर्म्याट · ~२४.१ MB</p>
                                        </div>
                                    </div>
                                    <button class="download-trigger-btn px-3.5 py-1.5 rounded-lg bg-surface-container-highest text-on-surface font-label-md text-label-md hover:bg-primary hover:text-on-primary shadow-sm flex items-center gap-1.5 active:scale-95 transition-all" data-filename="facebook_video_720p.mp4" data-quality="720p" type="button">
                                        <span class="material-symbols-outlined text-[17px]">download</span>
                                        <span>डाउनलोड</span>
                                    </button>
                                </div>

                                <!-- 480p SD Option -->
                                <div class="p-3 rounded-xl bg-surface-container-low hover:bg-surface-container transition-colors flex items-center justify-between gap-3">
                                    <div class="flex items-center gap-3">
                                        <div class="w-9 h-9 rounded-lg bg-surface-container-high text-on-surface flex items-center justify-center font-bold text-label-sm">
                                            ४८०p
                                        </div>
                                        <div>
                                            <span class="font-label-md text-label-md text-on-surface">मानक गुणस्तर ४८०p</span>
                                            <p class="font-body-sm text-body-sm text-on-surface-variant">MP4 फर्म्याट · ~१३.५ MB</p>
                                        </div>
                                    </div>
                                    <button class="download-trigger-btn px-3.5 py-1.5 rounded-lg bg-surface-container-highest text-on-surface font-label-md text-label-md hover:bg-primary hover:text-on-primary shadow-sm flex items-center gap-1.5 active:scale-95 transition-all" data-filename="facebook_video_480p.mp4" data-quality="480p" type="button">
                                        <span class="material-symbols-outlined text-[17px]">download</span>
                                        <span>डाउनलोड</span>
                                    </button>
                                </div>

                                <!-- MP3 Audio Extract Option -->
                                <div class="p-3 rounded-xl bg-secondary-fixed/30 hover:bg-secondary-fixed/50 transition-colors flex items-center justify-between gap-3">
                                    <div class="flex items-center gap-3">
                                        <div class="w-9 h-9 rounded-lg bg-secondary-container text-on-secondary-container flex items-center justify-center">
                                            <span class="material-symbols-outlined text-[18px]">music_note</span>
                                        </div>
                                        <div>
                                            <div class="flex items-center gap-1.5">
                                                <span class="font-label-md text-label-md text-on-surface">अडियो MP3 मात्र</span>
                                                <span class="px-1.5 py-0.5 rounded bg-secondary-fixed text-on-secondary-fixed font-label-sm text-label-sm font-semibold">३२०k</span>
