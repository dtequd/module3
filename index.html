<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DTEQ — Module 3</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
<style>
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

:root {
  --black:   #0C0C0C;
  --black2:  #111111;
  --surface: #161616;
  --border:  #222222;
  --border2: #2a2a2a;
  --muted:   #555555;
  --mid:     #888888;
  --text:    #CCCCCC;
  --white:   #EFEFEF;
  --acid:    #C8FF00;
  --acid2:   #A8D800;
}

html { scroll-behavior: smooth; }

body {
  background: var(--black);
  color: var(--text);
  font-family: 'Inter', sans-serif;
  font-size: 15px;
  line-height: 1.65;
  min-height: 100vh;
  overflow-x: hidden;
}

/* ── BOTTOM TAB BAR ── */
.tab-bar {
  position: fixed;
  bottom: 0; left: 0; right: 0;
  z-index: 200;
  background: #0a0a0a;
  border-top: 1px solid var(--border);
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
}

.tab-btn {
  background: none;
  border: none;
  border-right: 1px solid var(--border);
  cursor: pointer;
  padding: 14px 28px;
  text-align: left;
  transition: background 0.15s;
  display: flex;
  flex-direction: column;
  gap: 3px;
}

.tab-btn:last-child { border-right: none; }
.tab-btn:hover { background: rgba(200,255,0,0.04); }

.tab-btn .t-label {
  font-family: 'Inter', sans-serif;
  font-size: 11px;
  color: var(--mid);
  letter-spacing: 0.08em;
  transition: color 0.15s;
}

.tab-btn .t-sub {
  font-family: 'Inter', sans-serif;
  font-size: 13px;
  font-weight: 400;
  color: var(--muted);
  letter-spacing: 0.05em;
  transition: color 0.15s;
}

.tab-btn.active .t-label { color: var(--acid); }
.tab-btn.active .t-sub   { color: var(--acid2); }

/* ── HERO ── */
.hero {
  min-height: 100vh;
  padding: 52px 60px 120px;
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  overflow: visible;
}

.hero-ghost {
  position: absolute;
  right: -40px;
  top: 50%;
  transform: translateY(-55%);
  font-family: 'Inter', sans-serif;
  font-size: clamp(180px, 25vw, 300px);
  font-weight: 900;
  color: transparent;
  -webkit-text-stroke: 1px rgba(255,255,255,0.045);
  line-height: 1;
  pointer-events: none;
  user-select: none;
  letter-spacing: -0.02em;
}

.hero-grid-overlay {
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(rgba(255,255,255,0.018) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.018) 1px, transparent 1px);
  background-size: 80px 80px;
  pointer-events: none;
}

.hero-top {
  position: relative;
  z-index: 1;
}

.hero-eyebrow {
  font-family: 'Inter', sans-serif;
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--mid);
  margin-bottom: 24px;
}

.hero-title {
  font-family: 'Inter', sans-serif;
  font-weight: 900;
  font-size: clamp(56px, 9vw, 120px);
  line-height: 0.88;
  letter-spacing: -0.01em;
  text-transform: uppercase;
  color: var(--white);
  margin-bottom: 0;
}

.hero-title .accent {
  color: var(--acid);
  display: block;
}

.hero-sub {
  margin-top: 32px;
  max-width: 420px;
  font-size: 14px;
  font-weight: 300;
  color: var(--mid);
  line-height: 1.7;
}

.hero-bottom {
  position: relative;
  z-index: 1;
}

.day-strip {
  border-top: 1px solid var(--border2);
  padding-top: 20px;
  display: flex;
  align-items: baseline;
  justify-content: space-between;
}

.day-strip-label {
  font-family: 'Inter', sans-serif;
  font-size: 12px;
  letter-spacing: 0.18em;
  color: var(--acid);
  display: flex;
  align-items: center;
  gap: 16px;
}

.day-strip-label::after {
  content: '';
  display: block;
  width: min(500px, 40vw);
  height: 1px;
  background: var(--border2);
}

.day-strip-meta {
  font-family: 'Inter', sans-serif;
  font-size: 11px;
  letter-spacing: 0.14em;
  color: var(--muted);
}

.day-strip-heading {
  font-family: 'Inter', sans-serif;
  font-size: clamp(28px, 4vw, 48px);
  font-weight: 800;
  color: var(--white);
  text-transform: uppercase;
  letter-spacing: -0.01em;
  margin-top: 4px;
  white-space: normal;
  overflow: visible;
}

/* ── PAGE BODY ── */
.page-body {
  padding: 0 60px 120px;
}

