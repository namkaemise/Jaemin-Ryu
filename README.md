<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>나를 죽이려는 SSS급 킬러의 상태창이 보인다</title>

# PROJECT STRUCTURE

<img src="https://raw.githubusercontent.com/namkaemise/Jaemin-Ryu/refs/heads/main/1784443852902.jpg" width="90%"></img>

***
# GENERAL REQUIREMENTS

• HTML + CSS + Vanilla JavaScript only.
• No frameworks.
• Responsive design.
• Optimized for GitHub Pages.
• Clean folder structure.
• Easy to maintain.
• Reusable components.
• Modern coding standards.

The website should be expandable by simply creating additional HTML files inside the posts folder.

***
# WEBSITE CONCEPT

This website is a blog-style character archive for Crak AI.

The atmosphere should feel like an official game encyclopedia mixed with a premium character database.

It should combine the feeling of

• anime visual novel
• modern game UI
• Korean web novel character pages
• elegant blog layout

without looking overly flashy.

***
# BACKGROUND DESIGN

.body {
  margin: 0;
  min-height: 100vh;
  background-color: #black;
  color: black;
}

/* 파티클 */
.particles{
    position:fixed;
    inset:0;
    pointer-events:none;
}

.particles span{
    position:absolute;
    width:3px;height:3px;
    background:white;
    border-radius:50%;
    opacity:0.15;
    animation:float 20s linear infinite;
}

@keyframes float{
    from{transform:translateY(100vh);}
    to{transform:translateY(-10vh);}
}

***
# COLOR PALETTE

Primary:
Light Gray

Secondary:
Concrete Gray

Cards:
White

Accent:
Soft Gray

Text:
Black (#111111)

Secondary Text:
Dark Gray

Avoid colorful gradients.

Avoid neon colors.

***
# TYPOGRAPHY

All visible text should use black or dark gray.

Use elegant Korean-friendly typography.

Titles should feel sophisticated.

Body text should prioritize readability.

***
# BLOG STYLE

The homepage should contain

• Hero Banner
• Website Title
• Search Box
• Category Filter
• Latest Characters
• Popular Characters
• Tags
• Footer

Each post card should include

• Thumbnail
• Character Name
• Short Introduction
• Tags
• Date

Hover animations should be smooth and elegant.

***
# CHARACTER PAGE

Each character page should include

<img src="https://raw.githubusercontent.com/namkaemise/Jaemin-Ryu/refs/heads/main/1784444402162.webp" width="90%"></img>

Character Name

Tags

Creation Date

Author

Character Introduction

Appearance

Personality

Background Story

Relationships

Trivia

Gallery

Quotes

Navigation
(Previous / Next Character)

***
# SIDEBAR

Include

Recent Posts

Popular Characters

Categories

Tags

Search

***
# CARDS

Use glassmorphism cards.

White or light gray background.

Rounded corners.

Soft shadow.

90~95% opacity.

Premium appearance.

***
# ANIMATIONS

Use smooth fade-in animations.

Smooth scrolling.

Hover animations.

Parallax scrolling.

Sticky navigation bar.

Back-to-top button.

Loading animation.

***
# ENVIRONMENTAL EFFECTS

Create subtle animated environmental effects using CSS and HTML5 Canvas.

Do NOT use external libraries.

Effects include

• small floating fire embers
• glowing sparks
• drifting ash particles
• floating dust
• subtle smoke haze near the screen edges

The movement should be random.

The particle density should remain low.

Particles should appear

Above the background

Behind the content

The animation should remain smooth (60fps if possible).

The atmosphere should resemble

• ruined abandoned building
• cinematic anime scene
• post-apocalyptic ambience
• quiet emotional storytelling

***
# VISUAL STYLE

The website should feel

Minimal

Modern

Elegant

Premium

Immersive

Anime-inspired

Game Encyclopedia

Visual Novel

Character Archive

Magazine Layout

***
# CONTENT LANGUAGE

IMPORTANT

All visible website text must be written entirely in Korean.

This includes

Menus

Buttons

Headings

Labels

Descriptions

Placeholder text

Sample articles

Search placeholder

Footer

Navigation

Everything shown to users.

***
# CODE LANGUAGE

Keep

File names

Variable names

Function names

CSS classes

IDs

Comments

entirely in English.

    </script>
</body>
</html>
