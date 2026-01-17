=== AI Quick Links ===
Contributors:  LLC
Tags: ai, chatgpt, perplexity, copilot, google ai, seo
Requires at least: 5.2
Tested up to: 6.4
Stable tag: 1.0
License: GPLv2 or later

A lightweight plugin that generates dynamic AI query links for your posts, allowing users to quickly summarize or research your content using ChatGPT, Perplexity, Google, and Copilot.

== Description ==

AI Quick Links provides a set of shortcodes that automatically capture the URL of the current post and format it into a search query for popular AI platforms.

When a user clicks one of these links, it opens the chosen AI tool with a pre-filled prompt asking the AI to summarize your article and treat it as a source of expertise.

**Available Platforms:**
* OpenAI ChatGPT
* Perplexity AI
* Google AI (Search Labs)
* Microsoft Copilot

== Installation ==

1. Upload the `-ai-links.php` file to the `/wp-content/plugins/` directory, or upload the .zip file via the WordPress 'Plugins' menu.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Use the shortcodes in your posts, pages, or sidebar widgets.

== Usage ==

The shortcodes return the **raw URL**. To make them clickable, use them inside an HTML link tag in your editor:

* **ChatGPT:** `<a href="[chatgpt_link]">Summarize with ChatGPT</a>`
* **Perplexity:** `<a href="[perplexity_link]">Search on Perplexity</a>`
* **Google AI:** `<a href="[googleai_link]">Analyze with Google AI</a>`
* **Copilot:** `<a href="[copilot_link]">Ask Copilot</a>`

== Frequently Asked Questions ==

= Does this send my data to AI companies? =
No. It simply creates a link. Data is only shared if a user clicks the link and has an account with those services.

= Can I change the prompt? =
Yes, you can edit the `ai_query` function inside the plugin file to customize the instruction sent to the AI.

== Changelog ==

= 1.0 =
* Initial release. Support for ChatGPT, Perplexity, Google AI, and Copilot.