.day-panel { display: none; }
.day-panel.active { display: block; }

/* ── LESSON ── */
.lesson {
  padding: 64px 0;
  border-top: 1px solid var(--border);
  scroll-margin-top: 0;
}

.lesson-meta-row {
  display: flex;
  align-items: center;
  gap: 20px;
  margin-bottom: 20px;
}

.lesson-index {
  font-family: 'Inter', sans-serif;
  font-size: 11px;
  letter-spacing: 0.18em;
  color: var(--acid);
}

.lesson-line {
  flex: 1;
  height: 1px;
  background: var(--border);
}

.lesson-title {
  font-family: 'Inter', sans-serif;
  font-size: clamp(22px, 3vw, 34px);
  font-weight: 800;
  color: var(--white);
  letter-spacing: -0.01em;
  line-height: 1;
  margin-bottom: 40px;
}

/* ── VIDEO BLOCK ── */
.video-wrap {
  position: relative;
  aspect-ratio: 16/9;
  background: var(--surface);
  border: 1px solid var(--border2);
  margin-bottom: 2px;
  overflow: visible;
  cursor: pointer;
}

.video-wrap::before {
  content: '';
  position: absolute;
  inset: 0;
  background:
    repeating-linear-gradient(
      -45deg,
      transparent,
      transparent 60px,
      rgba(200,255,0,0.012) 60px,
      rgba(200,255,0,0.012) 61px
    );
}

.video-wrap.has-embed::before { display: none; }

.video-wrap iframe {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  border: 0;
}

.video-center {
  position: absolute;
  inset: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 16px;
  z-index: 1;
}

.play-ring {
  width: 72px; height: 72px;
  border: 1.5px solid rgba(200,255,0,0.4);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: border-color 0.2s, background 0.2s;
}

.video-wrap:hover .play-ring {
  border-color: var(--acid);
  background: rgba(200,255,0,0.08);
}

.play-ring svg { margin-left: 5px; }

.video-caption-mono {
  font-family: 'Inter', sans-serif;
  font-size: 11px;
  letter-spacing: 0.14em;
  color: var(--muted);
  text-transform: uppercase;
}

.video-footer {
  background: var(--surface);
  border: 1px solid var(--border2);
  border-top: none;
  padding: 12px 18px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 24px;
}

.vf-title {
  font-family: 'Inter', sans-serif;
  font-size: 13px;
  font-weight: 600;
  letter-spacing: 0.02em;
  color: var(--text);
}

.vf-dur {
  font-family: 'Inter', sans-serif;
  font-size: 11px;
  color: var(--muted);
}

/* ── STEPS ── */
.steps-label {
  font-family: 'Inter', sans-serif;
  font-size: 10px;
  letter-spacing: 0.22em;
  color: var(--muted);
  text-transform: uppercase;
  margin-bottom: 0;
  border-top: 1px solid var(--border);
  padding-top: 20px;
}

.step {
  display: grid;
  grid-template-columns: 48px 1fr;
  gap: 0;
  border-bottom: 1px solid var(--border);
}

.step-num {
  padding: 22px 0 22px 0;
  font-family: 'Inter', sans-serif;
  font-size: 11px;
  color: var(--muted);
  border-right: 1px solid var(--border);
  display: flex;
  align-items: flex-start;
  justify-content: center;
  padding-top: 24px;
}

.step-content {
  padding: 22px 0 22px 24px;
  transition: background 0.15s;
}

.step:hover .step-content { background: rgba(255,255,255,0.012); }

.step-title {
  font-family: 'Inter', sans-serif;
  font-size: 16px;
  font-weight: 700;
  letter-spacing: 0.01em;
  color: var(--white);
  margin-bottom: 8px;
}

.step-desc {
  font-size: 14px;
  font-weight: 300;
  color: var(--mid);
  line-height: 1.75;
  max-width: 680px;
}

.step-img {
  margin-top: 14px;
  width: 100%;
  max-width: 640px;
  aspect-ratio: 16/6;
  background: var(--surface);
  border: 1px solid var(--border2);
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: 'Inter', sans-serif;
  font-size: 10px;
  letter-spacing: 0.1em;
  color: var(--muted);
  text-transform: uppercase;
}

.tip {
  display: flex;
  gap: 16px;
  align-items: flex-start;
  padding: 16px 20px;
  background: rgba(200,255,0,0.04);
  border: 1px solid rgba(200,255,0,0.12);
  border-left: 3px solid var(--acid);
  margin-top: 24px;
}

