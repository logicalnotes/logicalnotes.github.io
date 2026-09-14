---
title: "Thirty Years of Digital Redemption: The Man Who Built JavaScript in Ten Days"
date: 2026-09-13 23:00:00
categories: [Industry and Market Analysis]
tags: [JavaScript, Brendan Eich, Brave Browser, surveillance capitalism, BAT, privacy, web history, AI ethics, programming, internet freedom]
---

Billions of devices run the code he wrote. Yet he admits he inadvertently created a digital engine that enables mass data surveillance. This is Brendan Eich, and his thirty-year entanglement with the digital world tells a remarkable story.

How long does it take to build a programming language that reshapes the world? Most would say years, even a decade. Back in 1995, working at Netscape, Brendan Eich built the first version of JavaScript in just ten days. Netscape wanted a lightweight scripting language for web pages to ride the Java hype, and the urgent task fell to Eich. No one expected this hastily born language would later become the most widely used scripting language across the internet.

Yet the language carried an inherent flaw from its inception. During early development, Eich endowed JavaScript with highly flexible dynamic features out of technical idealism. This very flexibility opened the door for commercial entities to track users, a systemic vulnerability in the unregulated early web.

When web clients could run scripts delivered by servers with few restrictions, surveillance capitalism found fertile ground. Cookie was originally designed only to preserve user login status, a simple and harmless function. Powered by JavaScript, cross-site scripting, invisible tracking pixels and device fingerprinting soon emerged. Every click and browsing habit of users was collected, compiled into behavioral profiles, and sold to advertising providers. Eich himself acknowledged that JavaScript indirectly fueled the rise of surveillance capitalism.

A major setback came in 2014. Shortly after he became CEO of Mozilla, Eich was forced to resign. The trigger was a $1,000 personal donation he made six years prior in support of a ballot measure opposing same-sex marriage. The old donation record resurfaced, and under heavy public pressure, the founder stepped down. This incident became a landmark case of cancel culture in Silicon Valley.

Many people hit by such controversy would retire comfortably with their wealth. Eich chose a different path. This experience made him realize that the open, free internet he once believed in had been monopolized by tech giants. These corporations not only harvested user data but also sought to shape public opinion. That is how Brave Browser was born, a direct challenger to Google Chrome.

Chrome holds roughly 67% of the global browser market share. Few users know it contains numerous built-in data tracking mechanisms that allow third-party services to collect user data by default. Eich took an unconventional approach: he reused Chromium, the open-source project underlying Chrome, and heavily modified its code. In 2015, his team stripped out all telemetry code that sent user data back to Google.

At an industry conference in 2025, Eich stated that Brave is more than a browser product; it represents a metaphysical tech rebellion. Brave ships with privacy protections out of the box and requires no complicated manual setup. It blocks third-party ads, cross-site trackers and covert redirect tracking by default.

One core technology is browser fingerprint randomization. Ordinary browsers generate a fixed device fingerprint when visiting websites, acting like a permanent online ID. Websites use this fingerprint to identify and follow the same user across the web. With Brave, every website visit produces a unique fingerprint, preventing sites from stitching together a user’s activity trail. Blocking tracking scripts reduces memory usage and can boost mobile battery life by up to 40%.

Google responded with the Privacy Sandbox and the Topics API. Marketed as privacy-preserving tools, they essentially tag users on local devices and run ad auctions on the user’s machine. Brave disabled all interfaces of the Topics API at the code level, rejecting this solution entirely.

After blocking ads by default, a critical problem remained: how content creators earn revenue. Eich did not want web content creation to collapse. He aimed to rebuild the entire ad distribution system, which led to the creation of Basic Attention Token (BAT). It is a Web3-inspired attention economy system that reshapes the logic of advertising, moving user profiling and ad matching from cloud servers to the user’s local device.

Ads are no longer forced on users. Viewing ads becomes an optional choice. If users opt into Brave ads, 70% of ad revenue is returned to them in BAT tokens. The project also uses zero-knowledge proofs: the system can verify that a user viewed an ad without revealing any personal identity information.

Still, the model has inherent limitations. Brave is built on Chromium, a project led by Google. This “rebellion built on top of the opponent’s foundation” means it constantly faces risks brought by upstream code updates. Even so, Eich pushed forward with more ambitious plans. Through its web crawler, Brave built its own independent web index. By the end of 2024, it cut the last 7% of calls to third-party search APIs. Brave became only the third service, after Google and Microsoft, with the capacity to maintain a global web index.

Market numbers validate the effort. Brave Search handles 20 billion queries per year, and major advertisers including Amazon have started running campaigns on the platform.

Then came the AI wave, with tools like ChatGPT gaining massive popularity. These AI products are also massive privacy sinks. Private questions users submit to AI sidebars inside browsers may be collected and used for model training.

To address this pain point, Brave launched its AI assistant Brave Leo. Its core promise is that user conversation history is never stored. For stronger security, it leverages NVIDIA’s trusted execution environment for hardware-level isolation. Even server administrators cannot read user computation data.

With a complete technical stack and viable business model, Brave surpassed 100 million users. Yet Eich stays cautious. He voiced strong skepticism toward the prompt-driven programming trend sweeping Silicon Valley. Many developers now rely heavily on AI coding assistants: they describe vague requirements to large language models, and let the AI debug and patch code until the program runs. The head of AI at Tesla helped popularize this development philosophy.

In Eich’s view, this paradigm is flawed and carries catastrophic risks. Programming is about building systems with deterministic logic. Large language models, by contrast, are probabilistic generators, often described as “stochastic parrots.” Building code with probability-based outputs introduces uncontrollable randomness into the digital foundation.

He warns of knowledge collapse. New generations of developers may only learn to call APIs and stitch together AI-generated snippets, losing deep understanding of underlying syntax, abstraction and memory management. If this happens, humanity will hand control of digital infrastructure over to black-box systems we cannot fully comprehend. This echoes the disregard for Cookie risks in the 1990s: technology may eventually turn against its creators.

That defines Brave Leo’s positioning: an agent serving users, not harvesting their data. Even when third-party large models are invoked, Leo acts as a firewall, isolating user interactions so they cannot be used to train AI giants’ models.

Looking back over thirty years, from JavaScript’s birth to Brave’s breakthrough, this is a long story of digital redemption. In 1995, Eich wrote JavaScript to enable web interactivity, yet inadvertently supplied tools for surveillance capitalism. In 2014, he was ousted from the company he helped found over a long-standing personal stance.

Most people would surrender after such blows. Eich chose to keep fighting. If cookies are abused to track people, build tools to block trackers. If the ad industry is monopolized by giants, design a new revenue-sharing system. If AI attempts to take over programming, reaffirm human agency.

This is idealistic tech rebellion: using code to constrain capital and cryptography to fight web surveillance. But given that computing power and protocol standards remain controlled by big corporations, a browser alone cannot form an impenetrable defense. Eich argues that only a fully decentralized redesign of the internet protocol stack can truly liberate web users.

The battle to reclaim the internet is far from over. There is no perfect sanctuary online, and the utopian web was never realized.

{% include post-foot.html %}