.tip-mark {
  font-family: 'Inter', sans-serif;
  font-size: 10px;
  letter-spacing: 0.14em;
  color: var(--acid);
  white-space: normal;
  margin-top: 2px;
}

.tip-text {
  font-size: 12px;
  font-weight: 300;
  color: var(--mid);
  line-height: 1.7;
}

.tip-text strong { color: var(--acid); font-weight: 500; }

/* ── SCROLLBAR ── */
::-webkit-scrollbar { width: 4px; }
::-webkit-scrollbar-track { background: var(--black); }
::-webkit-scrollbar-thumb { background: var(--border2); border-radius: 2px; }

@media (max-width: 768px) {
  .hero { padding: 40px 24px 120px; }
  .page-body { padding: 0 24px 120px; }
  .hero-ghost { display: none; }
  .day-strip-heading { font-size: 32px; }
  .tab-btn { padding: 12px 16px; }
}
</style>
</head>
<body>

<!-- ── HERO ── -->
<section class="hero" id="hero">
  <div class="hero-grid-overlay"></div>
  <div class="hero-ghost" id="ghostNum">3</div>

  <div class="hero-top">
    <div class="hero-eyebrow">Digital Techniques for Urban Designers</div>
    <h1 class="hero-title">
      DTEQ
      <span class="accent">MODULE 3</span>
    </h1>
    <p class="hero-sub">Rendering, Animation &amp; Video Production — three days of intensive technical mastery across industry standard creative tools.</p>
  </div>

  <div class="hero-bottom">
    <div class="day-strip" id="dayStrip">
      <div>
        <div class="day-strip-label" id="dayLabel">DAY 01</div>
        <div class="day-strip-heading" id="dayHeading">Rendering with Lumion &amp; Twinmotion</div>
      </div>
      <div class="day-strip-meta" id="dayMeta">02 LESSONS &nbsp;·&nbsp; Intro Tutorials</div>
    </div>
  </div>
</section>

<!-- ── CONTENT ── -->
<div class="page-body">


  <!-- ═══ DAY 1 ═══ -->
  <div class="day-panel active" id="day-1">

    <div class="lesson" id="l1-1">
      <div class="lesson-meta-row">
        <span class="lesson-index">01_01</span>
        <div class="lesson-line"></div>
      </div>
      <h2 class="lesson-title">Introduction to Lumion</h2>

      <div class="video-wrap has-embed">
        <iframe src="https://www.youtube.com/embed/9ORqB6EM8eQ" title="Introduction to Lumion" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      </div>
      <div class="video-footer">
        <span class="vf-title">1.1 — Lumion Interface, Model Setup &amp; First Render</span>
        <span class="vf-dur">VIDEO TUTORIAL</span>
      </div>

      <div class="steps-label">Step-by-Step Tutorial</div>

      <div class="step">
        <div class="step-num">01</div>
        <div class="step-content">
          <div class="step-title">Open Lumion and Start a New Scene</div>
          <div class="step-desc">Launch Lumion and begin with a new scene or template. Choose a simple starting environment so the focus stays on learning the interface, navigation, and basic scene setup before adding detailed assets.</div>
          <div class="step-img">[ Screenshot: Lumion start screen / new scene template selection ]</div>
        </div>
      </div>

      <div class="step">
        <div class="step-num">02</div>
        <div class="step-content">
          <div class="step-title">Import the 3D Model</div>
          <div class="step-desc">Use the Import tool to bring in a model from your design software. After importing, place the model on the terrain and check that the scale, orientation, and ground elevation look correct.</div>
          <div class="step-img">[ Screenshot: Import model panel with imported file selected ]</div>
        </div>
      </div>

      <div class="step">
        <div class="step-num">03</div>
        <div class="step-content">
          <div class="step-title">Navigate Around the Scene</div>
          <div class="step-desc">Practice orbiting, panning, and zooming around the model. Get comfortable moving between aerial views, street-level views, and close-up detail views so you can quickly compose render scenes.</div>
          <div class="step-img">[ Screenshot: Model placed in Lumion scene with navigation view active ]</div>
        </div>
      </div>

      <div class="step">
        <div class="step-num">04</div>
        <div class="step-content">
          <div class="step-title">Apply and Adjust Materials</div>
          <div class="step-desc">Select surfaces and assign Lumion materials such as glass, concrete, asphalt, planting, or metal. Adjust material settings like scale, reflectivity, roughness, and color so the model begins to read as a finished environment.</div>
          <div class="step-img">[ Screenshot: Material library / material settings panel ]</div>
        </div>
      </div>

      <div class="step">
        <div class="step-num">05</div>
        <div class="step-content">
          <div class="step-title">Add Context, Landscape, and Entourage</div>
          <div class="step-desc">Use Lumion’s object library to add trees, people, vehicles, furniture, and site elements. Place these strategically to show scale, activity, and the intended atmosphere of the urban scene.</div>
          <div class="step-img">[ Screenshot: Object library with trees / people added to scene ]</div>
        </div>
      </div>

      <div class="step">
        <div class="step-num">06</div>
        <div class="step-content">
          <div class="step-title">Set Up Camera Views and Render Output</div>
          <div class="step-desc">Move into Photo mode, choose a camera angle, and save the view. Add basic effects like real sky, shadows, reflection, color correction, and exposure. Export a still image once the view feels clear and presentation-ready.</div>
          <div class="step-img">[ Screenshot: Photo mode with effects stack and render button ]</div>
        </div>
      </div>

      <div class="tip">
        <span class="tip-mark">// NOTE</span>
        <p class="tip-text"><strong>Screenshot pass:</strong> After confirming the exact video flow, replace each placeholder with a still from the corresponding moment in the tutorial. The goal is for students to be able to follow the page without constantly rewinding the video.</p>
      </div>
    </div>

    <div class="lesson" id="l1-2">
      <div class="lesson-meta-row">
        <span class="lesson-index">01_02</span>
        <div class="lesson-line"></div>
      </div>
      <h2 class="lesson-title">Introduction to Twinmotion</h2>

      <div class="video-wrap has-embed">
        <iframe src="https://www.youtube.com/embed/EAaHRVTPkIk" title="Introduction to Twinmotion" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      </div>
      <div class="video-footer">
        <span class="vf-title">1.2 — Twinmotion Interface, Import Workflow &amp; Media Export</span>
        <span class="vf-dur">VIDEO TUTORIAL</span>
      </div>

      <div class="steps-label">Step-by-Step Tutorial</div>

      <div class="step">
        <div class="step-num">01</div>
        <div class="step-content">
          <div class="step-title">Open Twinmotion and Start a New Project</div>
          <div class="step-desc">Launch Twinmotion and begin with a new project file. Take a moment to identify the main workspace areas: viewport, scene graph, library, import panel, and media/export tools.</div>
          <div class="step-img">[ Screenshot: Twinmotion opening workspace / interface overview ]</div>
        </div>
      </div>

      <div class="step">
        <div class="step-num">02</div>
        <div class="step-content">
          <div class="step-title">Import or Direct Link a Design Model</div>
          <div class="step-desc">Bring in a model using Import or Direct Link, depending on the source software. Confirm that geometry comes in at the correct size and that the model is positioned correctly in the scene.</div>
          <div class="step-img">[ Screenshot: Import / Direct Link panel with model loaded ]</div>
        </div>
      </div>

      <div class="step">
        <div class="step-num">03</div>
        <div class="step-content">
          <div class="step-title">Assign Materials from the Twinmotion Library</div>
          <div class="step-desc">Drag materials from the library onto the model. Adjust scale, color, reflectivity, and surface qualities so exterior paving, facade materials, landscape, and glazing feel intentional.</div>
          <div class="step-img">[ Screenshot: Material library with material applied to model ]</div>
        </div>
      </div>

      <div class="step">
        <div class="step-num">04</div>
        <div class="step-content">
          <div class="step-title">Add People, Vegetation, and Site Assets</div>
          <div class="step-desc">Use the asset library to populate the scene with trees, people, cars, seating, lighting, and other urban elements. Keep placement purposeful so the entourage supports the design story rather than cluttering the view.</div>
          <div class="step-img">[ Screenshot: Scene with vegetation / people / street assets added ]</div>
        </div>
      </div>

      <div class="step">
        <div class="step-num">05</div>
        <div class="step-content">
          <div class="step-title">Set Lighting, Weather, and Time of Day</div>
          <div class="step-desc">Adjust the sun position, sky, weather, and season settings to create a clear visual mood. Use lighting to emphasize building form, public space, and key circulation areas.</div>
          <div class="step-img">[ Screenshot: Environment settings with sun / weather controls ]</div>
        </div>
      </div>

      <div class="step">
        <div class="step-num">06</div>
        <div class="step-content">
          <div class="step-title">Create Media Views and Export</div>
          <div class="step-desc">Move into the Media tools to save still images, panoramas, or video paths. Compose views with a clear subject, save each camera, and export high-resolution files for presentation or post-production.</div>
          <div class="step-img">[ Screenshot: Media export panel with image / video options ]</div>
        </div>
      </div>

      <div class="tip">
        <span class="tip-mark">// NOTE</span>
        <p class="tip-text"><strong>For this module:</strong> Lumion and Twinmotion should be framed as parallel rendering workflows. Students do not need to master both immediately, but they should understand how each tool imports models, builds scenes, adds realism, and exports presentation media.</p>
      </div>
    </div>

  </div><!-- /day-1 -->

  <!-- ═══ DAY 2 ═══ -->
  <div class="day-panel" id="day-2">

    <div class="lesson" id="l2-1">
      <div class="lesson-meta-row">
        <span class="lesson-index">02_01</span>
        <div class="lesson-line"></div>
      </div>
      <h2 class="lesson-title">After Effects Interface &amp; Project Setup</h2>

      <div class="video-wrap">
        <div class="video-center">
          <div class="play-ring">
            <svg width="18" height="22" viewBox="0 0 18 22" fill="none"><path d="M1 1.5L17 11L1 20.5V1.5Z" fill="#C8FF00"/></svg>
          </div>
          <div class="video-caption-mono">Lesson 01 · Add video embed here</div>
        </div>
      </div>
      <div class="video-footer">
        <span class="vf-title">2.1 — AE Interface &amp; Composition Setup</span>
        <span class="vf-dur">~10 MIN</span>
      </div>

      <div class="steps-label">Step-by-Step Demo</div>

      <div class="step">
        <div class="step-num">01</div>
        <div class="step-content">
          <div class="step-title">Create a New Composition at 1920×1080, 30fps</div>
          <div class="step-desc">Open After Effects → Composition → New Composition. Set Width: 1920, Height: 1080, Frame Rate: 30fps, Duration: 00:00:30:00. Name it "Main_Sequence." This is your master timeline for the urban presentation.</div>
          <div class="step-img">[ Screenshot: AE New Composition dialog with settings filled ]</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">02</div>
        <div class="step-content">
          <div class="step-title">Import Your Lumion / Twinmotion Renders</div>
          <div class="step-desc">File → Import → File (Cmd+I). Select all PNG renders from Day 1. Check Import As: Footage. Drag into the Project panel folder structure. Rename each layer by right-clicking → Rename in the timeline.</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">03</div>
        <div class="step-content">
          <div class="step-title">Organize the Project Panel with Bins</div>
          <div class="step-desc">Create folders: /Renders, /Graphics, /Audio, /Comps. This structure becomes essential as your project grows. Drag imported assets into the appropriate folders. Consistency here will save hours when you're iterating under deadline.</div>
          <div class="step-img">[ Screenshot: AE Project panel with organized folder structure ]</div>
        </div>
      </div>
    </div>

    <div class="lesson" id="l2-2">
      <div class="lesson-meta-row">
        <span class="lesson-index">02_02</span>
        <div class="lesson-line"></div>
      </div>
      <h2 class="lesson-title">Keyframe Animation — Ken Burns &amp; Camera Moves</h2>

      <div class="video-wrap">
        <div class="video-center">
          <div class="play-ring">
            <svg width="18" height="22" viewBox="0 0 18 22" fill="none"><path d="M1 1.5L17 11L1 20.5V1.5Z" fill="#C8FF00"/></svg>
          </div>
          <div class="video-caption-mono">Lesson 02 · Add video embed here</div>
        </div>
      </div>
      <div class="video-footer">
        <span class="vf-title">2.2 — Keyframe Animation &amp; Easing</span>
        <span class="vf-dur">~16 MIN</span>
      </div>

      <div class="steps-label">Step-by-Step Demo</div>

      <div class="step">
        <div class="step-num">01</div>
        <div class="step-content">
          <div class="step-title">Enable the Scale Property Stopwatch</div>
          <div class="step-desc">Select your render layer in the timeline. Press S to reveal the Scale property. Click the stopwatch icon — this creates your first keyframe at the current time marker position. The keyframe diamond appears in the timeline.</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">02</div>
        <div class="step-content">
          <div class="step-title">Set a Slow Zoom: 100% → 108% Over 8 Seconds</div>
          <div class="step-desc">Move the playhead to 8 seconds. Change Scale to 108%. AE automatically creates a second keyframe. This creates a slow push-in that draws viewers into the scene. Keep zoom below 115% to avoid visible pixel degradation.</div>
          <div class="step-img">[ Screenshot: Timeline showing two Scale keyframes 8 seconds apart ]</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">03</div>
        <div class="step-content">
          <div class="step-title">Apply Easy Ease (F9) and Open the Graph Editor</div>
          <div class="step-desc">Select both keyframes. Press F9 for Easy Ease. Open the Graph Editor (wave icon) to see the velocity curve. Pull the Bezier handles to create a slow-start, slow-finish feel — this is the difference between amateur and professional motion.</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">04</div>
        <div class="step-content">
          <div class="step-title">Add a Subtle Pan Using Position Keyframes</div>
          <div class="step-desc">Press P to reveal Position. Set keyframes at 0s and 8s with a 20–30px horizontal drift combined with the zoom. This combined scale + position movement creates a natural "floating camera" feel reminiscent of documentary cinematography.</div>
          <div class="step-img">[ Screenshot: Position and Scale keyframes in Graph Editor ]</div>
        </div>
      </div>
      <div class="tip">
        <span class="tip-mark">// TIP</span>
        <p class="tip-text"><strong>Always combine Scale + Position keyframes.</strong> A zoom alone looks digital; adding even a 15px horizontal drift reads as a real camera operator making an intentional choice.</p>
      </div>
    </div>

    <div class="lesson" id="l2-3">
      <div class="lesson-meta-row">
        <span class="lesson-index">02_03</span>
        <div class="lesson-line"></div>
      </div>
      <h2 class="lesson-title">Animated Diagrams — Drawing On Maps &amp; Plans</h2>

      <div class="video-wrap">
        <div class="video-center">
          <div class="play-ring">
            <svg width="18" height="22" viewBox="0 0 18 22" fill="none"><path d="M1 1.5L17 11L1 20.5V1.5Z" fill="#C8FF00"/></svg>
          </div>
          <div class="video-caption-mono">Lesson 03 · Add video embed here</div>
        </div>
      </div>
      <div class="video-footer">
        <span class="vf-title">2.3 — Animated Site Maps &amp; Diagrams</span>
        <span class="vf-dur">~18 MIN</span>
      </div>

      <div class="steps-label">Step-by-Step Demo</div>

      <div class="step">
        <div class="step-num">01</div>
        <div class="step-content">
          <div class="step-title">Import Your Site Plan as a PNG or AI File</div>
          <div class="step-desc">Drag your base map or plan drawing into the composition. Use Illustrator files (.AI) when possible — they import as editable vector layers. Place it at the bottom of the layer stack. Reduce Opacity to 60–70% to use as an underlay reference.</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">02</div>
        <div class="step-content">
          <div class="step-title">Draw a Shape Layer for a Street Corridor Highlight</div>
          <div class="step-desc">Select the Pen tool. Draw a shape over a key street. Set Fill to None, Stroke to your accent color, stroke width 4px. This shape layer will animate in as a "drawing" motion using Trim Paths.</div>
          <div class="step-img">[ Screenshot: Shape layer drawn over street grid with stroke style ]</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">03</div>
        <div class="step-content">
          <div class="step-title">Animate Using Trim Paths</div>
          <div class="step-desc">Expand Shape layer → Contents → Shape → Add → Trim Paths. Set End to 0% at frame 0, keyframe End to 100% at 2 seconds. Apply Easy Ease. The stroke now "draws itself" across the map — a powerful way to guide viewers through a site narrative.</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">04</div>
        <div class="step-content">
          <div class="step-title">Add Text Labels That Fade In After Each Stroke</div>
          <div class="step-desc">Use the Text tool to add location labels. Set Opacity from 0% to 100% with a 15-frame fade, timed to start after the stroke reaches its destination. Align all labels consistently using AE's Align panel.</div>
          <div class="step-img">[ Screenshot: Finished animated map with stroke path and text labels ]</div>
        </div>
      </div>
    </div>

  </div><!-- /day-2 -->

  <!-- ═══ DAY 3 ═══ -->
  <div class="day-panel" id="day-3">

    <div class="lesson" id="l3-1">
      <div class="lesson-meta-row">
        <span class="lesson-index">03_01</span>
        <div class="lesson-line"></div>
      </div>
      <h2 class="lesson-title">Building the Edit — Sequence Setup &amp; Asset Assembly</h2>

      <div class="video-wrap">
        <div class="video-center">
          <div class="play-ring">
            <svg width="18" height="22" viewBox="0 0 18 22" fill="none"><path d="M1 1.5L17 11L1 20.5V1.5Z" fill="#C8FF00"/></svg>
          </div>
          <div class="video-caption-mono">Lesson 01 · Add video embed here</div>
        </div>
      </div>
      <div class="video-footer">
        <span class="vf-title">3.1 — Premiere Pro Sequence Setup</span>
        <span class="vf-dur">~12 MIN</span>
      </div>

      <div class="steps-label">Step-by-Step Demo</div>

      <div class="step">
        <div class="step-num">01</div>
        <div class="step-content">
          <div class="step-title">Create a New Project and Sequence</div>
          <div class="step-desc">Open Premiere Pro → New Project. Name it with your project title and date. File → New → Sequence. Under Presets, choose Digital DSLR → 1080p → DSLR 1080p30. This matches the AE exports from Day 2 — consistent frame rates prevent sync issues.</div>
          <div class="step-img">[ Screenshot: Premiere Sequence presets panel ]</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">02</div>
        <div class="step-content">
          <div class="step-title">Import All Assets into the Project Panel</div>
          <div class="step-desc">Cmd+I to import. Bring in: rendered AE exports (.MOV or .MP4), Lumion walkthrough video, ambient audio. Create bins in the Project panel: /Video, /Motion Graphics, /Audio, /SFX. Right-click → New Bin to organize.</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">03</div>
        <div class="step-content">
          <div class="step-title">Build the Story Arc in the Timeline</div>
          <div class="step-desc">Drag clips onto V1 in narrative order: Context shot → Site aerial → Street level renders → Animated diagrams → Design proposal → Close. A 3-minute urban presentation: 30s context, 45s existing conditions, 60s proposal, 30s close.</div>
          <div class="step-img">[ Screenshot: Premiere timeline with labeled clip segments on V1 ]</div>
        </div>
      </div>
    </div>

    <div class="lesson" id="l3-2">
      <div class="lesson-meta-row">
        <span class="lesson-index">03_02</span>
        <div class="lesson-line"></div>
      </div>
      <h2 class="lesson-title">Transitions, Titles &amp; Lower Thirds</h2>

      <div class="video-wrap">
        <div class="video-center">
          <div class="play-ring">
            <svg width="18" height="22" viewBox="0 0 18 22" fill="none"><path d="M1 1.5L17 11L1 20.5V1.5Z" fill="#C8FF00"/></svg>
          </div>
          <div class="video-caption-mono">Lesson 02 · Add video embed here</div>
        </div>
      </div>
      <div class="video-footer">
        <span class="vf-title">3.2 — Transitions, Titles &amp; Text Overlays</span>
        <span class="vf-dur">~14 MIN</span>
      </div>

      <div class="steps-label">Step-by-Step Demo</div>

      <div class="step">
        <div class="step-num">01</div>
        <div class="step-content">
          <div class="step-title">Add Cross Dissolves Between Render Clips</div>
          <div class="step-desc">In the Effects panel, search "Cross Dissolve." Drag it to the cut point between two clips on V1. Set duration to 20 frames (right-click → Set Transition Duration). Avoid flashy wipes — cross dissolves are the professional standard for still-image sequences.</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">02</div>
        <div class="step-content">
          <div class="step-title">Create a Title Card Using Essential Graphics</div>
          <div class="step-desc">Window → Essential Graphics → New Layer → Text. Type your project title. Use a clean sans-serif at 72pt for the title, 28pt for subtitle. Place on V2 above a semi-transparent black bar on V1 to ensure legibility over any background.</div>
          <div class="step-img">[ Screenshot: Essential Graphics panel with title text formatted ]</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">03</div>
        <div class="step-content">
          <div class="step-title">Design a Lower Third for Location Labels</div>
          <div class="step-desc">Lower thirds appear in the bottom 20% of the frame. Create a Text layer: bold location name (16pt) + lighter descriptor (12pt, 60% opacity). Animate with a 10-frame slide-in from left using Position keyframes.</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">04</div>
        <div class="step-content">
          <div class="step-title">Save as a Motion Graphics Template (.MOGRT)</div>
          <div class="step-desc">Export → Export as Motion Graphics Template. Save to your local library. Drop it onto the timeline and just change the text each time. Consistency across all labels is what makes a presentation look produced.</div>
          <div class="step-img">[ Screenshot: MOGRT export dialog and template in local library ]</div>
        </div>
      </div>
    </div>

    <div class="lesson" id="l3-3">
      <div class="lesson-meta-row">
        <span class="lesson-index">03_03</span>
        <div class="lesson-line"></div>
      </div>
      <h2 class="lesson-title">Color Grading &amp; Final Export</h2>

      <div class="video-wrap">
        <div class="video-center">
          <div class="play-ring">
            <svg width="18" height="22" viewBox="0 0 18 22" fill="none"><path d="M1 1.5L17 11L1 20.5V1.5Z" fill="#C8FF00"/></svg>
          </div>
          <div class="video-caption-mono">Lesson 03 · Add video embed here</div>
        </div>
      </div>
      <div class="video-footer">
        <span class="vf-title">3.3 — Color Grading &amp; H.264 Export</span>
        <span class="vf-dur">~11 MIN</span>
      </div>

      <div class="steps-label">Step-by-Step Demo</div>

      <div class="step">
        <div class="step-num">01</div>
        <div class="step-content">
          <div class="step-title">Open the Lumetri Color Panel</div>
          <div class="step-desc">Window → Lumetri Color. In the Basic Correction tab: Contrast +15, Highlights -10 to recover blown-out sky, Shadows +8 to lift detail in building undersides. These three adjustments alone transform a flat render into a finished image.</div>
          <div class="step-img">[ Screenshot: Lumetri Color panel — Basic Correction sliders adjusted ]</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">02</div>
        <div class="step-content">
          <div class="step-title">Apply a Subtle Creative LUT</div>
          <div class="step-desc">In the Creative tab, click the Look dropdown → Browse. Apply a cinematic LUT at 40–60% intensity. For urban presentations, cool-toned teal/orange grades read as "city documentary." Avoid heavy filters — subtle is professional.</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">03</div>
        <div class="step-content">
          <div class="step-title">Apply Grade to All Clips via Adjustment Layer</div>
          <div class="step-desc">Project panel → New Item → Adjustment Layer. Place on V2 spanning the full sequence. Apply Lumetri Color to the adjustment layer. Every clip below inherits the grade — change it once, change it everywhere.</div>
          <div class="step-img">[ Screenshot: Adjustment layer spanning full timeline on V2 ]</div>
        </div>
      </div>
      <div class="step">
        <div class="step-num">04</div>
        <div class="step-content">
          <div class="step-title">Export as H.264 at High Bitrate for Submission</div>
          <div class="step-desc">File → Export → Media (Cmd+M). Format: H.264. Preset: Match Source – High Bitrate. Target Bitrate: 20 Mbps, Max: 25 Mbps. Send to Media Encoder for background encoding. Always keep a lossless ProRes 422 master before compressing.</div>
        </div>
      </div>
      <div class="tip">
        <span class="tip-mark">// EXPORT</span>
        <p class="tip-text"><strong>Submission settings:</strong> H.264 at 20Mbps for competition portals (Vimeo, online submissions). 15Mbps is sufficient for screen-only presentations. Always export a ProRes 422 master copy first — never compress directly from your timeline without a lossless backup.</p>
      </div>
    </div>

  </div><!-- /day-3 -->

</div><!-- /page-body -->

<!-- ── BOTTOM TAB BAR ── -->
<nav class="tab-bar">
  <button class="tab-btn active" onclick="switchDay(1,this)">
    <span class="t-label">[01_RENDERING]</span>
    <span class="t-sub">Lumion &amp; Twinmotion</span>
  </button>
  <button class="tab-btn" onclick="switchDay(2,this)">
    <span class="t-label">[02_ANIMATION]</span>
    <span class="t-sub">After Effects</span>
  </button>
  <button class="tab-btn" onclick="switchDay(3,this)">
    <span class="t-label">[03_VIDEO]</span>
    <span class="t-sub">Premiere Pro</span>
  </button>
</nav>

<script>
  const days = {
    1: { ghost: '1', label: 'DAY 01', heading: 'Rendering with Lumion &amp; Twinmotion', meta: '02 LESSONS &nbsp;·&nbsp; Intro Tutorials' },
    2: { ghost: '2', label: 'DAY 02', heading: 'Animation with After Effects',           meta: '03 LESSONS &nbsp;·&nbsp; Est. 55m' },
    3: { ghost: '3', label: 'DAY 03', heading: 'Video Editing with Premiere Pro',        meta: '03 LESSONS &nbsp;·&nbsp; Est. 45m' }
  };

  function switchDay(n, btn) {
    document.querySelectorAll('.day-panel').forEach(p => p.classList.remove('active'));
    document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
    document.getElementById('day-' + n).classList.add('active');
    btn.classList.add('active');

    const d = days[n];
    document.getElementById('ghostNum').textContent = d.ghost;
    document.getElementById('dayLabel').textContent = d.label;
    document.getElementById('dayHeading').innerHTML = d.heading;
    document.getElementById('dayMeta').innerHTML = d.meta;

    window.scrollTo({ top: 0, behavior: 'smooth' });
  }
</script>
</body>
</html>
